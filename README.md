# Inventory-Management
This program will allow a user to upload, browse, and search using multiple terms for items in a (theoretical) car dealerships current inventory. The store owner will be able to upload and edit their inventory data.
Front end uses HTML, and React/JS 
processing mostly done via Javascript
Data storage handled by PouchDB to allow for offline, client-side only usage. In it's current state, the database is stored locally and does not offer an option for connecting to remote DB. Remote DataBase functionality will most likely not be implemented.

Big thanks to developers of: PouchDB (https://pouchdb.com/), Node.JS (nodejs.org), and React(Reactjs.org). 

In order to make this Program functional there are a few libraries that must be installed.
1. Install NODE.JS (mostly just for use of npm)
2. open a command prompt and type the following commands to install necessary requirements:

  $npm isntall pouchdb

  $npm install pouchdb-find

  $npm install -g pouchdb-server

  $pouchdb-server --port 5984


3. Now all of the necessary library requirements should be installed, and the final command in the list creates a local PouchDB database hosted on Port 5984. The GUI for this database can be accessed via: http://localhost:5984 (in case things aren't working properly check the GUI and verify installation requirements)
4. From here, you can open up the Index.HTML page to get started using the application.
5. It is recommended to start by uploading a set of mock_data to better gauge the functionality of the inventory browse/search apge.
  Note: Actual Admin/Store owner authentication was not implemented, due to this program being entirely functional offline. Without a remote database, making an admin   authentication system wouldn't serve much of a purpose.

6. If there are any further questions, or issues with the program, please feel free to contact me and we can get it figured out.
