[https://ecommerceseenpie.netlify.app/main ](https://harajuku-hub-sprint-3.netlify.app/#/)
Есть небольшой баг при регистрации нового пользователя автоматически перенаправляет в ранее открытый аккаунт, вместо нового. Перед этим в ранее открытом аккаунте осуществлялись изменения данных пользователя.
Total: 320/370

### 5.1. Catalog Page Implementation (130 / 150)

 5.1.1. Display Product List (45 / 45)     
- [x] Use the commercetools API to fetch a list of products with essential details, such as name, image, and description. RSS-ECOMM-3_01 (25 / 25)
- [x] Display prices with and without discount for discounted products, ensuring that the discounted price is visually distinct and clearly indicates that it is the current price. RSS-ECOMM-3_02 (20 / 20)
  
 5.1.2. Product Filtering, Sorting, and Searching (45 / 65)
- [x] Utilize the commercetools API to offer robust filtering options for users to refine the product list based on attributes such as price range, brand, color, size, or other relevant characteristics. RSS-ECOMM-3_03 (30 / 30)
- [x] Enable users to sort the product list by various properties, such as price and name. RSS-ECOMM-3_04 (15 / 15)
- [ ] Implement an efficient and user-friendly search feature that allows users to quickly find and display relevant products based on their search query using the chosen API. RSS-ECOMM-3_05 (0 / 20)
  
 5.1.3. Interactive Product Cards (15 / 15)
- [x] Design product cards that change their appearance when the user hovers over them, enhancing the browsing experience. RSS-ECOMM-3_06 (10 / 10)
- [x] Upon clicking a product card, redirect the user to a detailed product information page for the selected product. RSS-ECOMM-3_07 (5 / 5)
  
 5.1.4. Category Navigation (25 / 25)
- [x] Implement easy-to-use and clear navigation options for users to explore and switch between different product categories or subcategories using the commercetools API. RSS-ECOMM-3_08 (25 / 25)

### 5.2. Detailed Product Page Implementation (95 / 100)

5.2.1. Display Product Information (60 / 65)
- [x] Use the commercetools API to fetch and display the product name, description, and images on the Detailed Product page. RSS-ECOMM-3_09 (25 / 25)
- [+/-] Implement an image slider for product images fetched from the chosen API, allowing users to view multiple images of the product. RSS-ECOMM-3_10 (20 / 25)
Нет возмозможности проверить требование "If a product has only a single image, the slider gracefully degrades to simply display that image without any unnecessary slider controls." т.к. все товары имеют более 1 изображения.
- [x] Display the product price fetched from the chosen API, and if the product is on sale, display both the original and discounted prices. RSS-ECOMM-3_11 (15 / 15)
  
5.2.2. Enlarged Image Modal with Slider (35 / 35)
- [x] Allow users to click on the product image to open an enlarged version of the image in a modal window. RSS-ECOMM-3_12 (20 / 20)
- [x] Enable users to navigate through all product images from the commercetools API using a slider inside the modal window. RSS-ECOMM-3_13 (15 / 15)

### 5.3. User Profile Page Implementation (65 / 70)

5.3.1. Display User Profile Information (30 / 30)
- [x] Present the user's personal information, including first name, last name, date of birth, and a list of their addresses in the User Profile page. RSS-ECOMM-3_14 (10 / 10)
- [x] Provide a user-friendly interface for users to switch to an edit mode, where they can update their personal details, email, and addresses. RSS-ECOMM-3_15 (20 / 20)
  
5.3.2. Edit User Profile Information (35 / 40)
- [x] In the edit mode, allow users to update their personal information, including first name, last name, and date of birth and email. RSS-ECOMM-3_16 (10 / 10)
- [x] Enable users to change their password. RSS-ECOMM-3_17 (15 / 15)
- [+/-] Allow users to manage their addresses, including adding new addresses, deleting existing ones, and updating address details. RSS-ECOMM-3_18 (10 / 15) - не реализовано удаление адресов

### 5.4. Routing Implementation (40 / 40)
- [x] Implement routing for navigation between Catalog page, Product detail page. RSS-ECOMM-3_19 (25 / 25)
- [x] Implement routing for navigation to User Profile page. RSS-ECOMM-3_20 (15 / 15)

### 5.5. Evaluation Criteria for Header (10 / 10)
- [x] Consistent header layout with necessary information like branding and user navigation across all the pages. RSS-ECOMM-3_21 (5 / 5)
- [x] User Profile link or button in the header, enabling navigation to User Profile page. RSS-ECOMM-3_22 (5 / 5)

### Penalties for Cross-Check Criteria
- [x] Absence of Responsive Application Design (-20 points)
_____________________________________________________________________________________________________________

https://ecommerceseenpie.netlify.app/main 
Total: 0/370

### 5.1. Catalog Page Implementation (0 / 150)

 5.1.1. Display Product List ( / 45)     
- [] Use the commercetools API to fetch a list of products with essential details, such as name, image, and description. RSS-ECOMM-3_01 (25 / 25)
- [] Display prices with and without discount for discounted products, ensuring that the discounted price is visually distinct and clearly indicates that it is the current price. RSS-ECOMM-3_02 (20 / 20)
  
 5.1.2. Product Filtering, Sorting, and Searching (65 / 65)
- [] Utilize the commercetools API to offer robust filtering options for users to refine the product list based on attributes such as price range, brand, color, size, or other relevant characteristics. RSS-ECOMM-3_03 (30 / 30)
- [] Enable users to sort the product list by various properties, such as price and name. RSS-ECOMM-3_04 (15 / 15)
- [] Implement an efficient and user-friendly search feature that allows users to quickly find and display relevant products based on their search query using the chosen API. RSS-ECOMM-3_05 (20 / 20)
  
 5.1.3. Interactive Product Cards (15 points)
- [] Design product cards that change their appearance when the user hovers over them, enhancing the browsing experience. RSS-ECOMM-3_06 (10 / 10)
- [] Upon clicking a product card, redirect the user to a detailed product information page for the selected product. RSS-ECOMM-3_07 (5 / 5)
  
 5.1.4. Category Navigation (25 points)
- [] Implement easy-to-use and clear navigation options for users to explore and switch between different product categories or subcategories using the commercetools API. RSS-ECOMM-3_08 (25 / 25)

### 5.2. Detailed Product Page Implementation ( / 100)

5.2.1. Display Product Information (65 / 65)
- [] Use the commercetools API to fetch and display the product name, description, and images on the Detailed Product page. RSS-ECOMM-3_09 (25 / 25)
- [] Implement an image slider for product images fetched from the chosen API, allowing users to view multiple images of the product. RSS-ECOMM-3_10 (25 / 25)
- [] Display the product price fetched from the chosen API, and if the product is on sale, display both the original and discounted prices. RSS-ECOMM-3_11 (15 / 15)
  
5.2.2. Enlarged Image Modal with Slider (35 / 35)
- [] Allow users to click on the product image to open an enlarged version of the image in a modal window. RSS-ECOMM-3_12 (20 / 20)
- [] Enable users to navigate through all product images from the commercetools API using a slider inside the modal window. RSS-ECOMM-3_13 (15 / 15)

### 5.3. User Profile Page Implementation ( / 70)

5.3.1. Display User Profile Information (30 / 30)
- [] Present the user's personal information, including first name, last name, date of birth, and a list of their addresses in the User Profile page. RSS-ECOMM-3_14 (10 / 10)
- [] Provide a user-friendly interface for users to switch to an edit mode, where they can update their personal details, email, and addresses. RSS-ECOMM-3_15 (20 / 20)
  
5.3.2. Edit User Profile Information (40 / 40)
- [] In the edit mode, allow users to update their personal information, including first name, last name, and date of birth and email. RSS-ECOMM-3_16 (10 / 10)
- [] Enable users to change their password. RSS-ECOMM-3_17 (15 / 15)
- [] Allow users to manage their addresses, including adding new addresses, deleting existing ones, and updating address details. RSS-ECOMM-3_18 (15 / 15)

### 5.4. Routing Implementation (40 / 40)
- [] Implement routing for navigation between Catalog page, Product detail page. RSS-ECOMM-3_19 (25 / 25)
- [] Implement routing for navigation to User Profile page. RSS-ECOMM-3_20 (15 / 15)

### 5.5. Evaluation Criteria for Header (10 / 10)
- [] Consistent header layout with necessary information like branding and user navigation across all the pages. RSS-ECOMM-3_21 (5 / 5)
- [] User Profile link or button in the header, enabling navigation to User Profile page. RSS-ECOMM-3_22 (5 / 5)
_____________________________________________________________________________________________________________

https://ecommerceseenpie.netlify.app/main 
Total: 0/370

### 5.1. Catalog Page Implementation (0 / 150)

 5.1.1. Display Product List ( / 45)     
- [] Use the commercetools API to fetch a list of products with essential details, such as name, image, and description. RSS-ECOMM-3_01 (25 / 25)
- [] Display prices with and without discount for discounted products, ensuring that the discounted price is visually distinct and clearly indicates that it is the current price. RSS-ECOMM-3_02 (20 / 20)
  
 5.1.2. Product Filtering, Sorting, and Searching (65 / 65)
- [] Utilize the commercetools API to offer robust filtering options for users to refine the product list based on attributes such as price range, brand, color, size, or other relevant characteristics. RSS-ECOMM-3_03 (30 / 30)
- [] Enable users to sort the product list by various properties, such as price and name. RSS-ECOMM-3_04 (15 / 15)
- [] Implement an efficient and user-friendly search feature that allows users to quickly find and display relevant products based on their search query using the chosen API. RSS-ECOMM-3_05 (20 / 20)
  
 5.1.3. Interactive Product Cards (15 points)
- [] Design product cards that change their appearance when the user hovers over them, enhancing the browsing experience. RSS-ECOMM-3_06 (10 / 10)
- [] Upon clicking a product card, redirect the user to a detailed product information page for the selected product. RSS-ECOMM-3_07 (5 / 5)
  
 5.1.4. Category Navigation (25 points)
- [] Implement easy-to-use and clear navigation options for users to explore and switch between different product categories or subcategories using the commercetools API. RSS-ECOMM-3_08 (25 / 25)

### 5.2. Detailed Product Page Implementation ( / 100)

5.2.1. Display Product Information (65 / 65)
- [] Use the commercetools API to fetch and display the product name, description, and images on the Detailed Product page. RSS-ECOMM-3_09 (25 / 25)
- [] Implement an image slider for product images fetched from the chosen API, allowing users to view multiple images of the product. RSS-ECOMM-3_10 (25 / 25)
- [] Display the product price fetched from the chosen API, and if the product is on sale, display both the original and discounted prices. RSS-ECOMM-3_11 (15 / 15)
  
5.2.2. Enlarged Image Modal with Slider (35 / 35)
- [] Allow users to click on the product image to open an enlarged version of the image in a modal window. RSS-ECOMM-3_12 (20 / 20)
- [] Enable users to navigate through all product images from the commercetools API using a slider inside the modal window. RSS-ECOMM-3_13 (15 / 15)

### 5.3. User Profile Page Implementation ( / 70)

5.3.1. Display User Profile Information (30 / 30)
- [] Present the user's personal information, including first name, last name, date of birth, and a list of their addresses in the User Profile page. RSS-ECOMM-3_14 (10 / 10)
- [] Provide a user-friendly interface for users to switch to an edit mode, where they can update their personal details, email, and addresses. RSS-ECOMM-3_15 (20 / 20)
  
5.3.2. Edit User Profile Information (40 / 40)
- [] In the edit mode, allow users to update their personal information, including first name, last name, and date of birth and email. RSS-ECOMM-3_16 (10 / 10)
- [] Enable users to change their password. RSS-ECOMM-3_17 (15 / 15)
- [] Allow users to manage their addresses, including adding new addresses, deleting existing ones, and updating address details. RSS-ECOMM-3_18 (15 / 15)

### 5.4. Routing Implementation (40 / 40)
- [] Implement routing for navigation between Catalog page, Product detail page. RSS-ECOMM-3_19 (25 / 25)
- [] Implement routing for navigation to User Profile page. RSS-ECOMM-3_20 (15 / 15)

### 5.5. Evaluation Criteria for Header (10 / 10)
- [] Consistent header layout with necessary information like branding and user navigation across all the pages. RSS-ECOMM-3_21 (5 / 5)
- [] User Profile link or button in the header, enabling navigation to User Profile page. RSS-ECOMM-3_22 (5 / 5)
_____________________________________________________________________________________________________________

https://ecommerceseenpie.netlify.app/main 
Total: 0/370

### 5.1. Catalog Page Implementation (0 / 150)

 5.1.1. Display Product List ( / 45)     
- [] Use the commercetools API to fetch a list of products with essential details, such as name, image, and description. RSS-ECOMM-3_01 (25 / 25)
- [] Display prices with and without discount for discounted products, ensuring that the discounted price is visually distinct and clearly indicates that it is the current price. RSS-ECOMM-3_02 (20 / 20)
  
 5.1.2. Product Filtering, Sorting, and Searching (65 / 65)
- [] Utilize the commercetools API to offer robust filtering options for users to refine the product list based on attributes such as price range, brand, color, size, or other relevant characteristics. RSS-ECOMM-3_03 (30 / 30)
- [] Enable users to sort the product list by various properties, such as price and name. RSS-ECOMM-3_04 (15 / 15)
- [] Implement an efficient and user-friendly search feature that allows users to quickly find and display relevant products based on their search query using the chosen API. RSS-ECOMM-3_05 (20 / 20)
  
 5.1.3. Interactive Product Cards (15 points)
- [] Design product cards that change their appearance when the user hovers over them, enhancing the browsing experience. RSS-ECOMM-3_06 (10 / 10)
- [] Upon clicking a product card, redirect the user to a detailed product information page for the selected product. RSS-ECOMM-3_07 (5 / 5)
  
 5.1.4. Category Navigation (25 points)
- [] Implement easy-to-use and clear navigation options for users to explore and switch between different product categories or subcategories using the commercetools API. RSS-ECOMM-3_08 (25 / 25)

### 5.2. Detailed Product Page Implementation ( / 100)

5.2.1. Display Product Information (65 / 65)
- [] Use the commercetools API to fetch and display the product name, description, and images on the Detailed Product page. RSS-ECOMM-3_09 (25 / 25)
- [] Implement an image slider for product images fetched from the chosen API, allowing users to view multiple images of the product. RSS-ECOMM-3_10 (25 / 25)
- [] Display the product price fetched from the chosen API, and if the product is on sale, display both the original and discounted prices. RSS-ECOMM-3_11 (15 / 15)
  
5.2.2. Enlarged Image Modal with Slider (35 / 35)
- [] Allow users to click on the product image to open an enlarged version of the image in a modal window. RSS-ECOMM-3_12 (20 / 20)
- [] Enable users to navigate through all product images from the commercetools API using a slider inside the modal window. RSS-ECOMM-3_13 (15 / 15)

### 5.3. User Profile Page Implementation ( / 70)

5.3.1. Display User Profile Information (30 / 30)
- [] Present the user's personal information, including first name, last name, date of birth, and a list of their addresses in the User Profile page. RSS-ECOMM-3_14 (10 / 10)
- [] Provide a user-friendly interface for users to switch to an edit mode, where they can update their personal details, email, and addresses. RSS-ECOMM-3_15 (20 / 20)
  
5.3.2. Edit User Profile Information (40 / 40)
- [] In the edit mode, allow users to update their personal information, including first name, last name, and date of birth and email. RSS-ECOMM-3_16 (10 / 10)
- [] Enable users to change their password. RSS-ECOMM-3_17 (15 / 15)
- [] Allow users to manage their addresses, including adding new addresses, deleting existing ones, and updating address details. RSS-ECOMM-3_18 (15 / 15)

### 5.4. Routing Implementation (40 / 40)
- [] Implement routing for navigation between Catalog page, Product detail page. RSS-ECOMM-3_19 (25 / 25)
- [] Implement routing for navigation to User Profile page. RSS-ECOMM-3_20 (15 / 15)

### 5.5. Evaluation Criteria for Header (10 / 10)
- [] Consistent header layout with necessary information like branding and user navigation across all the pages. RSS-ECOMM-3_21 (5 / 5)
- [] User Profile link or button in the header, enabling navigation to User Profile page. RSS-ECOMM-3_22 (5 / 5)
_____________________________________________________________________________________________________________

