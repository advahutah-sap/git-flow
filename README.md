# git-flow

1. install gh cli and authenticate
1. install https://github.com/bobvanderlinden/probot-auto-merge
1. Add CODEOWNERS
1. Add merge label
1. create feature branch -  **we can remove it since we are using HEAD **
1. fix the code
1. Add token to url in "<project name>/.git/config". for example - 
  `	url = https://<token>@github.com/advahutah-sap/cap_hack`
1. Run task "super git" - git add & commit & push **Need to change the cwd to project path**
1. create pr -> gh pr create -f -l merge
