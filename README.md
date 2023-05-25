# Activity: Getting Started with TypeScript Part 2

- Install package.json: `npm init -y`

- Install the required node_modules.: `npm install`

- View webpage: `nodemon`

- Install TypeScript: `npm install typescript --save-dev`

- TypeScript settings: `npx tsc --init`
  - in `package.json` add:
    "scripts": {
        "build": "npx tsc"
    },

- in `tsconfig.json` uncomment and modify
  - line 58: "outDir": "./build",
  - line 86: "noImplicitAny": true,

- `npm run build`

- Install declaration for Node: `npm i --save-dev @types/node`

- `npm run build`

- Install declarations for Express: `npm i --save-dev @types/express`

- `npm run build`

- Update require to import 
  - line 5 before: `const express = require('express')`
    - Hover on require
    - Press: `Quickfix`
    - Press: `Convert require to import`
  - line 5 After: `import express from 'express`