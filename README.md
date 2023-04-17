# react-test-bild with gh-pages

## Steps:

1.  `npx create-react-app my-app` (folder name where will be app)
2.  `npm i gh-pages -D`
3.  In package.json add fields:
    "homepage": "https://AlexeyKiselyov.github.io/my-app", ("my-app" - name of gh repo)
    "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",...}
4.  `npm run deploy`
