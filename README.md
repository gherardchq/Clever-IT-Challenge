# Test template

## Configuring
npm install

## Run Automation-Test
newman run .\test.json --ssl-client-cert .\qa.ingressgateway.pem --ssl-client-key .\qa.ingressgateway-key.pem --ssl-client-passphrase abcDEF123. --insecure

newman run .\test.json -r htmlextra --reporter-htmlextra-title "Informe Prueba CleverIT Challenge"