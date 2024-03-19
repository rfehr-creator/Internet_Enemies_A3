# 3040 Crypto API
## API Description

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


