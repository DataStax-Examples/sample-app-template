<!--- 
WARNING: You must remove all comments (except exclusion tags) in your Sample App README.md 
--->

<!--- Use the below tags to exclude content from the Astra DB UI --->
<!--- STARTEXCLUDE --->
<!--- ENDEXCLUDE --->

<!--- 
The Project Name, duration and skillLevel, make sure these values match
the astra.json

Update the INSTRUCTIONS_LINK with the absolute path to your INSTRUCTIONS.md
--->
# {name}
*{duration}, {skillLevel}, [Start Building](INSTRUCTIONS_LINK)*

<!---  
A short few sentences describing what is the purpose of the example and what the user will learn

e.g.
This application shows how to use configure your NodeJs application to connect to DDAC/Cassandra/DSE or an Apollo database at runtime.

This should be the same as the "description" key in the astra.json file. 
--->
{description}

<!--- 
heroImage example:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-sample-app-default.png)

Be sure to include 2 line breaks before and after the hero image
-->
{heroImage}

<!--- 
A list of the top objectives that are being demonstrated by this sample

e.g.
* To demonstrate how to specify at runtime between a standard (DSE/DDAC/C*) client configuration and an Apollo configuration for the same application.
--->
## Objectives
* {objective 1}
  
<!--- 
A description of how this sample works and how it demonstrates the objectives outlined above
--->  
## How this works
{howThisWorks}

<!--- 
Replace INSTRUCTIONS_LINK with an absolute path link to your instructions
--->
## Get Started
To build and play with this app, follow the build instructions that are located here: [INSTRUCTIONS_LINK](INSTRUCTIONS_LINK)

<!--- Everything below Get Started should be excluded from the Astra UI --->
<!--- STARTEXCLUDE --->
<!--- ENDEXCLUDE --->

<!--- Enter the repository name --->
# Running {name}
Follow the instructions below to get started.

<!--- 
Modify this section as needed, however always include the Astra DB setup parts
--->
## Prerequisites
Let's do some initial setup by creating a serverless(!) database.

### DataStax Astra
<!--- enter a unique UTM_CODE for your sample app below --->
1. Create a [DataStax Astra account](https://astra.datastax.com/register?utm_source=github&utm_medium=referral&utm_campaign=UTM_CODE) if you don't already have one:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-register-basic-auth.png)

2. On the home page. Locate the button **`Create Database`**
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-dashboard.png)

3. Locate the **`Get Started`** button to continue
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-select-plan.png)

4. Define a **database name**, **keyspace name** and select a database **region**, then click **create database**.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-create-db.png)

5. Your Astra DB will be ready when the status will change from *`Pending`* to **`Active`** 💥💥💥 
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-active.png)

6. After your database is provisioned, we need to generate an Application Token for our App. Go to the `Settings` tab in the database home screen.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-settings.png)

1. Select `Admin User` for the role for this Sample App and then generate the token. Download the CSV so that we can use the credentials we need later.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-settings-token.png)

<!--- 
When connecting via an API, use the connect screen step below
--->
1. After you have your Application Token, head to the database connect screen and copy the connection information that we'll need later. We'll replace `ASTRA_DB_APPLICATION_TOKEN` with the `Token` value that is part of your Application Token.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-connect.png)

<!--- 
When connecting with a secure bundle, use the service account steps below
--->
1. After you have your Application Token, head to the database connect screen and select the driver connection that we need. Go ahead and download the `Secure Bundle` for the driver.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-connect-bundle.png)

9. Make note of where to use the `Client Id` and `Client Secret` that is part of the Application Token that we generated earlier.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-connect-bundle-driver.png)

### Github
<!-- Enter your GITHUB_URL below -->
1. Click `Use this template` at the top of the [GitHub Repository](GITHUB_URL):
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-use-template.png)

2. Enter a repository name and click 'Create repository from template':
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-create-repository.png)

3. Clone the repository:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-clone.png)

<!--- 
Include locally as a minimum so that folks will
create an Astra DB and use your repository as a template.

Remove paths that you don't need.
--->
## 🚀 Getting Started Paths:
*Make sure you've completed the [prerequisites](#prerequisites) before starting this step*
  - [Running on your local machine](#running-on-your-local-machine)
  - [Running on Gitpod](#running-on-gitpod)
  - [Deploying to Vercel](#deploying-to-vercel)
  - [Deploying to Netlify](#deploying-to-netlify)

<!--- 
Include the appropriate commands to run the app locally (post cloning). If you're using
Docker or something similar, include that setup here.
--->
### Running on your local machine


<!--- 
Include Gitpod where possible, it provides a good DX for experimentation 
--->
### Running on Gitpod
<!-- Enter your GITPOD_LINK below -->
1. Click the 'Open in Gitpod' link:
[![Open in IDE](https://gitpod.io/button/open-in-gitpod.svg)](GITPOD_LINK)

### Deploying to Vercel
<!-- Enter your VERCEL_URL below -->
1. Click the 'Deploy' button:
[![Deploy with Vercel](https://vercel.com/button)](VERCEL_URL)

### Deploying to Netlify
<!-- Enter your NETLIFY_URL below -->
1. Click the 'Deploy to Netlify' button:
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](NETLIFY_URL)
