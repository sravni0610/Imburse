# Imburse Task and steps to import collection into postman

Steps to Import Collection to Postman
1. Postman app should be installed in your local machine
2. Checkout Mail branch into local
3. Click on File -> Select Import -> Select collection named 'Imburse.postman_collection.json' from your local and click on Import
4. Import Environment in the same way as collection ex: Click on File -> Select Import -> Select collection named 'Imburse.postman_environment.json'


Run tests from Commandline - To run tests from command line, one should have node and newman installed in machines
Steps to run tests from newman using sharelink option from postman collection
1. Click on Share in postman colelction
2. Click on Get public link
3. Copy link and use link in below command
4. $ newman run <<placeholder for link generated in step#3 >> -e Imburse.postman_environment.json

