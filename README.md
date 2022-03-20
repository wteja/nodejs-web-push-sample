## Web Push Notification using Node.js + Web-Push Library

We can easily create our push notifications using **web-push** without using a 3rd party service like [Firebase Cloud Messaging (FCM)](https://firebase.google.com/docs/cloud-messaging).

By using the new way to provide self hosted push notifications called VAPID (Voluntary Application Server Identity)

Then we create and install **Service Worker** that interacts after receiving the new push notifications. Showing notification is the choice. The key point is that after you subscribe to web-push successfully, you can receive push data anytime. You might use that information in ways you can't imagine.

You can find the [full tutorial here](https://dev.to/wteja/how-to-make-push-notification-using-nodejs-and-service-worker-jaa/edit) this tutorial will walk you through the process to create self-hosted push notification service.