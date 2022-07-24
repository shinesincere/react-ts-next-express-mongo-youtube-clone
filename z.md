> git init
> code .gitignore
> git add .
react-ts-next-express-mongo-youtube-clone>git commit -m 'initial commit'
react-ts-next-express-mongo-youtube-clone>git branch -M main
react-ts-next-express-mongo-youtube-clone>git remote add origin https://github.com/shinesincere/react-ts-next-express-mongo-youtube-clone
react-ts-next-express-mongo-youtube-clone>git push -u origin main




> mkdir server
> cd server

server> npm init -y
server> npm i mongoose express express-async-errors
server> npm i argon2 busboy cors helmet jsonwebtoken nanoid pino
server> npm i zod zod-express-middleware cookie-parser http-status-codes mongoose-slug-generator
server> npm i @mantine/form @typegoose/typegoose
server> npm i typescript ts-node-dev pino-pretty -D
server> npm i @types/busboy @types/cors @types/cookie-parser @types/express @types/jsonwebtoken -D

server> npx tsc --init