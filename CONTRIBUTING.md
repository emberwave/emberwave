todo: add stuff

# info

use prettier extension there is already a prettier config for this project (dont change)

the package manager is pnpm

start the app by running 
`pnpm start:dev` 
* does not work without env vars (database url)

client are server are git submodules
client is hosted on port 3000
server is hosted on port 9000

# client

the client is made with nextjs, typescript, styled by tailwind, and uses apollo-client for fetching

# server

the server is using mongodb and uses apollo-server-express
we also use prisma use `pnpm prisma:gen` to generate a new prisma client
it supports rest and graphql but we dont really use rest