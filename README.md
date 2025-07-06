# SimTrade
SimTrade is an application that simulate a real-time stock trading platform where users can connect, buy/sell stocks, lend/borrow money,view live market data, and compete on leaderboards

It's build with the stack React Native / Spring boot.

You can download the app mobile from [here]().

The backend has a multi-service architercture with principals service :
- [user_service]() which manage account, authentification, and leaderboard
- [order_service]() which hold the stock trading, transaction and loan management
- [market_service]() which deal with the market data in real time

Each service API is accessible at /{service_name}/api.

I am currently writing the useful documentation of the each service. Let's me know if there is any finance-API you want be added to the app.

## Run the backend locally
```
docker login 
docker compose pull # or docker-compose pull if it docker compose version 1 or it's on windows
docker compose up
```
## Download the mobile 
You can download the mobile application from [here](). This apk is directly connect to my hosted backend. 
