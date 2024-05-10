# FromDoppler.github.io
Maintenance web page for fromdoppler.com

## Deployment
To deploy maintenance page into production, the following rules need to exist in CloudFlare:
![image](https://github.com/FromDoppler/FromDoppler.github.io/assets/11631812/7cbcb3e3-39c1-401f-938e-95abe2a7c34a)

By simply activating the above rules, the redirection of the URLs app, app2, and cm to https://fromdoppler.github.io will be performed.

In the event of a system outage, it will be necessary to redirect to the app_offline file. To do this, it will be necessary to modify the rules forwarding to: https://fromdoppler.github.io/app_offline.html

## Documentation
The maintenance and app_offline files are located in [FromDoppler.github.io](https://github.com/FromDoppler/FromDoppler.github.io) repository.
