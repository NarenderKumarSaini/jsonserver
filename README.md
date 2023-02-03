# Json server ✨


This repo is used for jsonserver for blog app for React native (https://github.com/NarenderKumarSaini/react-native-blog)

If you want to understand this repo better and use it follow the steps mentioned below

The First step is to fork the repo and get it in your Github repositories and then clone the repo to your local environment.


### Setup


1. First clone the branch from the repo

   > `git clone <remote-repo-url>`

2. Install all the npm packages

   > `npm install`

3. Run the db server
   > `npm run db`

3. Run ngrok to host local server 
   > `npm run tunnel`
   
## Important - Required Ngrok Setup Steps

In the next lecture, we will be introducing Ngrok to tunnel traffic between our backend and Expo client.

Ngrok has made some substantial changes that require you to signup for an account and install an authtoken.

Sign up for a free account here:

https://dashboard.ngrok.com/signup

Then, download the official Ngrok library for your specific OS rather than the Node port shown in the lectures:

https://ngrok.com/download

After registering for an account and installing the full library, you will need to copy your authtoken from your Ngrok account dashboard.

Then, using your terminal, run the following command:

> `ngrok authtoken YOUR_AUTHTOKEN`

This command only needs to be done once. Going forward, you can open a tunnel by using your terminal to run the following command (replacing PORT_NUMBER with the port of the backend server):

> `ngrok http PORT_NUMBER`

You must run the Ngrok server directly using the above command. Do not attempt to run Ngrok from the package.json file with "npm run tunnel" as it will not use the authenticated version.

Note - If you are reading this note after attempting to use Ngrok as shown in the course, you will need to follow all of the steps above. Then, afterward, you will need to restart any running tunnels and applications and generate a new tunnel address.


## Author ✍️

1.  Narender kumar saini (https://github.com/NarenderKumarSaini)
## Note

If you found this useful, then please consider giving it a 🌟 on Github and sharing it with your friends.<br>
Happy Coding 💻
