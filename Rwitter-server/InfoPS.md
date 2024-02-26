To start with Backend 

1. yarn init -y
2. yarn add typescript -D                (-D is for speficy that it is dev dependency)
3. tsc --init  
            <!-- if not works first install typescript on your system by 
            npm i typescript -->
Now by this command tsconfig.json is created
    - "rootDir": "./src"
    - "outDir": "./build"

4. yarn add express
5. yarn add tsc-watch -D

# To add Apollo Server

1. npm install @apollo/server graphql

# To Run Apollo /graphql

1. yarn add body-parser

# To app Prisma ORM

1. npm install prisma --save-dev
2. npx prisma init --datasource-provider postgresql

Now many files are got added
    1.  In .env paste your postgresql DB id 
    {go to superbase and create new org and get id}
    2.  create the schema in schema.prisma

3. npx prisma migrate dev --name added_user_model
Every time you do any change in schema you have to run this commant again and again
