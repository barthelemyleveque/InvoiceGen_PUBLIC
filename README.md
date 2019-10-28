# InvoiceGen_PUBLIC

Presentation of the web-app I am working on as a Freelance for the company Rotarex. Because of the sensitive nature of some information, the code is kept private.

Rotarex needed a web-app where existing customers can generate invoices for a fire-prevention system directly online, rather than through a time-consuming exchange of e-mails. 

This MVP is built fully in PHP, and data-storing and collection is done through MySQL.

# Landing Page
![Landing](https://i.ibb.co/XLcdz57/Screen-Shot-2019-10-28-at-9-34-30-AM.png)

# Account Creation 
![Account](https://i.ibb.co/72vrvQm/Screen-Shot-2019-10-28-at-9-34-45-AM.png)

In order to create an account on the web-app, you need an access key given by a Sales Rep. This allows identification of the Client ID and the potential discounts associated/

# Project Informations
![Project Infos](https://i.ibb.co/DpNmp00/Screen-Shot-2019-10-28-at-9-35-51-AM.png)

Once logged-in, the client has to fill a form with some basic information about his project.
But depending on the Product Line and the type of Gas that is concerned, the invoice generator will change.

# Invoice Generator
![Invoice Gen](https://i.ibb.co/bKrXz33/Screen-Shot-2019-10-28-at-9-59-15-AM.png)

Depending on the client system features, the collection of products will be affected. Each little change in one characteristic can have a crucial impact on the mix of products needed to effectively protect it from fire hazard. 

This required an effective use of MySQL queries in order to generate the related invoice : 

# Invoice
![Invoice](https://i.ibb.co/WcWcHYg/Screen-Shot-2019-10-28-at-9-38-55-AM.png)

As requested, the individual prices of the components were not to be shown, only the final price.
When the MVP is validated, this page will generate a .pdf that will be mailed to both the client and his associated sales representative.
