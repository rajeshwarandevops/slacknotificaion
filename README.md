# slacknotification 

1.Create remote repo 
2.commit changes in remote repo & add slack web hook secret in remote repo
 setting ------>Actions secrets and variables------->Repository secrets---->SLACK_WEBHOOK_URL ( updtae web hoom url)
3.git remote add origin https://github.com/rajeshwarandevops/slacknotificaion.git
git branch -M main
4.Create echo.txt & create notifytest.yaml uner .github\workflows
5.git add . & git commit -m "update commit message"
5.git push -u origin main

