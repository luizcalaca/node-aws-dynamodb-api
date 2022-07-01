# Node.js API with Express.js and Dynamo DB

## How to configure to get AWS credentials

Create your account and go to IAM service to create a new user, at the final of that you'll get the necessary keys to fill in the .env file

```
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=
```

## You can use the seed.js to get data with axios and store them on DynamoDB

```
node seed.js
```

## How to run the API

```
npm run start
```
