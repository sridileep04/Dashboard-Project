->Create a server folder.
->Create a init file fill the required details.
->install the * express     ->> Its a Framework
              * body-parser ->> Parsing our data coming in.
              * cors        ->>cross origin resourse sharing.is an HTTP-header based mechanism that allows a server to indicate any origins (domain, scheme, or port) other than its own from which a browser should permit loading resources.
              * dotenv     ->>for environment variables.
              * helmet     ->>Protecting our APIs.
              * morgan     ->>loging to API calls.
              * mongoose   ->>Handiling mongodb calls.
              * nodemon    ->>For Live server.

->Got to https://www.mongodb.com/ website and create the Account .
    >>After creating your account create a database 
    >>Click on connect then select Drivers you will find some code there copy it.
    >> Open the vs code then create a .env file and paste the code and save it.
    >>The env file is very important security reasons so to you need to protect it .
    >>For that create .gitignore file and paste below 2 lines.
    /node_modules
    .env
    >>The above 2 lines means ignore the env file.

->open the package.json file in scripts add below 2 lines
    >>"start": "node index.js",
      "dev": "nodemon index.js"
    >>The Above 2 lines means when ever clicked on start the index.js file runs. And nodemon is for live server avoids continuous refresh clicking.
->Now in the package.json file add below line.
             "type":"module",
            >>This will allow us to use input statements.

->MONGOOSE SETUP
  >> process.env.PORT  >> This allows us to access the environment variables
