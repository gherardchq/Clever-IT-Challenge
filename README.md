# PRUEBA CLEVERIT 

## Installation
npm install

## Run Automation-Test
newman run .\test.json

## Run Automation-Test with enviroment 
newman run .\test.json -e .\cleverIT.environment.json

## Generate Report 
newman run .\test.json -r htmlextra --reporter-htmlextra-title "Informe Prueba CleverIT Challenge"