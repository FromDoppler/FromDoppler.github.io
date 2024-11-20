# FromDoppler.github.io
Maintenance web page for fromdoppler.com

## Deployment
To deploy a maintenance page to production, the following redirect rules must be enabled in CloudFlare (Rules -> Redirect Rules):
![image](https://github.com/user-attachments/assets/73077b56-cdf2-4be8-9b33-e9de8d809c3b)


By simply activating the above rules, the redirection of the URLs app, app2, and cm to https://fromdoppler.github.io will be performed.

In the event of a system outage, it will be necessary to redirect to the app_offline file. To do this, it will be necessary to modify the rules forwarding to: https://fromdoppler.github.io/app_offline.html

## Documentation
The maintenance and app_offline files are located in [FromDoppler.github.io](https://github.com/FromDoppler/FromDoppler.github.io) repository.
