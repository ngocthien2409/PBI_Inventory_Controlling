# PBI_Inventory_Controlling

## 1. Introduction:

### 1.1 Overview of the company:

Adventure Works Cycles, a large, multinational manufacturing company, produces and distributes metal and composite bicycles to North American, European, and Asian commercial markets. While its base operation is located in Bothell, Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. In 2000, Adventure Works Cycles bought a small manufacturing plant, Wide World Importers, which is located in Mexico City, Mexico. Wide World Importers manufactures several critical subcomponents for the Adventure Works Cycles product line. These subcomponents are shipped to the Bothell location for final product assembly. In 2001, Wide World Importers became the sole  manufacturer and distributor of the touring bicycle product group. 

After a successful fiscal year, Adventure Works Cycles is looking to broaden its market share by focusing its sales efforts on the company’s best customers and reducing the cost of sales by reducing production costs.

### 1.2 Business problem:

A production department is a collection of roles within a company that is in charge of producing products. This can range from a small department that converts raw materials, assembles components into finished products, and packages them to a fully functional department that converts raw materials, assembles components into finished goods, and packages them.

AdventureWorks is a business that has a production department that has lots of components in inventory which are placed in different countries, and states,... AdventureWorks mainly produces bicycles that are friendly to the environment.

The process starts with a production request, which is usually initiated by another process, such as delivery, which must complete a customer order (make-to-order strategy), or material preparation, which has decided that the company needs to raise inventory levels (make-to-stock strategy). The production department identified the following requirement want Data team support: 

**Inventory controlling:** Help users review the inventory status of each category of product more quickly and conveniently. Support quantity control so that the Sales Department could be informed about the current stock of each product and know which product is going to be out of stock. It helps users start doing marketing strategies for products and schedule production and business operations to maximize sales and profit.

### 1.3 Import the dataset:

* Log in to your Google Cloud Platform account and create a new project.
* Navigate to the BigQuery console and select your newly created project.
* Select the "Type to search" in the navigation panel on the left then type the project name "adventurework2019" and click "Enter".

### 1.4 Apply Design Thinking Mindset:

#### 1.4.1 Empathize

![image](https://github.com/ngocthien2409/PBI_Inventory_Controlling/assets/155359458/47ed8a2f-acd5-4509-a220-0fc9e633ce8e)

#### 1.4.2 Define point of view

![image](https://github.com/ngocthien2409/PBI_Inventory_Controlling/assets/155359458/867200d5-71ef-4ebf-8512-723e21f40e68)

#### 1.4.3 Ideate

![image](https://github.com/ngocthien2409/PBI_Inventory_Controlling/assets/155359458/7d97da67-2ce0-4f2a-bfd3-a712bcffeadc)

#### 1.4.4 & 1.4.5 Protorype & Review 

![image](https://github.com/ngocthien2409/PBI_Inventory_Controlling/assets/155359458/a9c874bc-ca49-4948-93e9-6d333d19a76c)

## 2. Build Dashboard:

* Using DAX to create measures and calculated columns
* Build 2 report pages

**Inventory Overview**

![z5761912506480_e247ad2e0a8b0dd5b01e88b177197317](https://github.com/user-attachments/assets/76b138b7-5296-4c8a-8ffe-c7fb2d4ed96b)


**Product Inventory Detail**

![z5761912511411_cbde458a9848a5e8581228b1482385bc](https://github.com/user-attachments/assets/a7523b38-157c-4e4f-92c7-4179a7e42b0d)


## 3. Insights:

### 3.1 Inventory Value over periods:

* Inventory Value decreased gradually from March 2008 to May 2011, then rose to April 2013 and finally, solid growth in August 2014.
* The fact that both the Inventory Quantity and Value increased sharply in August 2014 shows that the company needed to reserve many products at that time but the company's storage method was not effective because the percentage of products stored at dangerous levels was very high. The percentage of products at safe level was very low compared to the total number of products being stored, accounting for only 14.6% of the total products.

### 3.2 Inventory Quantity by Category:

* The situation of the company's inventory was extremely concerning because 368 out of 504 products, accounting for 73%, are at dangerous levels.
* There was a paradox in the company's storage: the category with the largest number of stored products, Components, did not have any products at safe level.

### 3.3 Inventory Quantity by Location:

* Products belonged to location Tool Crib accounted for the largest proportion of location distribution and there was a fact that all of these products were at dangerous levels.
* All products within the safety level in storage were located in the location Finished Goods Storage, meaning these products have completed the production process.

## 4. Recommendations:

* Need to store more products in category Components because although the amount of storage was the largest, it did not meet the safety level.
* If the products in the safety level were all in the Finished Goods Storage, the company should have pushed those products to the market for early sale to clear the storage and had more resources to reserve other products.
* All product categories and locations had dangerous products that needed to be stocked, proving that the company was not doing well in Inventory and needs to improve this to facilitate the production process in the future.
