# NotificationService
- **Backend REST API :** We can use this notification service multiple places where we need this features.

### Features
- create notification by subject,recepientEmails,content,requester
- get notification by /:id and status of notification { sent or un-sent }
- I am using node_mailer to send notification on client email.
- node-corn : he check every 15 sec. any new notification comes in Database or not, he take and send

### Prerequisite
- Understanding of Node.js
- Understanding of Async Await
- Mongo DB locally installed and running

## 🛠 Tech
- **Client   :** Post-man
- **Server   :** Node, Express, node_mailer, node-cron
- **Database :** mongoDB
- this app requires Node.js v14+ to run.

### Install the dependencies and devDependencies and start the server.
Before starting the server please ensure mongodb server is locally installed and running on the default port

```bash
  cd notificationService
```
```bash
  npm install
```

## Development
Want to improve? Great! Make the changes and raise a PR.
