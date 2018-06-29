# Fetching Data from Yelp GraphQl API

This repository fetch data from Yelp Api using GraphQL

## Usage

### 1. Clone the repo & install dependencies

```bash
git clone https://github.com/julisbf/yelp-graphql-fetch.git
cd yelp-graphql-fetch
npm install
```

### 2. Create .env file

```bash
touch .env
open .env
```

Add your Yelp Api Token \
`ACCESS_TOKEN = "__YOUR_YELP_API_TOKEN__"`

> **Note:** You’ll need to create a client, join the beta program, and grab the API key from your [client settings](https://www.yelp.com/developers/v3/manage_app)

### 3. Start your server

```bash
node index.js
```

### 4. Fetching data

Go to [http://0.0.0.0:8080/api/location=new+york&term=pizza&limit=6](http://0.0.0.0:8080/api/location=new+york&term=pizza&limit=6)

> **Note:** You can test changing _location and term_ values. _limit_ is not mandatory
