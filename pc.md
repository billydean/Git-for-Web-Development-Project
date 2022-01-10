# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [ ] [Download gitbash]() - Windows computers speak in a language called powershell however we will be speaking to our computers in a language called unixshell, in order to all be speaking the same language if you are using a PC you will need to download gitbash and use this program instead of the native command line. Whenever you see an instruction to use the terminal that will be your queue to open up gitbash. On a PC gitbash will be your terminal. 
2. [ ] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [ ] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection. 
4. [ ] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [ ] [Download Slack](https://slack.com/intl/en-ca/help/articles/209038037-Download-Slack-for-Windows) - make sure your slack display name is your `first name` `last name` 
6. [ ] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [ ] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [ ] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
    Git is version control software, and GitHub is a hosting service for git repositories.
2. Why do we create a branch? 
    Creating branches allows team members to work on specific parts of larger projects, such that they can be reviewed and merged individually.
3. What is the purpose of a pull request?
    It communicates to (whoever might be responsible) that you've made changes that need to be reviewed and/or merged.
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
    $ git checkout -b
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
    `git fetch` will download any new changes, branches, etc. from an online repository to your local repository. I guess you'd use this if you want to review different branches (or forks?) from the remote repository in your local repository.
    `git merge` combines changes into a single branch, updating the repository to reflect any new commits
    `git pull` is like `git fetch`, but it automatically merges the downloaded repository content with whatever you have in your local repository. I guess this would be preferred when you just need the current version of your main branch so that you can work on it locally (i.e. when you don't need to decide what to merge or not)
6. What is a merge conflict? How do you resolve a merge conflict? 
    A merge conflict occurs when either contributors make different changes to the same line or when someone deletes a file another contributor has edited. 
    Git will add conflict markers to the code in question, indicating where the conflict begins/ends, as well as which branches are involved in the conflict. In VSC (or whatever editor), decide which change you'd like to keep and delete the rest (along with the conflict markers). Then you should be able to stage and commit your changes like normal.