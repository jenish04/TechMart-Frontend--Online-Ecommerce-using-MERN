TechMart: An ecommerce website for Tech devices made with MERN stack technologies, 
To run this in your System, Follow the below steps:
1. Clone the repository(Download the code)
2. Install the dependencies using npm install
3. cd to Server-side: install node modules via npm install, after the completion write npm run dev to run the Server side. It should look something like this 
PS C:\Users\jenish.p\Desktop\projects\Shopifyy- Ecommerce App\Server-side> npm run dev

> ecommerce-backend@1.0.0 dev
> nodemon index.js

[nodemon] 2.0.7
[nodemon] to restart at any time, enter `rs`
[nodemon] watching path(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node index.js`
server started
database connected

4.cd to client-side : similarly as server-side, first type npm install in terminal, then after installing type npm run start, to start the front end side server.if everything works well ,It should look something like this

Compiled successfully!

You can now view react-ecommerce in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.12.71:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully
5. Voila here is how U can run front-end as well as server-side server, 

6.IMPORTANT!! :- Now we want .env file to run client as well as server side ,because the port,MongoDB url(database we used to store info), JWT secret key and Session key. As github restricts the .env file to public, If you want the .env file then mail me at jenish4103@gmail.com  stating "send .env file -your name"