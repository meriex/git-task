Explain version control: 
Version control is the practice of tracking and managing changes to software code or files. it's also known as source control or revision control; Version control is also used to protect source code from mistakes as it facilitates a smooth and continuous flow of changes to the code.

Explain difference between git and GitHub: 
Git is a version control system that lets you manage and keep track of changes to source code history, it is designed for coordinating work among programmers, but it can be used to track changes in any set of files. While, 
GitHub is a cloud-based hosting service that lets you manage Git repositories, it is a service that allows developers to host, share, and manage their code files on the internet and also to collaborate with other developers or team members.

List 3 other GitHub alternatives:
1.	SourceForge
2.	Gogs
3.	Gitlab

Explain the difference between git fetch and git pull: 
Git fetch retrieves the latest changes from the remote repository and updates or downloads into your local repository’s but it doesn’t automatically merge it with any of your work or modify what you’re currently working on i.e. your working repository. You have to merge it manually into your work when you’re ready. While,
Git pull, on the other hand, retrieves the latest changes from the remote repository and merges them into your local repository’s working directory automatically

Explain in simple terms git rebase and the command for it: Git rebase is a command in Git that helps you to integrate changes from one branch into another. It determines a series of commits and then cherry-picks them one by one in the same order somewhere else.
The command for git rebase is git rebase "Then write in the name of the branch you want to rebase" e.g. git rebase master, but before running this command you have to make sure you are on the branch you want to commit by using git checkout.

Explain in simple terms git cherry-pick and the command for it: 
Git cherry-pick is a Git command that allows you to apply a specific commit from one branch to another. It is useful when you want to apply a single commit from one branch to another without merging the entire branch.
The command for git cherry pick is git cherry-pick "Then write in the hash of the commit that you want to apply" e.g. git cherry-pick <commit-hash> commit-hash typically consists of a sequence of letters and numbers, and it is used to identify a specific commit in the repository, but before running this command you have to make sure you are on the branch you want to commit by using git checkout.
