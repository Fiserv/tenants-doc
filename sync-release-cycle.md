# Syncing your Repo branches & Devstudio Release Cycle

As part of our current release cycle our team has been syncing/updating the GitHub branches for your repositories, before every Stage and Production release. However, as per our new release cycle, we are requesting your teams to sync up your own Github repos before our next production and Stage releases.
 
This is the usual sync process that we followed, unless asked otherwise: develop à stage à main. You can create GitHub Pull requests to do so.
 
Below are few things that are worthy to note:
 
Stage Branch:   When the GitHub branches are updated in Stage, our daily indexing job (scheduled time: 8:01:49 PM PST/11:01:49 PM EST) will pick up the latest changes from the spec files which will take care of updating the APIs. The documentation will be updated on Dev Studio UI almost instantly as we have GitHub webhooks in place already. So you can sync up the Stage branches as and when you see fit.
 
Main Branch:    For production releases we need to follow Service Now Change request (CHG) process, where we deploy our changes during specific release windows. So for production releases we would request teams to sync their changes right before our change window starts. It is important to note that as of now we do not have any daily indexing jobs scheduled for apis or docs to run in production. So we run these jobs only during the release window.
Although, the docs will always get updated on Dev Studio UI due to GitHub webhooks.
In case of issues, it will be either taken care later on during our production release or as part of an emergency CHG , as needed.
 
 
Let's take a look into our upcoming release dates:
Production :- Kindly keep your main GitHub branches synced, before our release window starts so that our release process runs smoothly. In case you miss this window, your updates would be taken care as part of the next production release cycle.
Stage : 
Production : 
 
In upcoming sprints our release team would be sending email notifications before any production release so that you can sync your GitHub branches as necessary.
