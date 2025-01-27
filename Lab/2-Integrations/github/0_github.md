# Initial Github Setup

- When creating multiple GitHub connectors, use a different username and token to facilitate speedier data collection. There is a rate limit for GitHub API calls of about 5000/hr per individual and 15000/hr at enterprise level.

- Use a personal access token that does not expire.

- When Historical data collection is selected (see step 9), select a start date close to the date that will be used for AI training. Selecting a date further back might result in more API calls to GitHub, especially if there is a large volume of issues.


Here are the steps to follow:

1. [Creating a github integration](1_github_create.md)
1. [Editing a github integration](2_github_edit.md)
1. [Deleting a github integration](3_github_delete.md)



