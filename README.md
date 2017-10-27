# APoker
Apoker app is built with ReactJS/REdux with backend as NodeJS/express server. The purpose of this app is to create a robust open source backlog grooming solution that gives admins and users enhanced user interface, enable admins create up to 100 user stories on each session and enable them to save stories with estimates within each planning poker room. 

Running the app: 

Open 2 git-bash terminals to run client-side and server-side independently. However, please note that server side code is already deployed on heroku and embedded as a URL on client-side. Therefore it is completely optional to run on a separate terminal. 

Client-side:
	$ cd client/
	$ npm install(update any dependencies if necessary)
	$ npm run build, 
	$ npm run serve(to fire client-side code),
	Open your browser and run: http://localhost:9000/

Server-side(optional): 
	$ cd server/src/
	$ npm install(update any dependencies if necessary),
	$ npm run build(ensure that the build is clean), 
	$ npm start(to fire client-side code)
