# Inventory-Management-System
An Inventory MAnagement System in python made on Jupyter Notebook/Google Colab. 
Can be accessed on Google Colab or Jupyter Notebook.
Included modules like json and datetime.

The following files have been added: 
       
       >record.json file contains an inventory with 30 pre-recorded items with their ID, availability, expiry date, MRP and profit % 
       
       >record.txt file (in case the json file cant be accessed)
       
       >Inventory Management System.ipynb file with the following functionalities:
           
           1. accessing the record file with the inventory including ID, availability, expiry date, MRP and profit % at any given time
           
           2. checking the availability of chosen products at any given time using their ID
           
           3. generating a bill containing srl no, name of the product, price per quantity
              (which includes the MRP and its profit %),quantity purchased of each product ID with the total price to be paid by the buyer
           
           4. checking if any product has been expired or not at any given time 
              (with the datetime module) along with the expiry date mentioned in the records using the ID of the chosen product
           
           5. the total number of sales made which includes the product IDs of items bought by the buyer along with the quantity purchased in total
       


