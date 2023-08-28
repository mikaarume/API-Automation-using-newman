# Postman

This project about Postman Automation
to run this project please use command "newman run kasiraja.postman_collection.json"

Here I use newman to run API Automation, here are the steps:
Install Node.js and npm: Newman requires Node.js and npm (Node Package Manager) to be installed on your system. You can download and install them from the official Node.js website: https://nodejs.org/

Install Newman: After installing Node.js and npm, open your terminal or command prompt and run the following command to install Newman globally:
npm install -g newman

Export Postman Collection: Before you can run a collection with Newman, you need to export the collection from Postman. Open Postman, go to the collection you want to run, and click the "Export" button. Choose the desired format (usually JSON) and save the exported file.

Run Newman: In your terminal, navigate to the directory where you've saved the exported collection JSON file. Then use the following command to run the collection with Newman:
newman run collection.json

Replace collection.json with the actual name of your exported collection file.

Newman will execute the requests in the collection and provide you with the results in the terminal. You can also use various command-line options with Newman to control the execution, generate reports, and more. You can learn about these options by running newman --help in the terminal.

Remember that Newman requires an active internet connection to send requests to APIs and receive responses.

Make sure to replace placeholders like collection.json with the actual file name and path on your system.
