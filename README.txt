
copy my nginx config from /config-dev-ginx
cp config-dev-ginx/nginx.conf   /usr/local/etc/nginx
cp config-dev-ginx/openssl/*.*  /usr/local/etc/openssl/

Be advised yu need to install openssl to run the app

i added 2 folder with :
one configuration to test the production  config-prod-ginx
(file compressed and only one port (3000) running just need to start feather)

and one configuration to test the development  config-dev-ginx (like we worked before)


add in /etc/hosts this line:
127.0.0.1	localhost fr.skiscool.com ru.skiscool.com pt.skiscool.com uk.skiscool.com


go to /temp
run
npm install

Manual action to apply !! important

unzip mapbox.js.zip to /temp/node_modules (replace the installed one by mine)
unzip match-media-mock.zip to /temp/node_modules (replace the installed one by mine)
unzip material-ui-country-flags.zip to /temp/node_modules (replace the installed one by mine)
unzip mobx-react-form.zip to /temp/node_modules (replace the installed one by mine)
unzip validatorjs.zip to /temp/node_modules (replace the installed one by mine)

then
delete in /temp/node_module 
react
react-event-listener@0.3.1

exept:
but let in /temp/node_module
react-addons-create-fragment@15.3.2
react-addons-transition-group@15.3.2

go to / (root)
run
npm install


to start application in / (root) 

1)
first start the application:
mongod (start mongo)

then 
2)run nginx
sudo nginx (sudo is important)

In / (root)
3) run the api (feather)
node ./bin/server

4) finally run the application
npm start

go in your browser in 
https://fr.skiscool.com
 

click on map yu see the map
