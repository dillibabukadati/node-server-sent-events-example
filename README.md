# Node Server Sent Events (SSE) Example

This Projects illustrates the usage and guidance to implete the Server side events (SSE).
To know about What is SSE Click here to read about it on my blog.

## Installation & Starting

Node Generator requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
git clone https://github.com/dillibk777/node-server-sent-events-example.git
cd sse-server && npm install && node app.js
```
Now the Backend is running on http://localhost:3000
Open another terminal tab in the project directory and execute the below commands

```sh
cd sse-client && npm install && npm start
```
Now the Frontend is running on http://localhost:3001

Copy and paste the Below Curl command in another terminal and observe the frontend website. You will receive the automatic update from backend to frontend.

```sh
curl --location --request POST 'http://localhost:3000/fact' \
--header 'Content-Type: application/json' \
--data-raw '{"info": "Shark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.", "source": "https://en.wikipedia.org/wiki/Shark"}'
 ```

## Buy me a Coffee
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/dillibabukadati)
