# Ethereal Bazaar

Ethereal Bazaar is building a network of merchants to allow for a trustless exchange of inventory and cryptocurrency.


# User Stories:

## Seller
  * Creating an account:
    Accounts can be created via email x password, Facebook or Gmail

  * Creating a listing:
    Listings are created and maintained at no charge. 
    Images are stored in Amazon S3 Json Blob is stored in mongoDB
  
  * Shipping a Product:
    Shipping Labels are generated for seller if selected, otherwise seller is responsible for shipping
  
  * Receiving Funds for a product:
    Funds are held in escrow until product is delivered to customer.        

## Buyer
  * Creating an account:
    Accounts can be created via email x password, Facebook or Gmail
  
  * Browsing Listings:
    Search and filter by category, merchant review and popularity
 
  * Purchasing a Product
    A buyer with metamask installed is able to pay directly to escrow contract.
  
  * Refunding a fraudulent product
    If a Buyer fails to recieve a product as it was advertised in the listing
    They can claim a refund with proof 
    
## Escrow Service
  * Funds are held in Escrow During shipping 1% fee is charged for this service

  * Escrow Protects the buyer and seller from fraud by verfying the product has been shipped and recieved.      
    
## Policies       
    Ethereal Bazaar has a zero tolerance policy for fraud.
    Merchants or buyers found guilty of fraud are permanently banned.
    Sellers are responsible for the legality of the products they list.
    Firearms, illicit substances, and other contraband items are not permitted and will be delisted.  
