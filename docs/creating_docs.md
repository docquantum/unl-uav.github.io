# Creating Documention

This is a useful guide on how to start writing documentation. We will be using git to control what information get in and what information doesn't get in.

***

## Novice
This is indended for people who is less technical about git and github. Just want to publish an documentation. Here is how to do it.

1. Go to [GitHub](https://github.com)
2. Create an account
3. Go to our [Documentation Repo](https://github.com/UNL-UAV/unl-uav.github.io/)
4. Click Issues
5. Create new Issue
6. If applicable select add documentation template.
7. Fill out the form.
8. Attach your information that you want to publish.
9. Submit
10. Wait for it to publish

***

## Advanced
This is for the people who want to get done now and knows git/github.

1. Login to Github
2. Fork the Repository.
3. Use the clone command for your forked repository. (Check how below)
4. Add, Modify, Remove your forked repository with the necessary documents.
5. Create Pull Request on UNL-UAV Repo.

***

## Resources/FAQ
### Git Resources
> Give a man a fish and you feed him for a day; Teach a man to fish and you feed him for a lifetime.

[Try Git](https://try.github.io/)

***

### Markdown Resources

[Learn Markdown](https://www.markdowntutorial.com/)

[Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

[Live Editor](https://markdownlivepreview.com/)

***

### Cloning the Repository
```git clone https://github.com/UNL-UAV/unl-uav.github.io --branch docs```. 

Make sure you have ```--branch docs``` otherwise you will enter in the wrong branch.

***

### Adding Documents
Add all new documents in the ```/docs/``` directory. With the extension of ```.md```. Commit and push.

***

### Deploying
Deploying to the website is as simple as pushing to the docs repository. It will take up to a minute for the website to load and refreash the cache. To bypass the cache you can press either key combination:

```
CTRL+R

Command+R

Shift+F5

Shift+Reload Button

CTRL+F5
```
