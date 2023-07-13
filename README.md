# MERN APP
## Introduction
This the chat app this is designed and developed and built for friends who are look for a place to conect just like twitter and instagram.
## Installation
### Server Installation
### Client Installation
For this application going to use Vite instead of "create react app". Using Vite because its faster and better.
* To use vite for client folder follow these instructions
```
npm create vite@latest
```
* THen when you have used that command in your terminal Vite will ask what is your project, which will be client as that will be the directory that you will create
```
Project name: client
```
* Then vite will prompt you with the next question which is "Select the framework", which means for this project you will use the down arrow key on keyboard to navigate to "React" like this:
```
Select a framework: React 
```
* The you will be prompted to select which variant of React framework you and for this project you will choose normal javascript
```
Select a variant: JavaScript
```
Now we need some style for the react applicatio so now we are going to install tailwindcss for the next installation for the client.
Always make sure you are in the client directory when executing this commands unless directed otherwise.
* This the is why we use this command below especially when paired with Vite: ```Installing Tailwind CSS as a PostCSS plugin is the most seamless way to integrate it with build tools like webpack, Rollup, Vite, and Parcel.```
```
npm install -D tailwindcss postcss autoprefixer
```
* Then you will use this command to initialize tailwindcss
* You will include the "-p" for postcss when you run this command:
```
npm tailwindcss init -p
```
After running the commands for tailwindcss you should see the following files in your directory:
```postcss.config.js``` and ```tailwind.config.js```
Meaning that all the commands have been executed correctly
## Usage
### Server Usage (backend)

### Client Usage (frontend)
Now that you are done with the installation you will now concentrate on changing the directory to the client directory with these simple commands
* First in your terminal to change to client directory use the following command:
```
cd client
```
* Then to install the node_modules with your directory you are simply going to type:
```
npm install
```
* Then the last thing to do is to run the client directory with this command as you will be building the frontend live
```
npm run dev
```
Now you can hide your terminal and get ready to the build the mern chat application.--host
## Contributing
## Related Projects
## Licensing
## Deployment Tools