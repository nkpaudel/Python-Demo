Branch Protection. Define branch proteciton rules to disable force pushing, prevent branches from being deleted, and optionally require status checks before merging

Step-by-Step Configuration
1. On GitHub, navigate to the main page of your repository.
2. Click the Settings tab located under the repository name. (If you don't see it, you don't have the required permissions).
3. In the left sidebar, locate the Code, planning, and automation section and click Branches.
4. Under the "Branch protection rules" heading, click Add classic branch protection rule (or Add rule).
5. In the Branch name pattern field, type the branch name or pattern you want to protect.
	• Enter a specific branch name like main or develop.
	• Use wildcards to match multiple branches, such as release/* or v*.
6. Check the boxes for the specific protection settings you want to enforce (detailed below).
7. Scroll to the bottom of the page and click Create or Save changes. If prompted, confirm your password.


Forking:
 Github allows us to create personal copies of other peoples repositories. We call those copies a fork of the original
 When we fork a repo, we're basically asking github "make me my own cop of this repo please"
 As with pull request, forking is not a git features. this ability to fork is implemented by Github.

 Method 1: Using the GitHub Web Interface (Easiest)
1. Navigate to the original GitHub repository you wish to fork.
2. In the top-right corner of the page, click the Fork button.
3. Select an Owner (your personal account) and customize the repository name if desired.
4. (Optional) By default, GitHub will only copy the default branch (main or master). Uncheck Copy the main branch only if you need all existing branches.
5. Click Create fork. GitHub will create a server-side copy of the codebase inside your account within a few seconds

Rebase:
git-rebase - Reapply commits on top of another base tip

SYNOPSIS
git rebase [-i | --interactive] [<options>] [--exec <cmd>]
	[--onto <newbase> | --keep-base] [<upstream> [<branch>]]
git rebase [-i | --interactive] [<options>] [--exec <cmd>] [--onto <newbase>]
	--root [<branch>]
git rebase (--continue|--skip|--abort|--quit|--edit-todo|--show-current-patch)
DESCRIPTION
Transplant a series of commits onto a different starting point. You can also use git rebase to reorder or combine commits: see INTERACTIVE MODE below for how to do that.

For example, imagine that you have been working on the topic branch in this history, and you want to "catch up" to the work done on the master branch.

          A---B---C topic~

Alias:
git config --global alias.lg log
git config --global alias.s status

with argument
cm = commit -m  "My commit"