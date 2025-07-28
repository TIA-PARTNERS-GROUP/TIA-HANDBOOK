Make sure that your in the tia_partners_frontend/ or tia_partners_backend/ dir before running these commands

## Package Manager
Using npm
[npm](https://docs.npmjs.com/)
### How to install packages
```console
npm install
```
### How to run 
```console
npm run dev
```

## Documentation
Using storybook
[storybook](https://storybook.js.org/docs)
### How to run
```console
npm run storybook
```

### ENV Setup
### TODO: REMOVE ENV CONFIGURATIONS FROM README
## Backend
```
NODE_ENV=development
PORT=5000
FRONTEND_BASE_URL=http://localhost:3000
MIDDLEWARE=True
DB_HOST=localhost
DB_USER=testuser
DB_PASS=testpass
DB_PORT=5432
DB_NAME=testdb
```

## Frontend
```
VITE_FRONTEND_BASE_PORT=3000
VITE_API_BASE_URL=http://localhost:5000/api
```

## Testing
Using the Jest testing framework
[jest](https://jestjs.io/)
### How to run test 
```console
npm test
```
