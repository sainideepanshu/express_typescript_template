npm init -y
npm install express

// Adding dev dependencies

npm install -D ts-node

npm i -D  @types/express

npm i -D  @types/node

npm i -D  nodemon


// Configuring typescript

npm i -D  typescript

npx tsc --init

// In tsconfig.json file , add include and exclude property below the compilerOptions

"include": [
    "src/**/*"
],
"exclude": [
    "node_modules"
]

//

"outDir": "./dist",

"rootDir": "./src",  



// Running the tyypescript code

npx ts-node src/server.ts

npx tsc   // this command will create a dist folder for us

node dist/server.js // this command now is equivalent to    ::::::      npx ts-node src/server.ts