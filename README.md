#Kroger_Project

## Team Name and Members

- Charles McCollough - 811961114 - charlmc/McCollough-Kroger-P1: MIST 4610 Project (github.com)
- Kaitlyn Schindler - 811910151 - https://github.com/KaitlynSchindler/Kroger
- Amy Do - 811900843 - https://github.com/amydo21/Kroger
- Lucas Sparger - 811580057 - https://github.com/luhttps://github.com/KaitlynSchindler/Krogercassparger/Kroger
- Aidan Daly - 811653166 - https://github.com/apd82722/Kroger 

## Problem Descrption

Our team decided to model a database that describes the inventory, transaction, and ordering system for Kroger. In our group's project we made 12 entities to describe the problem outlined above, along with the relationships between the entities to create a full data model. From the perspective of the store we modeled stores and departments to separate the inventory and order process by departments. From there we added inventory related entities and also transactions between customers and the store to change the inventory entity and provide an accurate total of items in the department of the store. On the other side of the data model we made a way to track the replenishment of inventory through orders from Krogers vendors. This would act like: “The seafood department is running out of fish, they order more fish from the fish vendor, get the invoice, and get the items delivered.” This scenario outlines the process of our solution for Kroger’s orders along with lists of items in the order, vendor names, delivery descriptions, invoices, and payments from the store to the vendor. 

## Data Model

![Kroger_datamodel_Final](https://user-images.githubusercontent.com/128402148/229185416-c6468df9-a700-4e02-8461-8a9008ffbeed.png)
Our team’s data model is based on the different stores Kroger has across the United States. Each store has many relationships with other entities in the table. For example, a store has many transactions, and in those transactions are many items. A store can also make multiple payments to one vendor, and each of those payments would have one invoice. Likewise, a store has many departments, and each of those departments also have relationships with other entities. More specifically, a department can have many inventories, and in each inventory is the quantity of an item (e.g. the Bakery department has cupcakes and cookies, and the quantity of those items are 100 and 50 (respectively)). A department also has many orders, and each order contains many items. Each order is made through one delivery and contains one invoice; however, a vendor can have multiple orders.
