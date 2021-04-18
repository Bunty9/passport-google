Passport Google OAuth2 Example
==============================

This is an Express 4 application using Google for authentication via OAuth2.


## Create a Google client ID and client secret
We can create a client ID and client secret using its [Google API Console](https://console.cloud.google.com/apis/dashboard). You need to follow below steps once you open Google API Console

1. From the project drop-down, select an existing project, or create a new one by selecting Create a new project
2. In the sidebar under "APIs & Services", select Credentials
3. In the Credentials tab, select the Create credentials drop-down list, and choose OAuth client ID.
4. Under Application type, select Web application.
5. In Authorized redirect URI use http://localhost:3000/auth/google/callback
6. Press the Create button and copy the generated client ID and client secret
---Note: If Google doesn't support http://localhost:3000, then use http://127.0.0.1:3000---

## Install

1. `git clone https://github.com/Bunty9/passport-google.git myapp`
2. `cd myapp && npm install`
3. Create a .env file in the root directory on package.json level
4.  Add GOOGLE_CLIENT_ID, GOOGLE_CLIENT_SECRET, and SESSION_SECRET to .env file
5. also define PORT and MONGO_URI in the .env file


## Start 

run `npm start` 
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Github
You can check out [My GitHub repository](https://github.com/Bunty9) - your feedback and contributions are welcome!
