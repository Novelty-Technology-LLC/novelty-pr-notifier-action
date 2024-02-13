# novelty-pr-notifier-action
This is an action repo which uses Post Google Chat message to receive Pull Request notification. 

## Usage
```
- name: Novelty-PR-Notifier
  uses: Novelty-Technology-LLC/novelty-pr-notifier-action@<version>
```

## Variables
| Input Variables | Required | Description   |
|:----------------|:--------:|:--------------|
| webhook         | T        | Google Chat Web Hook |
| repoName        | T        | Repository Name |
| prTitle         | T        | PR Title |
| prNumber        | T        | Pull Request Number |
| prHtmlUrl       | T        | PR HTML URL |
| sourceBranch    | T        | Source Branch From where the PR is created |
| targetBranch    | T        | Target Branch or Base Branch |
| creator         | T        | PR creator |
| reviewer        | T        | PR reviewers |
| assigner        | T        | PR assigner |
| eventAction     | T        | Event Action |

## Notifier Sample
![image](https://github.com/Novelty-Technology-LLC/novelty-pr-notifier-action/assets/141004148/6c7c9470-a308-45bb-b5a5-6f6d65c7545f)
