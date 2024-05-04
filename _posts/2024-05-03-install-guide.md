---
layout: post
title: Install Guide
subtitle: install and run the application
gh-repo: daattali/beautiful-jekyll
---

## Platform and Environment
### 1. Operating System:
- Windwos 10/11
- MacOS
- Linux(may have some issues installing node.js)

### 2. Prerequisites
1. Node.js: Ensure Node.js is installed on your system. You can download it from [nodejs.org](https://nodejs.org/).
2. npm (Node Package Manager): Comes with Node.js, used to manage dependencies.
3. AWS Account: You need an AWS account to use AWS services. Create one at [aws.amazon.com](https://aws.amazon.com/).

**AWS API(code) may not include in this guide**

*******************

### 3. Environment Setup and Run:
#### 1. Clone the repository: Start by cloning the source code from your repository.

In project repo, you can select any option you like to clone the repository.

![image](https://github.com/OSDModeling/OSDModeling-Guide/blob/main/_posts/install_1.png?raw=true")

OR In a new folder, open Terminal/Command Prompt in the folder.

Example:
``
D:\Github\<folder name>
``

Run Command:

``git clone https://github.com/OSDModeling/OSDModeling-Work``

``cd <folder name>``

#### 2. Install Dependencies and Running the Application.

You can go to `frontend` folder and double-click the run.sh/run.bat to auto install and run the application.

When the application runs successfully, React will automatically open your browser.

#### Optional: Deployment
Build the App: Build the production version of your app.
Open Terminal/Command Prompt in the folder. Run command:
`` npm run build``
