# BMI6016_SDOH
Group project for BMI 6016

'''
SOME BEST PRACTICES, PER THE INTERNET:

THIS LINK: https://www.reddit.com/r/bioinformatics/comments/18alwyn/best_practices_for_putting_a_project_on_github/ 

THIS LINK: https://dev.to/pwd9000/github-repository-best-practices-23ck

THIS LINK: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424

AND SOME HIGHLIGHTS:

Favor branching over forking
To streamline collaboration, we recommend that regular collaborators work from a single repository, creating pull requests between branches instead of between repositories. Forking is best suited for accepting contributions from people that are unaffiliated with a project, such as open-source contributors. To maintain quality of important branches, such as main, while using a branching workflow, you can use protected branches with required status checks and pull request reviews. For more information, see About protected branches.

Embrace a consistent branching strategy
A consistent branching strategy is crucial for effective collaboration and code management. It provides a clear structure for how code changes are managed and integrated into the codebase. It also helps to maintain a clean and stable codebase, and reduces the risk of conflicts and errors. There are several branching strategies that you can adopt, such as:

Gitflow: A popular branching strategy that uses two main branches, master and develop, and a variety of supporting branches to aid parallel development and release management.
Feature Branching: A strategy where each feature or task is developed in a dedicated branch, and then merged into the main branch once complete.
Trunk-Based Development: A strategy where all changes are made directly to the main branch, and feature toggles or other techniques are used to manage incomplete features.
GitHub Flow: A lightweight branching strategy that uses a single main branch, and feature branches are created for each new feature or bug fix.
GitLab Flow: A strategy similar to GitHub Flow, but with the addition of environments and release branches for managing the release process.
Release Branching: A strategy where a release branch is created from the main branch to prepare for a new release, and then merged back into the main branch once the release is complete.
Environment Branching: A strategy where branches are used to manage different environments, such as development, staging and production.
When choosing a branching strategy, it's important to consider the needs of your team and project. You should choose a strategy that is simple, flexible, and scalable, and that supports the way your team works. You should also document the branching strategy and make sure that everyone on the team understands how it works and follows it consistently.

You can get more information on branching and how to use branches by checking the official documentation: GitHub repo branch documentation  

Use Git Large File Storage
To optimize performance, GitHub limits the sizes of files allowed in repositories. For more information, see About large files on GitHub. To track large files in a Git repository, we recommend using Git Large File Storage (Git LFS). For more information, see About Git Large File Storage.

Tip 6: Maintain a Clean Commit History
A clean commit history is crucial for effective collaboration and code management. It provides a clear record of the changes that have been made to the codebase, and helps to maintain a clean and stable codebase. It also makes it easier to understand the history of the codebase, and reduces the risk of conflicts and errors.

There are several best practices that you can adopt to maintain a clean commit history, such as:

Write descriptive commit messages: Write clear and descriptive commit messages that explain the purpose and context of the changes that have been made.
Use atomic commits: Make small, focused commits that contain a single logical change. This makes it easier to understand the history of the codebase, and reduces the risk of conflicts and errors.
Use meaningful commit titles: Use meaningful commit titles that summarise the purpose of the changes that have been made.
Use consistent formatting: Use consistent formatting for your commit messages, such as using the imperative mood and keeping the first line to 50 characters or less.
Use signed commits: Use signed commits to verify the authenticity of your commits and protect against tampering.
For example, a good commit message looks like this::

git commit -m "Add user authentication mechanism to the inventory management system"
It's bad practice to have vague messages such as:

git commit -m "Fixed stuff"
When maintaining a clean commit history, it's important to consider the needs of your team and project. You should choose practices that are simple, flexible, and scalable, and that support the way your team works. You should also document the practices and make sure that everyone on the team understands how they work and follows them consistently.

Tip 7: Utilise .gitignore
The .gitignore file is a simple and effective way to manage the files and directories that you want to exclude from version control. It allows you to specify patterns that match files and directories that you want to ignore, and prevents them from being added to the repository.

To name a few, the .gitignore file is particularly useful for:

Ignoring build artifacts: Ignore files and directories that are generated during the build process, such as log files, temporary files, and build artifacts.
Ignoring sensitive information: Ignore files and directories that contain sensitive information, such as passwords, API keys, and configuration files.
Ignoring user-specific files: Ignore files and directories that are specific to individual users, such as editor settings, local configuration, and temporary files.
Ignoring large files: Ignore files and directories that are large and not necessary for version control, such as media files, binary files, and archives.
Ignoring logs and caches: Ignore files and directories that are created as part of the logging and caching process, such as log files, cache files, and temporary files.
Ignoring test files: You can use .gitignore to ignore files and directories that are created as part of the testing process, such as test results, test logs, and test artifacts.
When using .gitignore, it's important to consider the needs of your team and project. You should choose patterns that are simple, flexible, and scalable, and that support the way your team works. You should also document the patterns and make sure that everyone on the team understands how they work and follows them consistently.

You can get more information on .gitignore and how to use it effectively in the GitHub repo .gitignore documentation.

As a beginner, what setup currently works for me is:

Initialize a Git repository

Create folders data, results, scripts and notebooks (nowadays I also create a reports folder to store RMarkdown reports, but that may be a subject of taste). Put the contents of data and results folders into .gitignore. Thus, only the code and documentation are versioned (however, the structure inside the data folders also matters for code readability)

I start the analysis in notebooks. Once a chunk of workflow (e.g., sample QC) is completed, I refactor the code, test it again and separate the logical parts into individual scripts. Then I test that sequence of scripts. If everything works fine, I delete the notebook (I personally do not like how notebooks interact with Git. If I want to showcase the code together with the results, I prefer RMarkdown)

Right now I'm working on improving my documentation practices. I think going with a README with a general description of the project, outline of main steps in your scripts and their order (e.g., PROJECT.md) and DATA.md which summarizes where you got the data you use

'''
