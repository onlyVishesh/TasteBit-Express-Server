# 🌐 TasteBit Express Server

A TasteBit Express Server (Node.js web server) that fetches data from a third-party (Swiggy) API (Fix the CORS Issue) and exposes it to a client [🚀 TasteBit Express ]() App 😍.

🍁 [TasteBit Express App]() is part of [Namaste React Live Course](https://learn.namastedev.com/courses/namaste-react-live) and Github Repository for this App is [Namaste-React 💜](https://github.com/onlyVishesh/Namaste-React) ️
<br/>
## 🔥 Clone this Repository

You need to write the following commands on the terminal screen(in vscode) so that you can run this project locally.

```bash
  git clone "https://github.com/onlyVishesh/TasteBit-Express-Server.git"
```

Go to the project directory

```bash
  cd TasteBit-Express-Server
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

This application should now be running on `localhost`. If you want to Fork repository and want to run locally, follow this guidelines [Fork and Clone Github Repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

💫 Test the TasteBit Express Server Locally in your TasteBit Express React App then use this domain name (`http://localhost:3000/`) if the Server is running on a `3000` Port:
```javascript
const response =  await fetch(`https://www.swiggy.com/mapi/homepage/getCards?lat={Your latitude}&lng={Your longitude}`)

const data = await response.json();
```


## 🔮 Deploy the TasteBit Express server
Once you have tested the TasteBit Express server locally, you can deploy it to a production environment by following these steps.

1. Create an account on [Render](https://render.com/) if you haven't already.
2. Click on the `New +` button and select `Web Service` from the dropdown menu.
3. `Connect` to your own GitHub repository (node server that you have created your own) which you want to deploy.
4. In the `Settings` tab, scroll down to the `Environment Variables` section and add `PORT` environment variables to `3000`.
5. Wait for the deployment to finish. Once it's done, you should see a success message and a link to our server URL. For Instance: `http://YourOwnServerName.onrender.com`
6. Click on the link URL to test our server.

Note: Now that our server is deployed on [Render](https://render.com/) you can change the API URL in react app to the domain in which the server is deployed. For instance: if your server is hosted in `http://YourOwnServerName.onrender.com`, in the react app while sending a request to API, use this domain name : 

```javascript
const response =  await fetch(`http://YourOwnServerName.onrender.com/api/restaurants?lat={Your latitude}&lng={Your longitude}&page_type=DESKTOP_WEB_LISTING`)
```

<!-- ## 🔗 Let's Connect

[![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chetannada/)
[![twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/chetannada)
[![discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/916005177838956555) -->
