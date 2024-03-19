# 3040 Crypto API
## API Description
Our API will provide our users with all the necessary tools required for crypto trading and managing of your wallet. Below we have included a subset of the API endoints we plan to give users access to. First, we have an endpoint for getting the balance of your account. Next, we give users a way to access their history of transactions. This will return them a list containing all their previous transactions. Finally, we will give users the ability to access the price of any crypto currency.

## Endpoints
* GET /account/history
    * Sample request
      * https://3040crypto/1234134/history
   ```json
    {
      Transaction:
         from - You
         to CryptoWallet - a13te71
         amount - 0.3 btc
      Transaction:
         from - CryptoWallet - b34y37a
         to You
         amount - 6 eth
       Transaction:
         from - You
         to CryptoWallet - b127383
         amount - 3 eth
       Transaction:
         from - You
         to CryptoWallet - a62w3y27ey
         amount - 10 btc
       End of transactions
    }
     ```

* GET /account/balance

   * Sample request
     * https://3040crypto/1234134/balance

  * Sample response
    ```json
    {
     balance: 1234.00
    }
    ```  


* GET /crpto/name/price
  * https://3040crypto/42342134/crypto/bitcoin/price
  * Sample response:
  ```json
     {
        cost: 60864.23
     }
```


