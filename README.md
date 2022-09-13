# Food Ordering System using C

This project is a food ordering system, implimented using C language. The code has been sub-divided into separate sub-programs according to the functioanlities used in the program.
This makes the problem easy and simple to understand & debug. This approach of programming is called **Modular Programming**.
### It has the following functionalities:
    * Signup & Login
    * Validating user account
    * Search by food
    * Search by hotel name
    * Cart and order confirmation
   
## Aprroach

###### Sign-up
User has to sign then login before ordering food. <br /><br />
The following inputs have to be submitted by user:<br />
 - Name
 - Email id
 - Age
 - Password
 - Confirm the password
 - Mobile number
 
 ![welcome page](
https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/welcome_page.jpg)
 
###### Validation
For validating the user account the following criteria must match with the user details. Otherwise user account will be invalid. If all the details are correct user account will be created.
- **Name**:  User name must contains alphabets, user can input first name & last name.
- **Age**: Age must be greater than and not equal to 0.
- **Email**: 
    * First character must be an alphhabet(no numbers or symbols).
    * There must be a '@' in the id prior to the '.' 
    * There should be a domain name after '@' & before '.'
    * There should be a dot at the end of id.
- **Password**: 
    * Length of password must be between 8 to 12 characters.
    * There must be at least one uppercase, lowercase, number and special character. 
    * Both password and confirm password should be the same.<br />
    
 ![user-details](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/signup.jpg)
 
###### Login
Email & password are checked & must match with the user details.<br />

![login](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/login.jpg)

![login_details](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/login_details.jpg)

###### Order by hotel or Order by food item
Order by hotel consits of a list of hotels details & their menu. While order by food consists of list of food items along with their price.
User can add the quantity of order.<br />

![hotel](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/select_food_hotel.jpg)

![food](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/search_food_item.jpg)

![order-food](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/item-confirm_cart.jpg)


###### Cart & confirmation
After selecting the food user can choose to move to the cart and confirm order or exit without oredering the food. 
Cart will show the sum total of money of order food.<br />

![cart](https://github.com/sheetalMehta7/food-ordering-system-using-C/blob/main/images/cart_confirm.jpg)
















