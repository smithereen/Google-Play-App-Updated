A simple nodejs that checks every 20min if your app is updated and publish to a slack channel

##### Configuration
Create a file ```config.js``` with the following:

```
config.slack = {};
config.slack.webhook = '<slack-webhook-uri>';
config.slack.channel = '<slack-channel>';
config.slack.message = '<slack-message>';
config.app = {};
config.app.currentVersion = "<current-version>";
config.app.packageName = "<android-app-package-name>"
module.exports = config;
```
