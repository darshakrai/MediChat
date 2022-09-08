# Online Medical Chat App

![Online Medical Chat App using React JS](https://user-images.githubusercontent.com/92095133/189185099-9f043423-fed9-4421-845b-4c30129be76a.png)

## 📌 Before you start

1. Make sure **Git** and **NodeJS** is installed
2. **Yarn** is faster than Npm. So use [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/).
3. Create .env file in both client and server folder.
4. _server/.env_

```
STREAM_API_KEY=xxxxxxxxxx
STREAM_API_SECRET=xxxxxxxxxxxxxxxxxxxxx
STREAM_APP_ID=xxxxx

TWILIO_ACCOUNT_SID=xxxxxxxxxxxxxx
TWILIO_AUTH_TOKEN=xxxxxxxxxxxxxxx
TWILIO_MESSAGING_SERVICE_SID=xxxxxxxxxxxxxxxxx
```

5. _client/.env_

```
REACT_APP_STREAM_API_KEY_SECRET=xxxxxxxxxx
```

6. Create an account in [Stream](https://getstream.io/)
7. Create a new app. You can name it whatever you want.
8. On app dashboard, you can copy your keys and paste it.

_NOTE:_ Both `STREAM_API_KEY` and `REACT_APP_STREAM_API_KEY_SECRET` are same

9. To use messaging functionality, Create an account in [Twilio](https://www.twilio.com/try-twilio)
10. On app dashboard, copy keys and paste them in .env file in server folder.
11. To get Messaging service sid, go to _Messaging/Services_ through dashboard sidebar.
12. Create a messaging service in case it doesn't exists
13. Then, click on messaging service you created and you will be able to see its properties as shown below. Copy **Messaging Service SID**

## 📌 How to use this App?

1. Open **terminal** in root directory and `cd server`
2. Type and Run `yarn install`
3. Run `yarn run dev` to start back end server
4. Now, in browser go to this URL [http://localhost:5000/](http://localhost:5000/)
5. Now, nodejs server is **configured** and started. Next, we need to setup **Client** side server.
6. Open a new **Terminal** by using **split terminal** feature in vs code and cd into client then run `yarn install`
7. Once packages are installed, type and run `yarn start`
8. Now client side server will be started and you can start using this app :+1:

![Authentication Page](https://user-images.githubusercontent.com/92095133/189056738-d06a46b0-0c4a-4f3d-baf2-2d59ddd36fd9.png)
