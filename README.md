# InsightUBC

**Due to UBC CS license issue, I'm not able to publish my repo. Any recruiters who is interested looking into the project, please contact me at [`shawn.gu.92@gmail.com`](shawn.gu.92@gmail.com).**

## Introduction

- The website application is built for CRUD through the University of British Columbia's all building & rooms and class record data.
- The backend demonstrated my understanding of the RESTful API and how it connect to the front end.
- All RESTful API are customized, which means we built it from scratch. 
- Front end is built through React. The page simply provides certain ways to interact with the data. 

## Configuring your environment

To start using this project, you need to get your computer configured so you can build and execute the code.
To do this, follow these steps; the specifics of each step (especially the first two) will vary based on which operating system your computer has:

1. [Install git](https://git-scm.com/downloads) (v2.X). After installing you should be able to execute `git --version` on the command line.

1. [Install Node LTS](https://nodejs.org/en/download/) (v14.17.X), which will also install NPM (you should be able to execute `node --version` and `npm --version` on the command line).

1. [Install Yarn](https://yarnpkg.com/en/docs/install) (v1.22+). You should be able to execute `yarn --version` afterwards.

1. Clone your repository by running `git clone REPO_URL` from the command line. You can get the REPO_URL by clicking on the green button on your project repository page on GitHub. Note that due to new department changes you can no longer access private git resources using https and a username and password. You will need to use either [an access token](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) or [SSH](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account).

## Project commands

Once your environment is configured you need to further prepare the project's tooling and dependencies.
In the project folder:

1. `yarn install` to download the packages specified in your project's *package.json* to the *node_modules* directory.

1. `yarn build` to compile your project. You must run this command after making changes to your TypeScript files.

1. `yarn test` to run the test suite.

1. `yarn pretty` to prettify your project code.

## Running and testing from an IDE

IntelliJ Ultimate should be automatically configured the first time you open the project (IntelliJ Ultimate is a free download through their students program)

Data is available here: [JSON data](https://github.com/shhhawn9/InsightUBC/tree/master/data). You can load them on the webpage after start running the application, then use other functions provided.
