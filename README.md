# micro-fe

## Installation
Use package manager to install package on every repositories

### [repo]
```bash
cd packages/[repo]/
npm install
```

## Running on Development Mode

To run a whole app/module or container, required to run every module on repositories
### [repo]
```bash
cd packages/[repo]/
npm run start
```
The development mode also allow you to run any module on isolation mode, that mean you can run a single module on specified port base on setting. In default current module will run on:
```bash
http://localhost:8081 => Marketing Module
http://localhost:8082/auth/signup || http://localhost:8082/auth/signin => Auth Module
http://localhost:8083 => Dashboard Module
```



