## Zendesk Adblocker - User Sidebar

### What is this app for?

The new release of the [Marketplace Recommendations feature in Zendesk](https://support.zendesk.com/hc/en-us/articles/360000569387-Announcing-App-Recommendations) display Marketplace ads to agents and admins if the sidebar doesn't have any applications present.

There is presently no opt out mechanism for this feature. If you don't want agents to be digging through the marketplace while they should be working on tickets this app might solve your problems, until a better implementation of this feature is made available. 

### What the app does:
Since the recommendations only display when no apps are present, this app being installed will prevent them from loading. 

Installs an application to the user sidebar in Zendesk. This app is literally a blank app template from Zendesk with height adjusted to 30px. It just states that it blocks Marketplace ads.

I'm not a developer. There's no warranties here, expressed or implied. Feel free to modify it as you see fit. If I had the time or patience, I'd learn to make this configurable so you could block the ads on any combination of the Org, User or Ticket page. For now, if you want to change this application's location, edit the manifest.json file and change the location from

"user_sidebar"

to any of the values found in [Zendesk's API docs for app locations](https://developer.zendesk.com/apps/docs/support-api/introduction)


If you're the kind of person that likes making Pull Requests to projects that are a step above an empty shell, feel free
