# React-Todo-App

Live link: https://md-wasimm.github.io/React-Todo-App/

![Screenshot (39)](https://github.com/md-wasimm/React-Todo-App/assets/89610732/ed68c902-575f-46e5-b77f-dfd98c56839f)

# Deploy in Github Pages -

1. Open your package.json and add a homepage field for your project -
  "homepage": "https://myusername.github.io/my-app",

2. To publish it at https://myusername.github.io/my-app, run -
  npm install --save gh-pages

3. Add the following scripts in your package.json -
 "scripts": { "predeploy": "npm run build", "deploy": "gh-pages -d build",}

4. Change the deployment to master

5. Then run -
   npm run deploy
