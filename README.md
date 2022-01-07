# Description
A technical sample project for building Web application. 

- Next.js for the front-end
- Nest.js for the back-end
- Firebase Authentication for authentication.

# Getting started
## Requirement
- Node.js v14
<br>
Install v14, not the other versions.

## Initialization
```
npm run init
```
## Running backend server
```
npm run dev:server
```
Then go to http://localhost:8080/graphql
## Running frontend server
```
npm run dev:client
```
Then go to http://localhost:3000

## Generate React Hook query for client from server 
``` 
npm run generate
```
This command generate React Hook Query from 
### Input
```
/member-server/src/schema.gql
/member-client/src/graphql/queries
/member-client/src/graphql/mutations
```
### Output
```
/member-client/src/graphql/generated
```