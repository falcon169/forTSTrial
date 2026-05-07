# forTSTrial
 which npm
    3  npm init --y
    4  npm i -D typescript ts-node @types/node
    5  npx tsc --init --rootDir src --outDir dist 
    6  mkdir src && touch src/index.ts
    7  npm run build
    8  npm run start

    inside package.json
package.json
  "scripts": {
    "build": "tsc",
    "start": "ts-node src/index.ts",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
