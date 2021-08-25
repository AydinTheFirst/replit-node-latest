<h1 align='center'> Node@latest </h1> 

### 1. To Install NodeJs v16 Copy This Given Code And Paste In Shell Of Replit.

```
npm init -y && npm i --save-dev node@latest && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH
```

### 2. Create the .replit file to execute node from the shell instead of the console, and insert this in that file.

```
run="npm start"
```

### 3. Make sure to add the start script in your package.json file

```
"scripts": {
  "start": "node ."
}
```
