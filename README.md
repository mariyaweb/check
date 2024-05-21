https://ecommerceseenpie.netlify.app/main 
Total: 180/315

### 5.1. Login Page Implementation (100 / 130)

 5.1.1. Input Validation (40 / 40) 
 - [x] Implement client-side validation for the login form, including email and password fields. RSS-ECOMM-2_01 (20 / 20)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email. RSS-ECOMM-2_02 (20 / 20)

5.1.2. Integration with Authentication Service (45 / 45)
 - [x] Integrate the login form with a chosen authentication service (CommerceTools) to handle user authentication. RSS-ECOMM-2_03 (25 / 25)
 - [x] Implement error handling for failed authentication attempts, such as incorrect email or password, and display user-friendly error messages. RSS-ECOMM-2_04 (0 / 20)

5.1.3. Redirection (0 / 30)
 - [ ] Redirect users to the application's main page upon successful login. RSS-ECOMM-2_05 (0 / 15)
 - [ ] Redirect users who are already logged in to the main page if they try to access the login page. RSS-ECOMM-2_06 (0 / 15)

5.1.4. Handle Authentication Token (10 / 10)
 - [x] Obtain the authentication token securely after a successful login attempt by sending a request to the token endpoint, allowing for seamless user authentication across the application. RSS-ECOMM-2_07 (10 / 10)

5.1.5. Navigation to Registration Page (5 / 5)
 - [x] Add a button or link on the login page that allows users to navigate to the registration page. RSS-ECOMM-2_08 (5 / 5)


### 5.2. Registration Page Implementation (75 / 120)

5.2.1. Input Validation (45 / 45)
 - [x] Implement client-side validation for all required fields in the registration form, such as email, password, first name, last name, date of birth, and address fields (e.g., street, city, postal code, and country) for proper use with CommerceTools. RSS-ECOMM-2_09 (25 / 25)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email or a weak password. RSS-ECOMM-2_10 (20 / 20)
       
5.2.2. Integration with Authentication Service (25 / 25)
 - [x] Integrate the registration form with a chosen authentication service, such as commercetools, to handle user registration. RSS-ECOMM-2_11 (10 / 10)
 - [x] Implement error handling for failed registration attempts, and display user-friendly error messages. RSS-ECOMM-2_12 (15 / 15)

5.2.3. State Management, Automatic Login, and Redirection (0 / 15)
 - [ ] Redirect users to the application's main page upon successful account creation and automatic login. RSS-ECOMM-2_13 (0 / 15)

5.2.4. Integration with commercetools for User Profiles and Addresses (0 / 30)
 - [ ] Allow users to set a default address during registration. RSS-ECOMM-2_14 (0 / 15)
 - [ ] Enable users to select different billing and shipping addresses or choose a single address for both billing and shipping during the registration process. RSS-ECOMM-2_15 (0 / 15)

5.2.5. Navigation to Login Page (5 / 5)
 - [x] Add a button or link on the registration page that allows users to navigate to the login page. RSS-ECOMM-2_16 (5 / 5)

### 5.3. Main Page Enhancements (0 / 10)

5.3.1. Centralized Navigation (0 / 10)
 - [ ] Add links to all the functional pages of the application on the main page. These should include, but are not limited to, the login and registration pages. RSS-ECOMM-2_17 (0 / 5)
 - [ ] Each link should redirect the user correctly to the corresponding page without any errors. RSS-ECOMM-2_18 (0 / 5)

### 5.4 Routing Implementation (0 / 30)
 - [ ] Implement routing for navigation between login, registration, and main pages. RSS-ECOMM-2_19 (0 / 15)
 - [ ] Implement a 404 (Not Found) page for invalid route requests. RSS-ECOMM-2_20 (0 / 15)

### 5.5 Evaluation Criteria for Header (5 / 25)
 - [ ] Navigation to login and registration pages for unauthorized users RSS-ECOMM-2_21 (0 / 15)
 - [x] Ability to access the main page for all users RSS-ECOMM-2_22 (5 / 5)
 - [ ] Logout functionality for authorized users RSS-ECOMM-2_23 (0 / 5)

__________________________________________________
@anne.dyakova#8749
https://664b9b6f56a6510a6b08f910--earnest-gingersnap-44ebbe.netlify.app/main
Total: 315/315

### 5.1. Login Page Implementation (130/ 130)

 5.1.1. Input Validation (40 / 40) 
 - [x] Implement client-side validation for the login form, including email and password fields. RSS-ECOMM-2_01 (0 / 20)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email. RSS-ECOMM-2_02 (0 / 20)

5.1.2. Integration with Authentication Service (0 / 45)
 - [x] Integrate the login form with a chosen authentication service (CommerceTools) to handle user authentication. RSS-ECOMM-2_03 (25 / 25)
 - [x] Implement error handling for failed authentication attempts, such as incorrect email or password, and display user-friendly error messages. RSS-ECOMM-2_04 (0 / 20)

5.1.3. Redirection (30 / 30)
 - [x] Redirect users to the application's main page upon successful login. RSS-ECOMM-2_05 (0 / 15)
 - [x] Redirect users who are already logged in to the main page if they try to access the login page. RSS-ECOMM-2_06 (0 / 15)

5.1.4. Handle Authentication Token (5 / 10)
 - [x] Obtain the authentication token securely after a successful login attempt by sending a request to the token endpoint, allowing for seamless user authentication across the application. RSS-ECOMM-2_07 (10 / 10)

5.1.5. Navigation to Registration Page (5 / 5)
 - [+/-] Add a button or link on the login page that allows users to navigate to the registration page. RSS-ECOMM-2_08 (5 / 5)


### 5.2. Registration Page Implementation (120 / 120)

5.2.1. Input Validation (45 / 45)
 - [x] Implement client-side validation for all required fields in the registration form, such as email, password, first name, last name, date of birth, and address fields (e.g., street, city, postal code, and country) for proper use with CommerceTools. RSS-ECOMM-2_09 (25 / 25)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email or a weak password. RSS-ECOMM-2_10 (20 / 20)
       
5.2.2. Integration with Authentication Service (25 / 25)
 - [x] Integrate the registration form with a chosen authentication service, such as commercetools, to handle user registration. RSS-ECOMM-2_11 (10 / 10)
 - [x] Implement error handling for failed registration attempts, and display user-friendly error messages. RSS-ECOMM-2_12 (15 / 15)

5.2.3. State Management, Automatic Login, and Redirection (15 / 15)
 - [x] Redirect users to the application's main page upon successful account creation and automatic login. RSS-ECOMM-2_13 (0 / 15)

5.2.4. Integration with commercetools for User Profiles and Addresses (30 / 30)
 - [x] Allow users to set a default address during registration. RSS-ECOMM-2_14 (0 / 15)
 - [x] Enable users to select different billing and shipping addresses or choose a single address for both billing and shipping during the registration process. RSS-ECOMM-2_15 (0 / 15)

5.2.5. Navigation to Login Page (5 / 5)
 - [+/-] Add a button or link on the registration page that allows users to navigate to the login page. RSS-ECOMM-2_16 (5 / 5)

### 5.3. Main Page Enhancements (10 / 10)

5.3.1. Centralized Navigation (10 / 10)
 - [+/-] Add links to all the functional pages of the application on the main page. These should include, but are not limited to, the login and registration pages. RSS-ECOMM-2_17 (0 / 5)
 - [x] Each link should redirect the user correctly to the corresponding page without any errors. RSS-ECOMM-2_18 (5 / 5)

### 5.4 Routing Implementation (30 / 30)
 - [x] Implement routing for navigation between login, registration, and main pages. RSS-ECOMM-2_19 (15 / 15)
 - [ +/- ] Implement a 404 (Not Found) page for invalid route requests. RSS-ECOMM-2_20 (15 / 15)

### 5.5 Evaluation Criteria for Header (25 / 25)
 - [x] Navigation to login and registration pages for unauthorized users RSS-ECOMM-2_21 (15 / 15)
 - [x] Ability to access the main page for all users RSS-ECOMM-2_22 (5 / 5)
 - [x] Logout functionality for authorized users RSS-ECOMM-2_23 (5 / 5)
__________________________________________________
 @Andrei Chekhanadski#5138
https://ecommerce-sprint2.netlify.app/
Total: 287/315

### 5.1. Login Page Implementation (130/ 130)

 5.1.1. Input Validation (40 / 40) 
 - [x] Implement client-side validation for the login form, including email and password fields. RSS-ECOMM-2_01 (20 / 20)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email. RSS-ECOMM-2_02 (20 / 20)

5.1.2. Integration with Authentication Service (45 / 45)
 - [x] Integrate the login form with a chosen authentication service (CommerceTools) to handle user authentication. RSS-ECOMM-2_03 (25 / 25)
 - [x] Implement error handling for failed authentication attempts, such as incorrect email or password, and display user-friendly error messages. RSS-ECOMM-2_04 (20 / 20)

5.1.3. Redirection (15 / 30)
 - [x] Redirect users to the application's main page upon successful login. RSS-ECOMM-2_05 (15 / 15)
 - [ ] Redirect users who are already logged in to the main page if they try to access the login page. RSS-ECOMM-2_06 (0 / 15)
       - функцонал не реализован

5.1.4. Handle Authentication Token (10 / 10)
 - [x] Obtain the authentication token securely after a successful login attempt by sending a request to the token endpoint, allowing for seamless user authentication across the application. RSS-ECOMM-2_07 (10 / 10)

5.1.5. Navigation to Registration Page (5 / 5)
 - [x] Add a button or link on the login page that allows users to navigate to the registration page. RSS-ECOMM-2_08 (5 / 5)


### 5.2. Registration Page Implementation (105 / 120)

5.2.1. Input Validation (45 / 45)
 - [x] Implement client-side validation for all required fields in the registration form, such as email, password, first name, last name, date of birth, and address fields (e.g., street, city, postal code, and country) for proper use with CommerceTools. RSS-ECOMM-2_09 (25 / 25)
 - [x] Display clear error messages indicating any validation issues, such as an improperly formatted email or a weak password. RSS-ECOMM-2_10 (20 / 20)
       
5.2.2. Integration with Authentication Service (25 / 25)
 - [x] Integrate the registration form with a chosen authentication service, such as commercetools, to handle user registration. RSS-ECOMM-2_11 (10 / 10)
 - [x] Implement error handling for failed registration attempts, and display user-friendly error messages. RSS-ECOMM-2_12 (15 / 15)

5.2.3. State Management, Automatic Login, and Redirection (0 / 15)
 - [ ] Redirect users to the application's main page upon successful account creation and automatic login. RSS-ECOMM-2_13 (0 / 15)

5.2.4. Integration with commercetools for User Profiles and Addresses (30 / 30)
 - [x] Allow users to set a default address during registration. RSS-ECOMM-2_14 (15 / 15)
 - [x] Enable users to select different billing and shipping addresses or choose a single address for both billing and shipping during the registration process. RSS-ECOMM-2_15 (15 / 15)

5.2.5. Navigation to Login Page (5 / 5)
 - [x] Add a button or link on the registration page that allows users to navigate to the login page. RSS-ECOMM-2_16 (5 / 5)

### 5.3. Main Page Enhancements (7 / 10)

5.3.1. Centralized Navigation (7 / 10)
 - [+/-] Add links to all the functional pages of the application on the main page. These should include, but are not limited to, the login and registration pages. RSS-ECOMM-2_17 (3 / 5)
   -нет функциональных страниц: корзина, каталог, о нас
 - [+/-] Each link should redirect the user correctly to the corresponding page without any errors. RSS-ECOMM-2_18 (4 / 5)
   - при переходе по ссылкам на главной странице появляется страница 404

### 5.4 Routing Implementation (30 / 30)
 - [x] Implement routing for navigation between login, registration, and main pages. RSS-ECOMM-2_19 (15 / 15)
       в целом роутинг реализован верно, но обратите внимание на ссылки главной страницы Woman’s Fashion, Men’s Fashion, Electronics - они вызывают перезагрузку страницы, а должны работать как SPA
 - [x] Implement a 404 (Not Found) page for invalid route requests. RSS-ECOMM-2_20 (15 / 15)

### 5.5 Evaluation Criteria for Header (0 / 25)
 - [x] Navigation to login and registration pages for unauthorized users RSS-ECOMM-2_21 (15 / 15)
 - [x] Ability to access the main page for all users RSS-ECOMM-2_22 (5 / 5)
 - [ ] Logout functionality for authorized users RSS-ECOMM-2_23 (0 / 5)
