# Exploring MERN Stack

Reference: <br>
[1] Learn The MERN Stack - Frontend Authentication | Redux Toolkit, [Traversy Media YT Channel](https://www.youtube.com/watch?v=mvfsC66xqj0&list=PLillGF-RfqbbQeVSccR9PGKHzPJSWqcsm&index=1)

## Requirement
Node v14 (recommend v14.18.2)

## Installation
```bash
# run on /
npm install
# run on /frontend
cd frontend
npm install
```

## Start backend server (express-mongo)
```bash
# run on /
npm run server
```

## Start frontend server (react-redux)
```bash
# run on /
npm run client
```

## Start both
```bash
# run on /
npm run dev
```

## Deployment (Heroku)
1. Create Heroku App
```bash
# install Heroku CLI (if not ready)
sudo snap install heroku --classic

# login to heroku account
heroku login

# create new heroku app
heroku create hagai-mernapp
```
2. On the Heroku Page set env variable on the ``Settings/Config Vars``
3. Link the code to the Heroku App
```bash
# the command can be seen in the page under the 'Deploy' section
heroku git:remote -a hagai-mernapp

# push the code
git push heroku main
```
4. The Deployment is finished
```bash
# to get the link of the app
heroku open
```