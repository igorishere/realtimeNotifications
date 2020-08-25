## realtimeNotifications
Small project made to demonstrate how to implement notifications sent by the server in realtime and consumed by the frontend, using SSE(Server Sent Events) and node Events API.

Medium post detailing all that i´ve done here: 
https://medium.com/@igorbitencourtsilveira/um-jeito-simples-de-notificar-o-frontend-atrav%C3%A9s-de-node-js-sse-server-sent-events-271b87be67c6


# Starting the server #

Enter the directory and type in terminal:
```bash
npm install 
or
yarn install
```

After download package, type in terminal
```
node index.js
```

So, open the ```index.html``` in any broswer.
Now, make some requests to 
```http://localhost:3000/pedidos/cancelamento``` or ```http://localhost:3000/pedidos/novo```
and see in the ```index.html``` the magic happens!
