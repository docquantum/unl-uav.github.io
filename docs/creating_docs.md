# Creating Documention

This is a useful guide on how to start writing documentation. We will be using git to control what information get in and what information doesn't get in.

## Git Resources

## Markdown Resources

## Cloning Repository
```git clone https://github.com/UNL-UAV/unl-uav.github.io --branch docs```. Make sure you have ```--branch docs``` otherwise you will enter in the wrong branch.

## Adding Documents
Add all new documents in the ```/docs/``` directory. With the extension of ```.md```. Commit and push.

## Deploying
To deploy changes we need to use the mkdocs tool. You can download it [here](https://www.mkdocs.org/). Once you have the tool open the directory and use the command ```mkdocs gh-deploy``` to deploy the changes.
