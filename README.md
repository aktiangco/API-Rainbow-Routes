# Activity: Getting Started with TypeScript Part 2

- Install package.json: `npm init -y`

- Install the required node_modules.: `npm install`

- View webpage: `nodemon`

- Install TypeScript: `npm install typescript --save-dev`

- TypeScript settings: `npx tsc --init`
    "scripts": {
        "build": "npx tsc"
    },

- tsconfig.json
  - line 58: "outDir": "./build",
  - line 86: "noImplicitAny": true,

- `npm run build`

- Install declaration for Node: `npm i --save-dev @types/node`

- `npm run build`

- Install declarations for Express: `npm i --save-dev @types/express`
