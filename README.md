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

## Date Dictionary

![Dic 1](https://user-images.githubusercontent.com/91034834/229182016-ecabb3cf-a992-4787-b8c1-d1e17f6c8617.PNG)
![Dic 2](https://user-images.githubusercontent.com/91034834/229182042-704c4992-7455-4f6b-a870-581c6831b3f6.PNG)
![Dic 3](https://user-images.githubusercontent.com/91034834/229182065-ae7f4074-ec6c-4680-a826-f49d1358c461.PNG)
![Dic 4](https://user-images.githubusercontent.com/91034834/229182078-c40383fb-13c0-4c93-95f2-331a7c1bb5bb.PNG)
![Dic 5](https://user-images.githubusercontent.com/91034834/229182093-55b74d30-52b0-4510-a71e-dfb25ccf6d16.PNG)
![Dic 6](https://user-images.githubusercontent.com/91034834/229182103-93ef2b9f-b0ee-4199-b430-8bd625dcc9a3.PNG)
![Dic 7](https://user-images.githubusercontent.com/91034834/229182113-5c97bbc9-3b4a-4d32-afab-ca2ef01424d7.PNG)
![Dic 8](https://user-images.githubusercontent.com/91034834/229182126-c4dc44eb-635b-41d4-962d-057c197e6406.PNG)
![Dic 9](https://user-images.githubusercontent.com/91034834/229182134-aeb05bb7-df49-40d8-8c6b-00457521edc1.PNG)
![Dic 10](https://user-images.githubusercontent.com/91034834/229182155-2689d36e-ab42-4953-a560-ea141d6b078b.PNG)
![Dic 11](https://user-images.githubusercontent.com/91034834/229182173-25f26457-01b3-4629-be93-b026bf410729.PNG)
![Dic 12](https://user-images.githubusercontent.com/91034834/229182196-664bd209-68c8-4a60-a5f8-082d6550670f.PNG)
