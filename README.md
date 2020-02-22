# SOXS E-commerce Platform

SOXS is an Asia-based specialist retailer of socks. Found in 2010 by Elizabeth Graham and Jennifer Greive, they started their first store in Singapore. Till date, the socks are sold in over 1,000 distribution stores across Asia. <br><br>
The store is looking to further the sales of the products by creating a online platform for their customers to make purchase. The wesbite is designed to meet the user experience and deployed in Heroku with the link below: <br><br>
**https://nyt-soxs-store.herokuapp.com/** <br><br>

## UX Design- User Stories
### Customer View
1) “I want to view the products from any device via my laptop or mobile device.”
2) “The interface must be simple and easy to use.”
3) “I want to view the products in category that I want.”
4) “I must be able to search products that I want using text search.”
5) “I want to filter the products by the price to look for the socks that is within my budget.”
6) “I want to make online purchase of the socks trhough secure payments.”

### Company Goals
1) “The company wants to build up the product branding by setting up a online platform.”
2) “The company wants to improve the product sales by allowing customers to make online purchase.”
3) “The company wants to collect contact details of customer so that the company can inform them of any new products or promotion.”

## Project Structure

### Wire Frame
The wireframe can be viewed in the link below:


## Project Skeleton

### Features

Page | Description
--- | ---
Top Navigation Bar | The navigation bar has the following items: <br><br> 1. **Company Logo** - *direct to the index page when customer click on it.* <br> 2. **About** - *direct to the About Us page.* <br>  3. **Category** - *Display 3 links, MEN, WOMEN and KIDS, when hover over. Customer can go to individual category when they click on the link.* <br> 4. **Shop** - *direct to the Show_Item page which displays all the socks for the customer to choose.* <br> 5. **Login** - *direct to the login page for users to log into their account. The Log in will change to Log out after the user login. User will log out their account when they click on the Log Out link.* <br> 6. **Search Icon** - *Search Textbox will be displayed when customer clicks on the icon. Customer can input the product name and press the Enter key to conduct the search.* <br> 7. **Cart Icon** -  *this icon will display the number of items that the customer added to the cart. Customer are direct to the View_Cart page to see their cart items.* <br><br>
Footer Bar | The footer bar has the following items:<br><br> 1. **About Us** - *A short Introduction on the Organisation and link to direct the customer to the About Us page with full details of the organisation.* <br> 2. **FAQ** - *direct to the FAQ page* <br> 3. **Privacy Policy** - *direct to the Privacy_Policy page* <br> 4. **Return & Refund** - *direct to Return_n_Refund page* <br> 5. **Terms & Condition** - *direct to Term_n_Condition page* <br> 6. **Company Contact Information** *such as Email, Contact Number and Address are shown here.* <br><br>
Index | This is the landing page. The **Shop Now** button in the middle of the page will direct the customer go to the show_item page to start their online shopping.  <br><br> There are also 3 links below, MEN, WOMEN and KIDS which allow the customer to go directly to the category of products without going through the entire product list. <br><br>
About |	This is the About Us page that introduce the Company to the customer. Full description such as Company History and Team members of the organisation are display here. <br><br>
FAQ	| This page display some of the frequent questions asked by the customer. This is display in the bootstrap feature and collapse feature. The answers will be displayed in the expanded views when customer click on the questions in the collapse view. <br><br>
Privacy_Policy | This page displays the Privacy Policy of the Company. <br><br>
Return_n_Refund	| This page displays the Return and Refund Policy of the Company. <br><br> 
Terms_n_Conditions | This page displays the Terms and Conditions of the Company. <br><br>
Show_Item | This page displays all the socks in the store. <br><br> Customers can filter the list of the socks by adjusting the price bar on the right side of the page. Only socks that fit in between price range set by the customer will be display. <br><br> In addition, customer can view the list by their category, MEN, WOMEN or KIDS. <br><br>
Create_Item	| This page let the staff of the store to add new products. Details like Product Name, Product Image, Color, Material, Size and Price are mandatory to fill in before the staff can add the item. <br><br>
Update_Item	| This page allows the staff of the store to amend or update the products details. <br><br>
Delete_Item	| This page alllows the staff to delete the products from the product list. <br><br>
View_Cart |	This page displays all the products that the customer added to the shopping cart. The product image, name and price will be display for individual item. Customer can change the quantity of the purchase. The sub total and grand total price will change accordingly to tell the user how much they need to pay for the purchase. <br><br> Customer can continue shopping for more products by clicking on the continue shopping button. <br><br> Once the customers are satisfy with their purchase, they will click on the checkout button to make payment. <br><br>
Checkout | This page is the payment page using Stripe Online Payment Platform. Customer will see the items and the amount that they will be paying. They will be able to pay through their credit card. <br><br>
Thankyou | After succesful payment, the customer will be directed to this Thank you page. <br><br>
Login |	This page allows the customer to log into their account using their username and password. There is a link for the new user to go to the Sign Up page to register their new account.There is also another link to the Password reset Page for User to reset their password. <br><br> The staff with administration account can log in using this log in page. After they log in , they will be able update and delete the product items. Normal user will not able to amend or the delete the products. <br><br>
Logout | After the user log in, the Log In link in the navigation bar will change to Log Out link. User can click on this link to log our their account. <br><br>
Sign Up | This page will allow customer without any account to sign up for one. They will receive news on the store latest Products and Promotion. <br><br> The store can build up their customer base using all the emails collected to promote their products. <br><br>
Password Reset | This page is Django default password reset page. User will be ale to reset their password when they enter their email address. <br><br>
Base | This is the template HTML containing the Navigation and the Footer page. All the rest of the pages inherient their Naviagtion and Footer from this Base HTML. <br><br>

### Features to implement in the future
1. I will like to add in the stock element so that staff do not need to keep track of the products stocks level. The staff will be prompt to replenish the stocks if there is no more stocks available.
2. I will like to add in virtual assistant to assist the customer on any queries and issue that they faced.
3. I will like to generate feature to generate self generate invoice for the customer.

## Project Surface
The theme that I wished to present is simple and user-friendly website as per the user requirement

### Colours
● **White and Blue** are main colors chosen for the website. <br>
● **White** - The White background is choosen so that the colourful socks image will stand out. <br>
● **Blue** - Blue Color is choosen to make the customer feel comfortable and at peace. Blue also subtle messages of trustworthiness and serenity, loyalty and tranquill. <br><br>

### Technologies Used
● <a href = "https://aws.amazon.com/cloud9/"> **Cloud9** </a> - The project was developed using Cloud9 Integrated Development Environment. <br>
● **HTML** - The project uses HTML to create the pages. <br>
● **CSS** - The project uses CSS to style the pages. <br>
● <a href="https://getbootstrap.com/">**Bootstrap**</a> - The project uses Bootstrap for styling and responsive design. <br>
● <a href="https://fonts.google.com/">**Google Fonts**</a> - The project uses Google Fonts to style the Fonts. <br>
● **JavaScript** - The project uses JavaScript for responsiveness. <br>
● **Python** - The project uses Python to write the websites logic. <br>
● **Django** - The project was built using the Django framework. <br>
● <a href="https://stripe.com/en-sg">**Stripe**</a> - The project uses Stripe for handling online payments. <br>
● <a href="https://uploadcare.com/">**Uploadcare**</a> - The project usess Uploadcare for uploading all the products images. <br>
● <a href="https://github.com/">**GitHub**</a> - The project uses GitHub as it's version control system. <br>
● <a href="https://id.heroku.com/login">**Heroku**</a> - The project uses the Heroku platform for hosting the website. <br><br>

## Testing
### Manual Testing

Test Case(s) | Test Description | Result
- | --- | - 
--- | **Home Page** | ---
1 | I clicked on the Update Product button which will direct to Update products page with the item detail displayed in the textbox. | Pass 
2 | I could click on individual link which will bring me to the respective page. <br> ● **About** in Navigation Bar- direct to **About Us Page** <br> ● **FAQ** in Footer- direct to **FAQ Page** <br> ● **Return & Refund** in Footer - direct to **Return & Refund Page** <br> ● **Terms and Condition** in Footer - direct to **Terms and Conditions page** | Pass
3 | I clicked on the Shop Now Button which will bring me to the show_item.html that displays all the socks | Pass
4 | I clicked on the picture with MEN, WOMEN and KIDS. It should display on the socks of that category. I should get the same result when I clicked on MEN, WOMEN and KIDS under the Catelog in the Navigation Bar.	| Pass
5 | I clicked on the magnifying glass in the navigation bar, a textbox should display with prompt message “Search products and hit enter”. <br> I should be able to key in the product name and press enter to conduct the search. It should bring me to show_item page which shows only socks name that match the search keyword. | Pass
6 |	I clicked on the company email address in the footer. It should open up a new email message with response to the company email address. | Pass
- |	**Show Item Page** | -
7 |	From the Show Item Page, I should able to see the socks displayed with the details like Picture, Name, Categories, Material, Size and Price. There should be a Add to Cart Button for each socks | Pass
8 |	I clicked on the link, MEN, WOMEN and KIDS under the Categories on the right side of the page. It should display on the socks of that category. | Pass
9 |	I clicked and dragged the minimum price to $20. Socks with price less than $20 will be filter away. Only socks with price more than $20 will be displayed. | Pass
10 | I clicked and dragged the maximum price to $10. Socks with price more than $10 will be filter away. Only socks with price less than $10 will be displayed.	| Pass
11 | I clicked on the Add to Cart Button. That sock will be added to my shopping cart. The number on the cart icon in the navigation bar will increase by one. | Pass
12 | I clicked on the shopping cart icon in the navigation bar. It should direct me to my shopping cart page. | Pass
- |	**Shopping Cart Page** | -
13 | From the shopping cart page, I should able to see the items that I added to the shopping cart with the following details. Sock picture, Name, Price, Quantity. | Pass
13 | The Cart Totals should display the total price of the all the items in the shopping cart | Pass
14 | I clicked on the Cross button in the Remove Column. The item in that row will be removed from my shopping cart. The Cart total price should subtract that item price. | Pass
15 | I clicked on the Proceed to Checkout Button. It should direct me to the Checkout Page | Pass
16 | I clicked on the Continue Shopping Button. It should direct me back to the show item page. | Pass
- | **Checkout Page** | -
16 | From the Checkout page, I should be able to see my company name, items in my shopping cart and their individual price as well as the total price. | Pass
17 | I clicked on the Back to SOXS Store link. It should direct me back to the show item page. | Pass
18 | Enter the following information: <br> - Any email address in valid format. <br> - Testing credit card number 4242 4242 4242 4242 in the card information. <br> - 03/22 in MM/YY <br> - any 3 numbers in CVC <br> - Any name in Name on Card <br> - Singapore in Country or region <br> I clicked on the Pay Button. I should be to pay successfully. |	Pass
19 | I clicked on the Back to SOXS Store link. It should direct me back to the show item page. | Pass
20 | After successful payment, I should be directed to Thank you page and show message that my order is successfully completed. | Pass
21 | I clicked on the Back to Shop Button which should direct me back to the show cart page to view all the socks. | Pass
22 | I clicked on the Log In link in the navigation bar. It should direct me to the Log In page	| Pass
- | **Log In Page**	| -
23 | From the Login Page, I should be able to Log In the customer account <br> Username: Test <br> Password: zaq1@WSX <br> It should direct me to the show_item page and display all the socks. | Pass
24 | After I Log in, the Log In link in the navigation bar should change to Log Out. I clicked on the Log Out link which will Log Out my Account and re-direct to Home Page. | Pass
25 | From the Login Page, I key in a wrong username and password. It should not Log In any account. An error message will be prompt “Your username and password didn't match. Please try again.” | Pass
27 | From the Login Page, I should be able to Log In using the staff  account below: <br> Username: admin <br> Password: admin123 <br> It should direct me to the show_item page and display all the socks. <br> 3 additional buttons will be displayed. Update Product, Delete Product and Add New Product. These 3 button should not be displayed when normal customer Log in. | Pass
28 | From the Log in Page, I clicked on the Lost  password link. It should direct to the Django default Password reset page. <br> I enter the registered email address and clicked Reset my password button. <br> Instructions for resetting your password will be send to the email. | Pass
29 | From the Login Page, I clicked on Sign Up Here link for New User. It should direct me to the Sign Up Page. | Pass
- | **Sign Up Page** | -
30 | From the Sign Up Page, I should be able to register a new account by filling out the information <br> Username, First Name, Last Name, Email, Password and Password Confirmation. <br> After I sucessfully sign up an account, it should direct me to the show item page in Log In status.	| Pass
31 | I tried to sign up using an existing username. Test. An error message will be prompt “A user with that username already exists.” I am unable to sign up a new account with that username. | Pass
32 | I left out the username and password and clicked on the Sign Up button. An error message will be prompt to fill up the required details. | Pass
33 | I sign up using a different password for Password and Password Confirmation. An Error message is prompt “The two password fields didn't match.” | Pass
- | **Add Products Page** | -	
34 | After I log in using the staff account, <br> Username: admin <br> Password: admin123 <br> I clicked on Add New Product Button which will direct to the Add products Page | Pass
35 | From the Add Products Page, I am able to add new products by filling in all the details and upload the product image. The new products can be found in the Shop Page | Pass
- | **Update Products Page** | -
36 | I clicked on the Update Product button which will direct to Update products page with the item detail displayed in the textbox. | Pass
37 | I amended the product details and clicked on the Update Products Button. The product details are updated and display in the Shop page | Pass
- | **Delete Products Page** |-
38 | I clicked on the Delete Product button which will direct to Delete products page with a confirmation message to ask if I want to delete the product | Pass
39 | I clicked on the No Button. It will direct to the Shop Page. The product is not deleted | Pass
40 | I clicked on the Confirm Delete Button. The product is deleted. It cannot be found in the Shop Page. | Pass

### Responsiveness
The websites are tested on mobile phone and desktop. In addition, the pages are tested using different viewport under the inspector tool. The site is fully responsive - it's mobile and desktop-friendly.,br><br>

#### Website Desktop View

<img src="/static/Readme_image/desktop_view.jpg">

#### Website Mobile View

<img src="/static/Readme_image/mobile_view.jpg">

### Problems Encountered/Bugs solved
● I was unable to add in filter by price feature in the first place. After going through the main.js with the Teaching Assitance, John. We managed to do it by adjusting adding and adjusting the min and max price into the javascaript file. <br><br>

## Upload Files to Github
This project was written using AWS Cloud9 IDE, uploaded to Github for version control. <br>

1.At the start of the project, I created my first Index.html file in Cloud9. <br>
2.Next, I opened a new terminal and type in the git init command to initialize a local repository. <br>
3.A new remote repository was created with a name SOXS_Store. <br>
4.After creating the repository in GitHub, I copy the code given back in Cloud9 to link the local repository to the remote one. <br>
5.Under the new terminal in Cloud9, the Index.html is added using the git add command. <br>
6.I typed in the command ```git commit -m “Initial commit”```, which puts the file into the staging area for the first commit. <br>
7.Next, I used the git push command to send the file to the remote repository. <br>
8.The terminal will prompt for the username and password. <br>
9.The command git add, ```git commit -m “message”``` and ```git push``` are used to saved the rest of the files and pictures to the remote repository. <br>
10.I tried to push the code regularly to Github every time there is any updates to the files. It served as a backup as I know I can go back to my history to retrieve my earlier codes if I messed up my current codes in Cloud9. <br>

## Deployed Webpage to Heroku
The website has been deployed to Heroku with reference to our lecturer Mr Paul Chor’s notes. <br>

### Part A  Dependencies
**Step 1** Go to <a href ="https://www.heroku.com">Heroku</a> and register for an account. <br>
**Step 2** Install the Herkou CLI in your system <br>
In your bash terminal, install the Heroku CLI by running the following command:

```sudo snap install heroku --classic```

**Step 3** Install dependencies

We need to install a few dependencies so that our project can work on Heroku. Run each of the following commands one by one.

```sudo apt install libpq-dev python3-dev```

And the following as well:

```
sudo pip3 install gunicorn
sudo pip3 install psycopg2
sudo pip3 install Pillow
sudo pip3 install whitenoise
sudo pip3 install dj_database_url
```

Add Whitenoise to your middleware inside settings.py:
```
MIDDLEWARE = [
.....
'whitenoise.middleware.WhiteNoiseMiddleware'
]
```

###  Part B Creating the Heroku App

**Step 1** Make sure you already have a git repository for your project.
If you do not have a .git hidden folder yet or no (master) after your directory name in your terminal, then you do not have a git repo.

Follow the steps below to initialise a new repository.

```
git init .
git add .
git commit -m "Initial commit"
```

**Step 2** Make sure you have a .gitgnore file
Check if you have a .gitignore file. If you have it, or not, make sure it looks like this: http://gitignore.io/api/django

Then at the end of the file, add in the following lines
```
.c9
```

**Step 3** Log into Heroku
Log into Heroku using the following command:

```
heroku login -i
```

**Step 4** Create the Heroku App

From this point on, make sure that you have logged into Heroku in your terminal.

Inside the terminal, we are going to create a new Heroku App. Take note that the name for the Heroku app must be unique in the entire universe. So if your app is rejected because the name already exists, try a different name.

```
heroku create SOXS

```

**Step 5** Double check the Heroku App has been created successfully.
Heroku will add two origins to your git remotes. Do a check by running the following:

```
git remote -v
```

You should see two more origins with the word heroku in the URL.

**Step 6** Copy environment variables over

1. Open your ```.bashrc file``` in Cloud9. 
2. Open a new browser tab, and go to http://www.heroku.com 
3. Click on your app in the dashboard.
4. Click on Settings
5. Click on Reval Config Vars
6. Copy the exported variables in .bashrc over to the Config Vars and omit the quotes.

## Part C Getting Ready for First Deployment

**Step 1** Create Procfile
The ```Procfile``` contains a command that Heroku will run when the app starts. In the root folder, create a file named Procfile

**Step 2** Add Command to Procfile
Open the Procfile, and enter the following and replace SOXS_Store.

```
web: gunicorn SOXS_Store.wsgi:application
```

**Step 3** Update ALLOWED_HOSTS inside settings.py

Add the domain name (AND JUST THE DOMAIN NAME ONLY. i.e without the HTTPS) of the  the heroku app into the ALLOWED_HOST inside settings.py (you can check by going to the app inside your Heroku dashboard, then click the [Open App] button on the upper right corner of the screen).

**Step 4** Generate requirements.txt

We need a requirements.txt file in our Git repository so that Heroku will know what packages install.

```
pip3 freeze --local > requirements.txt
```

**Step 5** Add STATIC_ROOT to your settings.py file
We need this for Whitenoise to work (so that it can serve static files properly):

```
SOXS_Store/settings.py
STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')
```

Also make sure when you use static files in your template, you make use of the {% static .... %} helper.

Example
```
{% load static %}
<img src="{% static "images/hi.jpg" %}" alt="Hi!" />

<!-- DON'T WRITE THIS -->
<img src="/static/images/hi.jpg" alt="Hi!" />
```

**Step 6** Deploy
To deploy Heroku, first, commit your code to your git repo

```
git add .
git commit -m "your commit message"

After which, make a push to Heroku:

git push heroku master
```

## Credits
The photos in the Home page is taken from: <br>
● https://www.businessinsider.sg/feetures-socks-review/ <br>
● https://www.parnellsports.com/shashi <br>

The photos from the About Page is taken from a stock image library called <a href="https://www.pexels.com/">Pexels.</a> <br>

The About Us, Terms and Condition, FAQ, Return and Refunds and Privacy Policy are taken from <a href="https://www.happysocks.com/us/">Happy Socks.</a> <br>
The products details and images are also taken from <a href="https://www.happysocks.com/us/">Happy Socks.</a>


The problems are resolved with reference to similar problems faced by other programmer in <a href="https://stackoverflow.com/">Stackoverflow</a> as well as advice from lecturers.

The styling and features were made with reference to the tutorial from <a href="https://www.w3schools.com/">W3schools.</a>

The Styling of the webpage is cutomised from <a href="https://colorlib.com/wp/template/dealers/">Colorlib template.</a>

### Special Thanks to:

**Code Institute**
- The Html Fundamentals module, CSS Fundamentals module, Python Fundamentals module,Practical Python module and the Fullstack Frameworks module were used for guidance.

**Our Lecturer, Mr Paul Chor and Teaching Assistant, John**

- For all  the Guidance and Help during lesson and tackling project issue.