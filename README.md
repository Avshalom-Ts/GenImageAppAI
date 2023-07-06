# App that used [Dall-E AI](https://openai.com/) to generate image and save it to [cloudinary](https://cloudinary.com/) as post in [mongoDB](https://www.mongodb.com/).

# Usage:

1. Connection in the terminal to mongoDB
   mongosh --port 27017 admin -u <user_name> -p <password>

2. use <Your desired database>

3. db.createUser({
   user: "<user_name>",
   pwd: "<password>",
   roles: [{ role: "readWrite", db: "<Your desired database>" }]
   })

4. Make copy and fill the credentials..
   `cp env-exemple.env .env`

5. Start the aplication:

## `cd client && npm run dev` and open `http://localhost:5173`

6. Start the api:

## `cd server && npm run start` and open `http://localhost:8080`

### ENGOY!!!
