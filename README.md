# testingRepo
Testing Jenkins with Github.
Now everything is working!

Steps to reconfig webhook:
* Enter into terminal: ngrok http 8080 (or 80 on Linux)
* Copy redirect (forwarding) link
* Go to github.com/your_username/your_project/settings/hooks
* Insert redirect link into you existing/new webhook (webhook payload)
* Create/Update your webhook
* Now it's working. Test it!
