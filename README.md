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

1. Click **Use this template** on GitHub to create a new repository from this template.
2. Use GitHub Desktop to clone the new repo to your system.

If that does not work automatically,
1. Go to the home page of your new repo
2. Click the green Code button
3. Select https
4. Copy the URL
5. Go into GitHub Desktop and click Add, then Clone repository
6. Paste the URL into the dialog box
7. Set Local Path to where you want the new project on your local system.
8. Click Clone

#### To start a new project

1. Download zip and unzip
2. Rename what you want, like `test`
3. GHD: Create repository where you want it, Give it same name
4. Copy downloaded `test` folder over the created one
5. Go to GHD. It should show all the files as changed.
6. Add a description, like “initial push”
7. Publish repository
8. Go to GItHub website. Your project should be there.

#### To use an existing project

1. Go to your project's folder. It should end in .appStudio
2. Copy that folder into the cloned template folder
3. Open the project as usual.

### Try CoPilot

1. In your repo's home page, click on the CoPilot icon at the top of the screen.
2. Make sure the repo name is set to the name of your new repo, not `All repositories`.
3. Enter the following into the `Ask anything` prompt box:
```
Using .github/copilot-instructions.md, make a branch with the following changes:
Modify Form1 by adding a Bootstrap 5 button named Button1, labeled "Click Me".
When clicked, it should display a message box with "Hello World".
```
