# sanusigittask
Version control is a system that manages changes to files over time in a collaborative software development environment. Its primary purposes are to track and coordinate changes made by multiple contributors, provide a history of revisions, and enable the ability to revert to previous states of a project.

Git is a distributed version control system, enabling developers to manage and track changes locally. It facilitates branching, merging, and version history. GitHub is a web-based platform that hosts Git repositories and provides collaboration features. Developers use GitHub to share, collaborate, and contribute to projects. While Git is the underlying technology for version control, GitHub adds a centralized hub for hosting repositories, issue tracking, and collaborative tools. In essence, Git is the engine for version control, while GitHub is the platform that enhances collaboration and project management.

three other github alternatives - SourceForge, Bitbucket, Beanstalk.

git fetch retrieves changes from the remote but doesn't automatically merge them into the local branch, allowing for inspection before merging. In contrast, git pull fetches changes and immediately merges them into the current local branch.

git rebase is a Git command that helps you clean up and organize your commit history. It allows you to move or combine your changes on top of the latest changes in the main branch.
the command for it is git rebase -i HEAD~number of commit to include

git cherry-pick is a Git command that allows you to pick and apply specific commits from one branch and add them to another branch.
the command for it is git cherry-pick <the commit want to pick>

