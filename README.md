# Jira and Github

## Setting up this tool for automation

Integrating Jira with Github and creating
automation processes to change status of
tasks in Jira when performing actions in
Github such as commit, pull requests, merge.

If you want to connect with Jira:
    When creating a branch make sure to include the issue key
    of Jira in the beginning of the branch name

    When you commit changes:
        Make sure to also include the issue key following the
        correct format:
            git commit -m "Issue_name <message>"

    For creating PR and merging PR:
        You can proceed as usual