# Stack Overflow Clone

This website is a question forum and made to look like Stack Overflow.

## Technologies used:

- React js
- Node js
- Express js
- MongoDb
- Redux
- Json web token and more

## How to use?

Fork and clone the repo and follow the below steps:

- Install Node.js
- Open client and server directories in VS code
- Install Dependencies using the command

```
npm install
```

Step 1:
Create MongoDb Account and setup the environment
    Note: Go for free setup
*StepByStep Setup Of Environment
![Screenshot (37)](../main/Screenshots/3.png)
![Screenshot (37)](../main/Screenshots/4.png)
![Screenshot (37)](../main/Screenshots/5.png)
![Screenshot (37)](../main/Screenshots/6.png)
![Screenshot (37)](../main/Screenshots/7.png)
![Screenshot (37)](../main/Screenshots/8.png)
![Screenshot (37)](../main/Screenshots/9.png)
![Screenshot (37)](../main/Screenshots/10.png)

Wait for a while to load after that Now click on connect and copy connection string

```
CONNECTION_URL = "Mongo db url"
```

![Screenshot (37)](../main/Screenshots/11.png)
![Screenshot (37)](../main/Screenshots/12.png)
![Screenshot (37)](../main/Screenshots/13.png)


Paste it on .env file created below in replace of ["Mongo db url"]

Step 2:
Create .env file and setup below config

```
PORT = "5000"
CONNECTION_URL = "Mongo db url"
JWT_SECRET = "This could be anything like test"
```

Example:
```
PORT = "5000"
CONNECTION_URL = "mongodb+srv://User:password@firstcluster.xyz.mongodb.net/?retryWrites=true&w=majority"
JWT_SECRET = "test"
```

Step 3:
Load it in Vscode and open terminal and split the terminal.

Step 4:
Open Client | Server and then run.
![Screenshot (37)](../main/Screenshots/2.png)

- Start App using the command from client and server side both

```
npm start
```

## DataBase
![Screenshot (37)](../main/Screenshots/14.png)
![Screenshot (37)](../main/Screenshots/15.png)
![Screenshot (37)](../main/Screenshots/16.png)


## Credits

This website uses icons from font awesome.

Made with ❤️ by [@Harshit](https://www.linkedin.com/in/harshitjoc/)
