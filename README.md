## Console-based-Inventory-Management-System

1. Supermarket Inventory Management.

An up and coming supermarket has been managing its inventory manually so far by
entering details of inventory and sales on spreadsheets one by one by a staff member.
However, due to the gradual expansion of the business, hiring of more staff and the
recent increase in demand for online sales due to the pandemic, it has become
increasingly difficult to keep track of everything manually and security risks have also
become a major concern. Therefore, the owner has decided that it is in the best interest
of the business to switch to an autonomous inventory management system and has
hired your team to implement it.

2. Basic requirements.

After a meeting with the client, the following requirements have been roughly identified:
Stock.The Inventory management system is responsible for storing and managing all details
regarding the stocks in the inventory. The details of items include the name of each
item, how many of each item are in stock, retail price, any discounts/promotions and the
final price after any discounts. Items in the inventory can be broken down into 10 major
categories. Produce (fruits & vegetables), Meat & Seafood, Grains (rice, dhal etc.),
Bakery products, Frozen foods, Dairy products, Snacks and Sweets, Beverages, Health
& Beauty (toothpaste, shampoo etc.) and Condiments & Spices. The stock of Produce,
Grains and Meat & seafood must be measured in grams. All other item categories
should be measured by the number of items in stock. All item categories except the two
fresh categories (Produce and Meat & seafood) must also record the brand of the
product and whether it is a local or imported product. Promotions are special discounts
that can apply to a single item, a brand of item or a category of item. The discounts are
recorded as percentages; the final price must be calculated by deducting the discount
percentage from the retail price of the eligible items.

3. Staff

The inventory system will be managed by the staff of the supermarket chain and the
amount of control over the system will be decided by the position of the staff member.
Each staff member has a username and password that must be entered in order to
access the inventory system. The full name, position and join date of all staff members
must be recorded. The lowest tier member of staff is the floor worker. The floor workers
are responsible for stocking up the items and hence can only increase the number ofstock of an existing product in the inventory. Next are the cashiers, who are responsible
for all transactions with the customers and have the ability to reduce the stock of the
relevant items after a successful transaction with a customer. The transactions must be
recorded separately, with the name of the cashier, customer and list of all the items
bought. The managers can add or remove items from the inventory and check the
details of other staff members in addition to being able to perform all the actions of the
cashiers and floor workers. The owner is the only user that is able to add or remove
staff members and is able to perform all other actions listed above. There can be only
one owner account.

4. Supply

Finally, the details of the supply chain that brings stock into the inventory must be
recorded. The supply to the supermarket comes from both local and international
sources. The local supply is transported from various farms and factories throughout the
island and in three types of vehicles; large trucks, small trucks and vans. Each vehicle
can only transport one type of goods at a time and are identified by their vehicle
registration number. Each local supply shipment must include the name of the item,
quantity, name of origin (the name of the farm/factory, date of departure (from the farm
or factory), date of arrival at the supermarket and vehicle used for the transportation.
International supply shipments will only be imported overseas by ship and should
include country of origin, the ship number, date it arrived at the local harbour and the
date it was transported to the store. All supply shipments will be given a pending status
until a staff member inspects the items and adds them to the stock. A floor worker is
able to approve and add stock of an existing item in the inventory. If the received item
does not yet have an entry in the inventory, a manager or the owner is required to first
make a new entry for the item in the inventory before adding the stock. Once the stock
has been successfully added to the inventory, the status of the supply shipment must be
changed to “approved”.



