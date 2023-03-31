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

## Ten Queries

1. What is the average amount of invoices for each Department? 
- The query will run and show the average amount of invoices for each department in the stores. This is relevant because it could be put in a dashboard for the Kroger manager to see how many invoices were received on average per month if implemented correctly.
![Screenshot 2023-03-30 200727](https://user-images.githubusercontent.com/91034834/229184159-64aa25fc-4657-4d67-a970-0f8f483c5339.png)
2. List the items that were not purchased by Store 1.
- The query will show what items were not purchased. This is relevant because it could show what items are not selling if implemented on a large scale. 
![Q2](https://user-images.githubusercontent.com/91034834/229184234-8f143427-4e7f-4edb-93cd-8ea81ff98c0c.png)
3. Count the number of Deliveries that arrived in April of 2023
- The query will return the number of deliveries that arrived in the month of April (2023). This is relevant because it affects the quantity of items a department has.

![Q3](https://user-images.githubusercontent.com/91034834/229184241-c7798c8b-47af-4e82-8dc8-e622810be37f.png)

4. What is the total revenue for each store?
- The query will return the total revenue for each store. This is relevant because it could be shown on a dashboard for managers to see the revenue for each store in their district. 

![Q4](https://user-images.githubusercontent.com/91034834/229184255-d07624d9-e743-4c5b-977a-cb9d59eeb35d.png)

5. How many orders is Vendor Anonymous responsible for?
- This query will return the amount of orders placed for a vendor to send to a Kroger. This is relevant because it could be used to track how many orders are placed to a certain vendor for a product. 

![Q5](https://user-images.githubusercontent.com/91034834/229184267-9a4ad41b-3e7b-4729-afb7-00950f683332.png)

6. What deliveries included filet mignons and how many were there?
- This query will return the count of orders that have filet mignons in them. This is relevant because it will show the orders that carry the filets, when they will be delivered, etc. 

![Q6](https://user-images.githubusercontent.com/91034834/229184287-898d282d-6b12-4188-a566-1e6128732971.png)

7. How many orders have stores received from each vendor?
- This query will return how many orders a store has for a specific vendor. This is relevant because we can see what vendor the store orders from the most. 

![Screenshot 2023-03-30 202058](https://user-images.githubusercontent.com/91034834/229184423-bfe99b7e-013f-4dd9-9cb6-c72c8611edd4.png)

8. List the name and cost of items that cost more than the average item
- The query will run and show what items are selling for more than the average cost of all of the items. This is important as Kroger can figure out which items are selling for a lot more per product and they could use that information to figure out how they should price adjust.

![Screenshot 2023-03-30 202223](https://user-images.githubusercontent.com/91034834/229184451-e63d6bf6-8d7a-4593-ae66-1b58c08219aa.png)

9. Select the item name and quantity of items whose quantity is greater than the average quantity of their store
- This query will return the name of an item and its quantity if the quantity of that item is greater than the average quantity of the respective store. This gives Kroger an idea of how much inventory their store has. 

![Screenshot 2023-03-30 202345](https://user-images.githubusercontent.com/91034834/229184475-2f61e50d-60e5-4c55-a44c-87a8da7eab7d.png)

10. What is the profit for each store
- The query will run and show the profit made for each store. This is useful as Kroger would be able to find out which stores they should keep and get rid of.

![Screenshot 2023-03-30 202613](https://user-images.githubusercontent.com/91034834/229184493-5eaf98b9-7fd2-4f62-94bc-b07603dfe8d4.png)


## Matrix

![2023-03-31 (13)](https://user-images.githubusercontent.com/128402291/229186991-7fadb6c7-a7c7-48f3-924b-3c0dce69b00c.png)


