MERN MEMORY CARD
//PACKAGE JSON ITEMS
"frontend": "npm start --prefix frontend",
"frontendinstall": "npm install --prefix frontend",
"dev": "concurrently \"npm run server\" \"npm run frontend\"",
"heroku-postbuild": "NPM_CONFIG_PRODUCTION=false npm install --prefix frontend && npm run build --prefix frontend"
//
