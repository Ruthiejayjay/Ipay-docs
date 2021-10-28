# IPay API Docs

IPay is a FinTech company, you can save, invest, pay bills and apply for loans on the platform.
Live link : [https://ipaytheworld.com](https://ipaytheworld.com)

## List of all APIs
1. Login : 
   - Url : [https://ipaytheworld.com/api/login/login](https://ipaytheworld.com/api/login/login)
   - Parameters : Email (required)
                  Password (reguried)
                  Remember (optional)
   - Method : Post               
2. Register :
    - Url : [https://ipaytheworld.com/api/register/Register](https://ipaytheworld.com/api/register/Register)
    - Parameters : Email (required)
                   Password (required)
                   Confirm Password (required)
    - Method : Post
3. Verification :
   - Url : [https://ipaytheworld.com/api/Verification/VerifyRecipient](https://localhost:44369/api/Verification/VerifyRecipient)
   - Parameters : Email (required)
   - Method : Get
4. Fund Cash Wallet : 
   - Url : [https://ipaytheworld.com/api/wallet/fundcashwallet](https://ipaytheworld.com/api/wallet/fundcashwallet)
   - Parameters : Email (repuired) Amount (required)
   - Method : Post
5. Send Cash Wallet :
   - Url : [https://ipaytheworld.com/api/wallet/SendCashWallet](https://ipaytheworld.com/api/wallet/SendCashWallet)
   - Parameters : Amount (required) Email (required)
   - Method : Post
6. Savings :
   - Url : [https://ipaytheworld.com/api/wallet/save](https://ipaytheworld.com/api/wallet/save)
   - Parameters : Amount (required) Months (required) Currency (USD)
   - Method : Post
7. Buy Package with wallet :
   - Url : [https://ipaytheworld.com/api/wallet/BuyPackageUsingCashWallet](https://ipaytheworld.com/api/wallet/BuyPackageUsingCashWallet)
   - parameters : Email (required) Package (required) Amount(required)    
   - Method : Post
