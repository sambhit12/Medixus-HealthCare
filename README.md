 # PROJECT TITLE

Medixus : Your Trusted Partner in Healthcare Solutions

# INTRODUCTION

Welcome to Medixus, a revolutionary healthcare platform leveraging technology and Azure services to simplify health management. Offering intelligent symptom checking, health tips, and seamless access to nearby healthcare facilities, Medixus empowers users for proactive and informed health decisions effortlessly.

# EXPLORE YOUR WELL-BEING: VISIT Medixus TODAY!

**PROJECT ON AZURE:** https://jolly-dune-0e4212a10.5.azurestaticapps.net/

# PURPOSE

Medixus is dedicated to simplifying healthcare, providing a user-friendly platform for immediate access to reliable health information, intelligent symptom checking, and seamless location-based services. Our goal is to empower individuals to make informed decisions, promoting proactive and personalized health management effortlessly.

# PROBLEM STATEMENT

Accessing reliable health information and guidance is often cumbersome and time-consuming. Individuals face challenges in understanding symptoms, locating nearby healthcare facilities, and receiving immediate assistance. The current healthcare landscape lacks a unified, user-friendly solution. Medixus aims to address this by providing a responsive and intelligent platform that leverages Azure services, offering personalized health insights, and simplifying health management for users.

# PROBLEM DESCRIPTION

Medixus is a revolutionary healthcare platform designed to simplify health management, catering to the need for accessible and intelligent healthcare solutions. Our project addresses the challenge individuals face in navigating the vast landscape of health information, symptom identification, and finding nearby healthcare facilities. By leveraging HTML, CSS, and JavaScript on Visual Studio Code, along with Azure services such as Azure Static Web Apps, Storage Accounts, Maps, and Health Bot, Medixus provides a user-friendly, responsive, and secure experience. The core idea revolves around creating a unified solution that streamlines health-related tasks, ensuring personalized care.
Users can effortlessly check symptoms through an intelligent conversational interface powered by Azure Health Bot, facilitating immediate health insights. The platform's integration with Azure Maps enables users to find nearby healthcare facilities, pharmacies, and clinics conveniently. Medixus caters to a diverse audience seeking reliable health information and guidance, offering tips and insights for proactive health management. By mapping the project's purpose to the identified need for simplified healthcare solutions, Medixus emerges as an inclusive and innovative health hub, seamlessly combining technology and Azure services to enhance user well-being.

# IDE USED :

Visual Studio Code

# TECHNOLOGY USED :

1. HTML

2. CSS

3. Javascript

# AZURE CORE SERVICES USED :

*1. AZURE STATIC WEB APPS :*
  
   Medixus utilizes Azure Static Web Apps to host its platform, ensuring high performance, scalability, and security. This service allows for seamless deployment and delivery of the web application, providing users with a fast and reliable experience.

*2. AZURE STORAGE ACCOUNTS :*
  
   Azure Storage Accounts are employed to efficiently manage and store data within Medixus. This includes user information, health-related data, and other essential details. The use of Azure Storage ensures data integrity, availability, and secure access, contributing to a robust healthcare platform.

# AZURE AI SERVICE USED :

*1. AZURE HEALTHBOT :*

    Medixus leverages the powerful Azure AI Service, specifically the Health Bot, to enhance user interactions and provide intelligent healthcare solutions. The Health Bot enables conversational interactions, allowing users to check symptoms, receive personalized health insights, and seek guidance in real-time. This intelligent chatbot adds a human touch to the platform, contributing to a user-friendly and informative healthcare experience on Medixus.


# STAGE 1 : STEPS FOR MAKING PROJECT ON VSCODE 

*1. Install VSCode:* Download and install Visual Studio Code.

*2. Open VSCode:* Launch VSCode.

*3. Create Folder:* Make a new folder for your project.

*4. Open Folder in VSCode:* Open the folder in VSCode.

*5. Initialize Project:* In the terminal, run npm init -y for a basic package.json.

*6. Install Dependencies:* Install libraries/frameworks with npm install.

*7. Create Files:* Generate HTML, CSS, and JS files.

*8. Write Code:* Use VSCode's editor to write your code.

*9. Save Changes:* Save your work frequently.

*10. Run Your Project:* Test your project using a server or extensions like "Live Server."

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ede874ff17e25989ecfe253de64241d3203b5443/assets/website/Medixus-IndexHtmlPage.png)


# STAGE 2 : MAKE A GITHUB REPOSITORY

*1. Create a GitHub Account:*
Sign up for a GitHub account if you don't have one at GitHub.

*2. Log in to GitHub:*
Log in to your GitHub account.

*3. Click on the "+" Icon:*
In the top right corner of the GitHub page, click on the "+" icon, and select "New repository" from the dropdown menu.

*4. Enter Repository Name:*
Choose a name for your repository. This should be a descriptive and concise name for your project.

*5. Add Description:*
Optionally, provide a short description of your repository.

*6. Initialize this repository with a README (Optional):*
If you want to add a README file immediately, check the "Initialize this repository with a README" option.

*7. Choose a .gitignore:*
If your project uses a specific programming language or framework, you can select a relevant .gitignore file to exclude unnecessary files from version control.

*8. Choose a License:*
If you want to specify a license for your project, select one from the provided options.

*9. Click on "Create Repository":*
Click the green "Create repository" button to create your GitHub repository.

*10. Copy Repository URL:*
Once the repository is created, copy the repository URL. You'll use this URL to connect your local project to the GitHub repository.

# STAGE 3 : STEPS FOR DEPLOYING PROJECT FROM VSCODE TO GITHUB

1. *Initialize Git in Your Project:*
   Open your project in VSCode, open the terminal, and run:
   ```bash
   git init
   ```

2. *Add and Commit Changes:*
   Stage and commit your changes using:
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

3. *Create a New Repository on GitHub:*
   Go to GitHub and create a new repository.

4. *Link Local Repository to GitHub:*
   In the terminal, run:
   ```bash
   git remote add origin <repository_url>
   git branch -M main
   ```

5. *Push Your Code to GitHub:*
   Push your committed changes to the GitHub repository:
   ```bash
   git push -u origin main
   ```
# STAGE 4 : STEPS FOR DEPLOYING WEBSITE ON AZURE STATIC WEB APP

*1. Create an Azure Account:*
Sign up for an Azure account if you don't have one at Azure Portal.

*2. Navigate to Azure Static Web Apps:*
In the Azure Portal, go to the "Create a resource" section and search for "Static Web Apps."

*3. Create a New Static Web App:*
Click on "Static Web Apps" and then "Add." Fill in the required details, including your GitHub repository and branch.

*4. Configure Build Details:*
Configure the build details, such as the build command and output location. This is often set to "build" for many web applications.

*5. Review and Create:*
Review your configuration and click "Review + create." Once validated, click "Create."

*6. Wait for Deployment:*
Azure will deploy your static web app. Wait for the deployment to complete.

*7. Access Your Website:*
Once deployed, go to the Static Web Apps resource in the Azure Portal, find the "URL" under the "Overview" section, and access your website.

**MY WEBSITE URL :** https://jolly-dune-0e4212a10.5.azurestaticapps.net/

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ede874ff17e25989ecfe253de64241d3203b5443/assets/website/Medixus-StaticWebApp.png)

# STAGE 5 : STEPS FOR CREATING AZURE STORAGE ACCOUNTS


*1. Navigate to Azure Portal:*
Go to the Azure Portal and log in.

*2. Create a New Storage Account:*
Click on "Create a resource," search for "Storage account," and select "Storage account - blob, file, table, queue."

*3. Fill in Storage Account Details:*
Provide the required details, including the subscription, resource group (same resource group as static web app), unique storage account name, location, and performance options.

*4. Configure Advanced Settings (Optional):*
Adjust advanced settings like the replication method, access tier, and networking configuration based on your requirements.

*5. Review and Create:*
Review your configuration, click "Review + create," and then click "Create."

*6. Wait for Deployment:*
Azure will deploy your storage account. Wait for the deployment to complete.

*7. Access Storage Account:*
Once deployed, go to the "Storage accounts" section in the Azure Portal, click on your newly created storage account, and explore its settings.

*8. Containers :*
Go to containers in data storage and upload files by drag and drop.

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ede874ff17e25989ecfe253de64241d3203b5443/assets/website/Medixus-Storage1.png)

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ede874ff17e25989ecfe253de64241d3203b5443/assets/website/Medixus-Storage2.png)


# STAGE 7 : STEPS FOR CREATING HEALTH BOT

*1. Azure Portal:*
Log in to the Azure Portal.

*2. Create Health Bot Resource:*
Click "Create a resource," search for "Health Bot," and select "Health Bot."

*3. Fill Details:*
Provide subscription, resource group, region, and a unique name for your Health Bot.

*4. Configure Settings:*
Set messaging endpoint, language, and time zone preferences.

*5. Generate App ID and Password:*
Create a Microsoft App ID and Password for authentication.

*6. Optional Channels Setup:*
If needed, configure channels (e.g., Teams, Web Chat) and obtain credentials.

*7. Review and Create:*
Review settings, click "Review + create," and then "Create."

*8. Wait for Deployment:*
Allow Azure to deploy your Health Bot.

*9. Access Resource:*
In the "Resource groups" section, explore your Health Bot resource.

*10. Configure Scenarios:*
Use the Health Bot management portal to set up health scenarios and prompts.

*11. Test and Integrate:*
Validate your Health Bot within Azure and integrate it into your applications or platforms as required.

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ede874ff17e25989ecfe253de64241d3203b5443/assets/website/Medixus-HealthBot.png)

# STAGE 8 : STEPS FOR INTEGRATING HEALTHBOT TO YOUR WEBSITE
 
 1. Once the resource is created, open the health bot management portal using the provided “Management portal link”.

 2. In the management portal, navigate to “Template Catalog” in the sidebar.

 3. Here, you will find various templates grouped by categories. Select a template that suits your requirements and click on “Open”.

 4. Click on “Import” from the pop-up window to import the selected template.

*5. Get Bot Secret:*
In the Azure Portal, go to your Health Bot resource, navigate to "Channels," and get the Bot Secret.

*6. Configure Web Chat:*
If using Web Chat, include the Bot Secret and your Web Chat secret in your website's code.

*7. Implement Direct Line Integration:*
For a custom integration, use the Direct Line API. Obtain the Direct Line secret from the Azure Portal and implement the integration in your website's code.

*8. Include Health Bot Script:*
Add the Health Bot Web Chat script to your website's HTML. Customize the script with your Bot ID and other relevant details.

*9. Initialize Web Chat:*
In your website's JavaScript, initialize the Web Chat with the required settings, including the Bot ID and Secret.

*10. Handle User Interactions:*
Implement the necessary logic to handle user interactions and messages sent to and received from the Health Bot.

*11. Test Integration:*
Test the Health Bot integration on your website to ensure that user inputs are correctly processed, and responses are displayed.

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/56c1b0d614c79cac5087513efb1ccf95a7c91a2e/assets/website/Medixus-Integration.png)

# MY PROJECT (Medixus) - HOMEPAGE

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ad737e97ef43cf808937f87eb38f62a29aed0768/assets/website/Medixus-HomePage.png)

# MY PROJECT (Medixus) - ABOUTUS

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ad737e97ef43cf808937f87eb38f62a29aed0768/assets/website/Medixus-AboutUs.png)


# MY PROJECT (Medixus) - HEALTHBOT

![image](https://github.com/sambhit12/Medixus-HealthCare/blob/ad737e97ef43cf808937f87eb38f62a29aed0768/assets/website/Medixus-HealthBot2.png)




