# Contador

Contador is a full stack web application & serves to assist users track the spending habits. Contador is Spanish for accountant. Users can create categories of purchases such as subscriptions, car payments, outdoor dining, etc. Each category routes to the transaction page for users to create a dated log of every purchase such as multiple gas purchases, Chipotle purchases, Netflix or Disney+ purchases, etc. Contador then calculates total spend. 

###Category
![categories](https://user-images.githubusercontent.com/87147191/213731309-ecdfaa56-5f1e-4ecd-950d-804788c5f2b3.jpg)

###Transactions
![Screenshot (579)](https://user-images.githubusercontent.com/87147191/213731421-0af649d2-0ef8-4757-b005-cbe905ee51e7.png)

## Stack

> Node.js v16 LTS is recommended

_Backend API_

- express.js (v4.18.2)
- sequelize.js (v6.25.2)
- PostgreSQL (v14 recommended)

_Frontend React client_

- Based on `create-react-app`
  - pre-configured to work with the api
- Bootstrap (v5)
  - added to `/client/public/index.html` (_optional_ can be removed)
- React Router (v6)

### Running the app locally

For local development you will need two terminals open, one for the api-backend and another for the react-client.

_Clone_ this app, then:

```bash
# api-backend terminal 1
cp .env.example .env
npm install
npm run dev
```



```bash
# react-client terminal 2
cd client
npm install
npm start
```

- api-backend will launch at: http://localhost:8080
- react-client will launch at: http://localhost:3000

