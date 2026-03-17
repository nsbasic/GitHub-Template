# GitHub-Template
A template for NSB/AppStudio projects, ready to use with CoPilot

## Usage

This repository is a starting-point template for [NSB/AppStudio](https://www.nsbasic.com/) projects.

### Contents

- `LICENSE` - the license for this template, not necessarily the same as your license, which will be in you 
- `README.md` - this document. Update it with general information for your own project.
- `GitHub-Template,appstudio/GitHub-Template.project` – AppStudio project file (JavaScript, one empty form)
- `GitHub-Template.appstudio/forms/Form1/Form1.json` – Form definition File for Form1
- `GitHub-Template.appstudio/forms/Form1/Form1.js` – JavaScript code file for Form1
- `GitHub-Template.appstudio/properties` – build option files for your project

### Prerequisites

1. A [GitHub account](https://github.com/)
2. [Github Desktop](https://desktop.github.com/download/) needs to be installed.
3. To use CoPilot, you need a [CoPilot subscription](https://github.com/features/copilot/plans). The Pro plan is much more powerful than the free plan.

### Getting Started

#### To start a new project

1. Using the green **Code** button, click **Download ZIP** and unzip on your local system.
2. Rename it what you want, like `test`.
3. In GitHub Desktop, select **New New Repository** from the **File** menu.
4. Give it the same name (`test`) and set the local path where you want it.
5. Click on **Create Repository**
6. Copy the downloaded `test` folder over the `test` folder in the new repo.
7. GitHub Desktop should show all the files as changed.
8. Add a name for the push, like “initial push”
9. Publish repository
10. Go to GitHub website. Your project should be there.

#### To use an existing project

1. Do the above steps to start a new project.
2. Go to your project's folder. It should end in .appStudio
3. Copy that folder into the cloned template folder
4. Remove the .appstudio folder that was there before.
5. Add a name for the push, like “initial push”
6. Publish repository
7. Go to GitHub website. Your project should be there.

### Try CoPilot

1. In your repo's home page, click on the **Agents** tab.
2. Paste the following into the `Describe a coding task to work on` prompt box, then click on the **Start task** button
```
Modify Form1 by adding a Bootstrap 5 button named Button1, labeled "Click Me".
When clicked, it should display a message box with "Hello World".
```
You can click on the action to watch it work.
When complete, merge the changes into your project.

**Important**

When using CoPilot to modify your code, make sure your project is not open in AppStudio.
Your changes could be overwritten.
