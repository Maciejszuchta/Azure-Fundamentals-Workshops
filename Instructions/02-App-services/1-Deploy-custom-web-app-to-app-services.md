
# 02 - Deploy custom web app to App Services

In this walkthrough, you will publish changes to ([first task](https://github.com/Maciejszuchta/Azure-Fundamentals-Workshops/blob/main/Instructions/02-App-services/1-Deploy-custom-web-app-to-app-services-in-vs-code.md)) webapp on Windows App Service Plan. Let's dive in!

>**Note** You will need Visual Studio Code to follow alone this demo.

# Task 1: Add some changes to app Index.cshtml file
 1. Open already created project in Visual Studio Code
 2. Navigate to Pages -> Index.cshtml file 
 3. Add some changes to the content of cshtml file 

 ![image](https://user-images.githubusercontent.com/12434636/165066737-287b8caa-3972-4b8a-b7d8-e5986564dd49.png)
    
 4. Hit ctrl+shift+s to save all changes  
 5. Verify if changes are applied locally by opening VSCode terminal and run: `dotnet run` command 

![image](https://user-images.githubusercontent.com/12434636/165068423-4de76d67-57b0-41b2-9f9a-e7b47ffa1822.png)



# Task 2: Publish the updated code from Visual Studio Code
 1. Open the extensions tab in Visual Studio Code 
 ![image](https://user-images.githubusercontent.com/12434636/165068626-e75488cf-fadd-40e5-a4ef-9b85db02c2c7.png)
 2. Search for `Azure Tools` extension
 3. Hit the install button
 ![image](https://user-images.githubusercontent.com/12434636/165069057-8145043f-78cf-4040-b8ae-4e99c1ffdb59.png)  
 4. After the installation is complete more options should be available for use in VSCode sidebar
 ![image](https://user-images.githubusercontent.com/12434636/165069240-ed78c3c3-0c95-4519-be9a-19854ce81e56.png)
 5. Select the Azure icon and log into your account.
 ![image](https://user-images.githubusercontent.com/12434636/165069356-e55f6eb6-1bc4-4994-9ca2-998cb72fe2a0.png)
 6. Under App Service blade choose your subscription and you should see there your WebApp
 7. Right click on your web app and select `Deploy to Web App...` 
 ![image](https://user-images.githubusercontent.com/12434636/165069783-ad92a4da-1556-4f98-a276-c1aff284841d.png)
 8. Confirm the prompt 
 ![image](https://user-images.githubusercontent.com/12434636/165070031-8171b3a5-8a22-462e-85f1-82dbd87776ba.png)
 9. Wait for the deployment to finish.

**Congratulations!** And now if you navigate to the url address of you Web App you will see the changes :)!

>**Note**: To avoid additional costs, you can remove this resource group. Search for resource groups, click your resource group, and then click **Delete resource group**. Verify the name of the resource group and then click **Delete**. Monitor the **Notifications** to see how the delete is proceeding.
