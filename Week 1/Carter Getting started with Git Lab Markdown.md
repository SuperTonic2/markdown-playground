# Getting started with Git Lab
## Instructions
In this lab, we'll be going through some basic tasks you'll need to do as you manage the GitHub repository for your CollectionBuilder site. The questions below are designed to help you learn and remember what you need to do to perform these tasks, as well as where you can go to look for help.  
## Creating your repository and editing files
**What did you click on to create a new repository in the web interface of Github (i.e., on Github.com)?**  
I went to the "Repositories" tab on my profile page and selected the green "New" button.

**What is the difference between a private and a public repository?**  
A public repository can be viewed and downloaded by anyone on the internet while a private repository can only be viewed by the creator and individuals specifically added to the repository.

**Once your repository has been made and has at least one file, what button do you need to click on the web interface in order to create a new file in your repository?**  
On the repository home page, I selected the "Add File" dropdowna and select "Create New File".

**Describe the steps you took to clone your repository on Github Desktop**  
On Github Desktop, I went to File > Clone Repository, went to the URL tab, entered the repository URL, and hit "Clone".

**What is the title of GitHub documentation?**  
GitHub Docs

**What is the URL for GitHub documentation on creating your first repository?**  
https://docs.github.com/en/desktop/overview/creating-your-first-repository-using-github-desktop

**Where is your local repository versus the remote repository?**  
Your local repository is saved to your computer while the remote repository is saved to GitHub's cloud service.

**What happens when you fetch?**  
When you fetch a repository, you are syncing the local repository with the remote repository so that any changes that have been made to the remote repository (typically by other users) are showing on the local repository.

**What happens when you pull changes/commits?**  
When you pull changes/commits, you are taking the changes/commits from a remote repository and incorporating them into the corresponding branch in the local repository.

**When working on GitHub Desktop, what order should you generally perform push, pull, and fetch?**
You should fetch first to understand how the remote repository differs from the local repository. Then, you should pull the remote repository into the local repository. Finally, after you have made the desired edits to your local repository, you should commit and then push to the remote repository.

**What happens when you push commits from your local repository?**  
When you push commits from your local repository, you will be changing the remote repository to match the changes made in the local repository.

**What is the URL for the Github glossary?**  
https://docs.github.com/en/get-started/learning-about-github/github-glossary

**Where can you find a list of your commits?**  
To view a list of Github commits on Github Desktop, open the repository and go to the "History" tab. On Github's online interface, open the repository home page and click the "[number of commits] Commits" button.

**What is the URL for documentation on reverting a commit?**  
https://docs.github.com/en/desktop/managing-commits/reverting-a-commit-in-github-desktop

**How do you revert a commit?**  
On Github desktop, go to the "History" tab, right click the change you want to revert, and select "Revert Changes in Commit".

## Git-flavored markdown
**What is the name of the page or URL in GitHub documentation where there's information on how to format your Markdown for GitHub?**  
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

**What precedes a second-level heading in Github markdown?**  
Two pound symbols (##) followed by a space and then the text.  
## This is a second-level heading!

**How do you indicate text that has been struckthrough?**  
Two tildes symbols at the beginning and end of the text.  
~~This is struckthrough text~~

**How do you create a hyperlink in your markdown?**  
You place the text you want to dispaly in square brackets followed by the URL in paratheses.  
[This is a link to a cute cat video!](https://www.youtube.com/watch?v=tGdL-34L-GE)

**How do you link to a section in the same or another markdown file?**  
You can link to a section in the same or another markdown file by opening the markdown file, selecting the link symbol next to the header you want to link to, right-cliking, copying the link, and then adding that link using the same format you'd use for a hyperlink.  
[This is a link to another section of this document](https://github.com/SuperTonic2/markdown-playground/blob/main/Carter%20Getting%20started%20with%20Git%20Lab%20Markdown.md#getting-started-with-git-lab)

**What are the three possible symbols for indicating an unordered list?**  
An asterisk (*), a dash (-) or a plus sign (+).
* List
* List

- List
- List

+ List
+ List

**Format the following text into a footnote:**
*Bonus: make "William and Mary" a hyperlink to W&M's website.*
Main text: Alex Wingate went to [William and Mary](https://www.wm.edu/).[^1]
[^1]: William and Mary is a university in Williamsburg, VA founded in 1693.  