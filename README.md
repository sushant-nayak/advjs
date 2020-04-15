# advjs
Advanced JavaScript Concepts

## Installing Latest React
npm i -g react 

If you are on Unix systems(Mac, Linus variations) use - 
sudo npm i -g react

cd react-wo-npm
npm init -y

Install Babel cli v6 & babel React App v3 (latest versions at the moment)
npm install babel-cli@6 babel-preset-react-app@3

For latest Babel version run - 
npm install babel-cli babel-preset-react-app

Run JSX Preprocessor
(Note - npx is not a typo — it’s a package runner tool that comes with npm 5.2+.)
npx babel --watch src --out-dir . --presets react-app/prod 

cd src
touch like_button.js (Only on Mac, else create a same file manually)

Open index.html -> Right Click and click 'Open with Live Server'

