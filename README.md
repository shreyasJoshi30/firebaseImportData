# firebaseImportData
The project imports JSON data to Firebase database. The code also handles nested json as well.
The JSON file needs to be in the format of dataToImport.json file.

# To run the application:
1. Clone the project
```
git clone https://github.com/shreyasJoshi30/firebaseImportData
```
2. Install all dependencies
```
npm install
```
3. Replace service-json file with your file. Download this file from your firebase database by generating a new private key.
4. Go to index.js Line 7. Enter your project url here eg - https://console.firebase.google.com..../project/<project-name>.../data~2F
5. Run application
```
node index.js
```
