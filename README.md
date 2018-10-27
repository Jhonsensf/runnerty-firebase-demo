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

Run Runnerty
```
runnerty
```

### Expected result:

The chain will listen to new followers of the given Twitter accound and send them automatically a direct message.