+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 7ebf0dd1a6674303940a86d8ed38b97a |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        |          |
|                                  | 11/20/24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 11/20/24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Git Basics

Answer the following research questions about Git, GitLab desktop and
GitHub.

1.  What is Git, and why is it important in software development?

-   Git is a version control system used for tracking changes in
    computer files. It is generally used for source code management in
    software development. It allows multiple developers to work
    together. It also supports non-linear development through its
    thousands of parallel branches.

2.  How does Git track changes in a project?

-   As you edit files, Git sees them as modified, because you've changed
    them since your last commit. As you work, you selectively stage
    these modified files and then commit all those staged changes, and
    the cycle repeats.

3.  What is the difference between a local repository and a remote
    repository in Git?

-   A local repository in Git is hosted on a local machine for
    individual user while a remote repository in Git is hosted on a
    remote (this could be on the internet or off-site server; it could
    even be the same machine in a different path) and is shared among
    multiple team members. Also, in local repository, Git allows user to
    perform work on the project from all over the world because of its
    distributive feature while in remote repository, Git allows users to
    sync their copy of the local repository to other repositories
    present over the internet.

4.  What are the basic Git commands?

-   git init - This command initiates a new Git repository within a
    directory. 

-   git init \[project name\] - To create a new repository while
    specifying the project's name.

-   git add - This command is used to stage file changes, preparing them
    for the next commit.

-   git commit - Use this command to create a commit message for the
    changes, making them part of your project's history.

-   git status - This command displays valuable insights into your
    files' modifications and staging status.

-   git log - The basic git log** **usage lets you view a chronological
    list of commit history.

-   git diff - This command lets you compare changes between your
    working directory and the most recent commit.

-   git diff commit 1 commit2 -- To compare changes between two commits.

-   git rm - This command removes files from your working directory and
    stages the removal for the next commit.

-   git mv - Use this command to rename and move files within your
    working directory.

-   git config - This command configures various aspects of Git,
    including user information and preferences.

-   git merge - To combine a feature or topic branch into the main Git
    branch.

-   git push - This command sends your local Git branch commits to a
    remote repository, updating it with your latest changes.

-   git pull - This command fetches and integrates changes from a remote
    repository into your current local branch.

-   git fetch - To retrieve new commits from a remote repository without
    automatically merging them into your current branch

5.  How do you check the status of a Git repository?

-   The git status command displays the state of the working directory
    and the staging area. It lets you see which changes have been
    staged, which haven't, and which files aren't being tracked by Git. 

6.  What is the purpose of branches in Git, and how do you create and
    switch between them?

-   Branches in
    [Git](https://www.datacamp.com/courses/introduction-to-git)
    represent independent lines of development, allowing developers to
    work on multiple features or versions of a project simultaneously.
    Git branches provide a structured way to manage code changes,
    enabling a smooth integration of new features, bug fixes, and
    experimental ideas without disrupting the main
    codebase. Traditionally, we used the [git checkout
    command](https://git-scm.com/docs/git-checkout) to move between
    branches. The [git switch
    command](https://git-scm.com/docs/git-switch) provides a more
    intuitive way to switch and create new branches.

7.  What are GitLab Desktop and GitHub, and how are they different from
    Git?

-   GitLab is a web-based platform for Git repository hosting, offering
    a comprehensive DevOps toolchain and GitHub is also a web-based
    platform built on top of Git, designed for collaboration and code
    hosting. While Git is a distributed version control system used to
    track changes in source code during software development.

8.  How do you connect a local Git repository to a GitLab or GitHub
    repository?

Follow these steps to add and push a new project into an existing GitLab
repository:

-   Create a GitLab repository for the current project.

-   Copy the GitLab URL for the new repository to your clipboard.

-   Issue the git init command in the base folder of your development
    project.

-   Add all of your project's files to the Git index and then perform a
    commit.

-   Add the GitLab repository as a remote reference for the local
    project.

-   Run a git push operation and use the -u switch to set the upstream
    branch.

-   Confirm that the files in the local project have been uploaded to
    GitLab.

9.  What are the steps to collaborate with others using GitLab or
    GitHub?

-   Ask for the username of the person you\'re inviting as a
    collaborator. If they don\'t have a username yet, they can sign up
    for GitHub. For more information, see \"[Creating an account on
    GitHub](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).\"

-   On GitHub, navigate to the main page of the repository.

-   Under your repository name, click **Settings**. If you cannot see
    the \"Settings\" tab, select the dropdown menu, then
    click **Settings**.

-   In the \"Access\" section of the sidebar, click **Collaborators**.

-   Click **Add people**.

-   In the search field, start typing the name of person you want to
    invite, then click a name in the list of matches.

-   Click **Add NAME to REPOSITORY**.

-   The user will receive an email inviting them to the repository. Once
    they accept your invitation, they will have collaborator access to
    your repository.

10. How do you resolve merge conflicts in Git?

-   Step 1: The easiest way to resolve a conflicted file is to open it
    and make any necessary changes.

-   Step 2: After editing the file, we can use the git add a command to
    stage the new merged content.

-   Step 3: The final step is to create a new commit with the help of
    the git commit command.

-   Step 4: Git will create a new merge commit to finalize the merge.

11. What is a pull request, and why is it used in GitHub?

-   A pull request is a proposal to merge a set of changes from one
    branch into another. In a pull request, collaborators can review and
    discuss the proposed set of changes before they integrate the
    changes into the main codebase. Pull requests display the
    differences, or diffs, between the content in the source branch and
    the content in the target branch.

12. What are some best practices for writing commit messages?

-   **Commit Often, but Not Too Often:**  Never push unrelated changes
    in a single commit.

-   **Write Clear and Descriptive Messages:** Your commit messages
    should be explaining what the commit does and why you made the
    change.

-   **Use Branches Effectively:** Use feature branches for new features,
    bug fixes, and experiments.

References:

<https://www.hostinger.in/tutorials/basic-git-commands#:~:text=Basic%20Git%20Commands%20FAQ,-What%20Are%20the&text=Some%20of%20the%20frequently%20used,git%20merge%2C%20and%20git%20stash>.

<https://git-scm.com/book/ms/v2/Git-Basics-Recording-Changes-to-the-Repository#:~:text=As%20you%20edit%20files%2C%20Git,changes%2C%20and%20the%20cycle%20repeats>.

<https://www.simplilearn.com/tutorials/git-tutorial/what-is-git>

<https://www.atlassian.com/git/tutorials/inspecting-a-repository>

<https://www.datacamp.com/tutorial/git-switch-branch>

<https://www.bairesdev.com/blog/git-github-and-gitlab-whats-the-difference/>

<https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-add-and-push-an-existing-project-to-GitLab>

<https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository>

<https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git#:~:text=Step%201%3A%20The%20easiest%20way,of%20the%20git%20commit%20command>.

<https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests>

<https://dev.to/sheraz4194/good-commit-vs-bad-commit-best-practices-for-git-1plc#:~:text=Best%20Practices%20for%20Good%20Commits&text=Never%20push%20unrelated%20changes%20in,%2C%20bug%20fixes%2C%20and%20experiments>.
