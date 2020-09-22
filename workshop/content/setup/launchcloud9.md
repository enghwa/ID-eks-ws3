+++
title = "Launching the Cloud9 IDE"
date = 2019-10-28T11:40:22+11:00
weight = 2
+++

Today you'll be working in the **AWS Cloud9** IDE.

<!-- We've pre-created two workspaces for you and we've also installed all of the tools that you are going you need for todays labs. -->

Let's get started by launching the **AWS Cloud9** console: [AWS Cloud9 console AP-SOUTHEAST-1](https://us-east-1.console.aws.amazon.com/cloud9/home?region=ap-southeast-1)

- Select **Create environment**
- Name it **eksworkshop**, click Next.
- Choose **"t3.small"** for instance type, take all default values and click **Create environment**
- When it comes up, customize the environment by closing the **welcome tab**
and **lower work area**, and opening a new **terminal** tab in the main work area:
![c9before](/images/c9before.png)

- Your workspace should now look like this:
![c9after](/images/c9after.png)

- If you like this theme, you can choose it yourself by selecting **View / Themes / Solarized / Solarized Dark**
in the Cloud9 workspace menu.

<!-- 
Find the workspace named **EKSLabIDE** and click **Open IDE**:

![pick-your-idea](/images/01pickidea.png) -->

<!-- When you open the **EKSLabIDE** workspace, you'll be presented with a welcome screen that looks something like this: -->

![cloud9-welcome](/images/00-cloud9-welcome.png)

> On the left pane (Blue), any files downloaded to your environment will appear here in the file tree. In the middle (Red) pane, any documents you open will show up here. Test this out by double clicking on README.md in the left pane and edit the file by adding some arbitrary text. Then save it by clicking File and Save. Keyboard shortcuts will work as well. On the bottom, you will see a bash shell (Yellow). For the remainder of the lab, use this shell to enter all commands. You can also customize your Cloud9 environment by changing themes, moving panes around, etc. (if you like the dark theme, you can select it by clicking the gear icon in the upper right then "Themes", and choosing the dark theme).
