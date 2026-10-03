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