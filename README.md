## Runnerty Demo - Firebase Realtime Database trigger

This a [Runnerty](https://github.com/runnerty/runnerty) demo that sends an email to every new user that is registered in our Firebase database

It uses the [@runnerty-trigger-firebase](https://www.npmjs.com/package/@runnerty/trigger-firebase). This trigger is allways listening to new records in the indicated document of our Firebase Realtime Database.

This chain will send a wellcome email to the new users registered in our database.

## Usage
Clone the repo
```
git clone https://github.com/Jhonsensf/runnerty-simple-twitter-bot.git
```

Go to the directory  
```
cd runnerty-simple-twitter-bot
npm install
```
In the config.json file add your firebase and email account data.

Run Runnerty
```
runnerty
```

### Build it yourself:

You can know how to configure and build it from scratch reading this [article](https://medium.com/runnerty/firebase-realtime-database-runnerty-eee3c9dec6aa)