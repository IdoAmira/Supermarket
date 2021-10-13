## Supermarket

Employee management system and organization of supplying products in the supermarket

The main purpose of this system is to help supermarket employees be in control of the store's product inventory as well as management of store employees.
The system will save time and reduce resources by storing the information in a convenient way that will allow easy identification. In addition, the system will reduce human errors by providing accurate service with minimal possibility of errors.
The system is written according to the MVC model, in addition there are uses in additional design patterns such as Observer, Singleton and Factory.
____________________________________________________________________________________________________________________________________________________________
## Class Diagram

![model](https://user-images.githubusercontent.com/68790040/137127351-b7502539-fdc0-493b-b8b7-6f0ba66be50c.png)

![controller](https://user-images.githubusercontent.com/68790040/137127349-26c48946-ed25-4460-8e7d-8f11a07ccc32.png)

![mvc](https://user-images.githubusercontent.com/68790040/137127367-e5057af1-d4fe-4b09-b3f4-46090d470b5d.png)
____________________________________________________________________________________________________________________________________________________________
## App screens

#### Main Menu

![menu](https://user-images.githubusercontent.com/68790040/137127365-0533dac8-318d-4737-b2bb-1cfb4a98c990.JPG)

![login](https://user-images.githubusercontent.com/68790040/137127362-4e535183-cd3d-48c3-94f7-8991c2416ee2.JPG)

The main menu navigates each employee to his part of the system.
Each employee should press the button with his job and then a login window will open for him.
In the login window the employee is required to enter his employee number and according to this the system knows whether the employee has clicked on his real job.
____________________________________________________________________________________________________________________________________________________________
#### Manager

![manager](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)

The manager's job is to manage the employees in the supermarket.
When the manager enters the system with his details, a table appears with all the employees and their details (employee number, name, hourly wage, monthly hours).

Manager actions in the system:

- Issuing a salary report to employees

    ![salaryReport](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Update employee details

    ![updateEmployee](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Adding an employee

    ![addEmployee](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Deleting an employee

    ![deleteEmployee](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
____________________________________________________________________________________________________________________________________________________________
#### Storekeeper

![warehouse](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)

The warehouse worker's job is to manage the supply in the warehouse and deliver products to the store.
When the warehouse worker enters the system with his details, a table appears with all the products in the warehouse and their details (barcode, name, current quantity in the warehouse, maximum quantity that can be in the warehouse).

Warehouse worker actions in the system:

- Adding a new product to the warehouse

    ![wAddItem](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Update product details

    ![wUpdateItem](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Deleting a product from the warehouse

    ![wDeleteItem](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Add to order list from supplier

    ![wOrderItem](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Create an order report according to the order lists

    ![wCreate](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
____________________________________________________________________________________________________________________________________________________________
#### Store Worker

![warehouse](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)

The job of the store employee is to manage the supplies in the store.
When the store employee enters the system with his details, a table appears with all the products in the store and their details (barcode, name, current quantity in the store, maximum quantity that can be in the store).

Store worker actions in the system:

- Update product details

    ![sUpdate](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Add to order list from warehouse

    ![sOrder](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
- Create an order report from the warehouse

    ![sCreate](https://user-images.githubusercontent.com/68790040/136853340-9b6f6226-c074-4430-a838-8cae84c13466.JPG)
    
____________________________________________________________________________________________________________________________________________________________
#### Important note:

In order to use the system for the first time without knowing the staff ids I made an admin manager for the system.

All you need to do is run the program, click Manager and then write "admin" in the id box, after that you can know all the staff ids and even creat new ones.

Another thing you need to know is if you want to change/order something from the tables you have to click it in the table and then select the option you want.
