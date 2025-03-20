# Vue-learn
Let's build with vue

## Initialising the repository
> cd frontend
> npm install
> npm run dev / build

=> Open a new terminal and initialize the json server
> npm install -g json-server
> json-server --watch data/db.json

npm install -g pm2
npm run build
npm install -g serve
serve -s dist -l 5173
pm2 start "serve -s dist -l 5173" --name vue-app
pm2 list
pm2 save
pm2 startup
http://<your-server-ip>:5173