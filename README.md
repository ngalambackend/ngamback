# Ngamback

End to End Test for ngalambackend.org Website

## How to test ngalambackend locally
Clone repository to your local computer from private repository (only crew can access)
Remember, after clone make sure you have checkout to `develop` branch. And also, Don't forget to read documentation on README.md

## How to install ?

1. Clone this repo with, following this command :
   ```
   git clone https://github.com/ngalambackend/ngamback.git
   ```
2. Install depedency with `npm install`
3. Run the automate test, following this command :
    ```
    npm run cy:open
    ```
    Or default command :
    ```
    npx cypress open 
    ```
    Or you can run the single spec like this :
    ```
    npx cypress run --spec="cypress/integration/$.spec.js"
    ```

## How to start develop ?

- Make sure that you use git-flow to be more organized in the application work. You can use [GitKraken](https://www.gitkraken.com/ "GitKraken") or [Sourcetree](https://www.sourcetreeapp.com/ "Sourcetree") if it is more convenient with GUI and if it is convenient with the terminal you can visit the following page.
   - [https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow "https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow")
   - https://danielkummer.github.io/git-flow-cheatsheet/
- Create the product folder which you are working on. Example CRM Product, you can create on `integration/crm`. Which means `CRM` is your folder. You can see the folder structure like this picture :
![](https://github.com/ngalambackend/ngamback/blob/master/folder-head.png)
- After that, you can create an automation test folder which you need. Folder structure :
[![](https://github.com/ngalambackend/ngamback/blob/master/sub-folder.png)](https://github.com/ngalambackend/ngamback/blob/master/sub-folder.png)
- Finally, you can create an automatic test file for your next work as seen in the following image:
![](https://github.com/ngalambackend/ngamback/blob/master/test-file.png)
