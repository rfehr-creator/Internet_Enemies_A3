# 3040 Crypto API
## API Description
Our API will provide our users with all the necessary tools required for crypto trading and the managment of their wallets. Below we have included a subset of the API endoints we plan to give users access to. First, we have an endpoint for getting the balance of your account. Next, we allow users to access their history of transactions. This endpoint will return a list of all their previous transactions. Finally, we will give users the ability to access the price of any crypto currency. This is a service many of our competitors already provide so it is essential we provide it as well. Our overall goal with this API is to make it easy for developers to implement crypto into their systems without needing to know anything about crypto. For example, to get the balance for a specific account we just need the account number and the system will do complex things like scanning all transactions and actually getting the balance.

## Endpoints
* GET /{account}/history
    * Sample request
      * https://3040crypto/1234134/history
   * Sample response
      ```json
      [
         This will be a list of transactions for the specific account
      ]
      ```

* GET /{account}/balance

   * Sample request
     * https://3040crypto/1234134/balance

  * Sample response
    ```json
    {
     balance: 1234.00
    }
    ```  


* GET /crpto/name/price
  * https://3040crypto/crypto/bitcoin/price
  * Sample response:
  ```json
     {
        cost: 60864.23
     }
   ```
