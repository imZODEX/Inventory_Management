1. Open terminal and enter & "<location of .venv>/.venv/Scripts/Activate.ps1"
2. Now Run the server using command py manage.py runserver
3. Django Admin Credential is user name- admin and password- admin and url is http://127.0.0.1:8000/admin/
4. Site admin Credential is user name- s@gmail.com and password- 12345678 and url is http://127.0.0.1:8000/
5. You can register users.
6. I you want to register as admin you need to do it from Django Admin or change SQlite data base.


FEATURES

1.1	User Interfaces 
Customer View (can register and login) 
1.	Registration 
    a.	Signup and logging page 
2.	The home page will show one navigation bar (site name, home, orders history, Cart, search bar, username – change password, help, logout, view profile) and items list with image, price to buy. 
3.	Cart should show selected items  
    a.	Add to cart option on items  
    b.	All items in cart  
    c.	Cumulative price and solo price of items 
    d.	Cart items will have removed option 
4.	Payment link should come on checkout  
    a.	After clicking on buy the user will see the total amount to pay and payment receipt and confirm button. 
5.	Mail notification at successful order placement  
    a.	All transection details will be sent by mail to the user and to the admin also.

 
1.2	Admin Interfaces 
Admin view (We will make admins) 
1.	Logging page same logging page as user, if login credentials match administrator credentials, then admin interface will show  
2.	The home page will show one navigation bar (site name, home, orders placed, add items and category, search bar, admin name – view profile, change password, help, logout). 
3.	Items list with image, price and edit item details will be there. 
4.	Add product 
5.	Disable Product  
6.	Change product (Price, Update details)

You can also use email server using proton SMTP server that is also in this.