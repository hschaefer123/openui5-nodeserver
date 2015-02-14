# openui5-nodeserver
OpenUI5 SDK Server running on node.js

This is a little quickstart project to serve the OpenUI5 SDK from a local node.js server.

You need a local **directory** **"openui5-nodeserver"** and put the files "**index.js**", "**package.json**" into it.

Open a console (CMD) inside this directory and install the needed module dependencies included in package.json from inside the directory

    c:\openui5-nodeserver>npm install

The create a subdirectory "**sdk**" 

    c:\openui5-nodeserver>md sdk
    
Download the OpenUI5 SDK from http://sap.github.io/openui5/download.html and unzip it into the created "**sdk**" directory. 

Now you can start using the SDK  by starting the server

    c:\openui5-nodeserver>node index.js

It will open a new browser window with the URL 
http://localhost:8888/sdk
launching the OpenUI5 SDK.

By using
http://localhost:8888/
the server will also serve other directory inside the root directory (maybe your app).
