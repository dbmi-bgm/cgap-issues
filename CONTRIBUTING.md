# CGAP Contributing Guide

Thank you for investing your time in contributing to our project!

Read our [Code of Conduct](https://github.com/dbmi-bgm/cgap-issues/blob/main/CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

In this guide you will get an overview of the contribution workflow from opening an issue, creating a PR, reviewing, and merging the PR.


## New contributor guide

To get an overview of the project, read the [README](https://github.com/dbmi-bgm/cgap-issues/blob/main/README.md); for high-level, cross-repository documentation, take a look at the [Wiki](https://github.com/dbmi-bgm/cgap-issues/wiki).

## Getting started

To navigate our codebase with confidence, see the CGAP Infrastructure Overview page on the wiki (coming soon).

Check [here](https://cgap.hms.harvard.edu/getinvolved) to see what types of contributions we accept before making changes. Many of them don't require writing a single line of code.


# Issues

## Create a new issue

If you spot a technical problem or bug in CGAP, please first search to see if an issue for that topic already exists. If a related issue doesn't exist, you can open a new issue using the most relevant issue template.

## Solve an issue

Scan through our existing issues to find one that interests you. You can narrow down the search using labels as filters. If you find an issue to work on, you are welcome to open a PR with a fix. See the Making Changes and Updates section below for more information.

## Editing the Wiki
Note that editing the Wiki directly is currently limited to Collaborators only. If you have a suggestion for a Wiki page or edit, create an issue using the Wiki template.

## Making Changes and Updates
1. Create an issue for the bug/issue first in `cgap-issues`, if one has not already been created. This can be a good way to request information on where and how to make the edits.

2. Once you have located the repository where you'd like to make your changes, set up the portal or repository according to the repo's instructions.

    *Note that sometimes multiple repositories may have to be updated in order to complete an edit (for instance, updating `Shared-Portal-Components` and `CGAP-Portal` to complete a Portal UI task).*

3. Create a new branch from the most recent master branch in the following format: 

    ```(github-username)-(branch-title)```

4. Commit your changes in that branch. Don't forget to add or update unit tests and comments!

5. Push your branch to remote/origin, and create a pull request with the appropriate template and label for your updates. Don't forget to link to the pull request from the issue you created in `cgap-issues`, to ensure someone on the team sees it.

6. Once it's ready for review, set it as ready for review.

7. Wait for review to be complete. We may ask for additional changes before your PR can be merged, using suggested changes or pull request comments. Commit any other edits to your branch.

8. Once your branch has been approved, we'll handle the merging of the branch to master and any merge conflicts that arise.

9. Congrats! Your PR is merged. The CGAP team thanks you! 🎉🎉

Once your PR is merged, your contributions will be deployed at the next release.