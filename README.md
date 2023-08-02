# node-todo-cicd

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

test

```amazon linux```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
   74  . ~/.nvm/nvm.sh
   77  nvm install 16
   78  node -e "console.log('Running Node.js ' + process.version)"
   79  ls
   80  cd my-notes-todo-cicd-jenkins/
   81  npm install
   82  node app.js
   85  docker build -t note-app .
   86  docker images
   87  docker run -d -p 8000:8000 note-app:latest
   88  docker ps
