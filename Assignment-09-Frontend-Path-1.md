# **Electronic Gadgets Shop Project Overview**

## **Disclaimer:**

> "In continuation of your previous assignment, we are excited to expand upon the existing project by introducing additional features and enhancing the user interface and experience(UI/UX). This extension seeks to enrich the platform, fostering deeper engagement within the community and offering improved functionality for users.”
> 

### **Project Overview:**

The Electronic Gadgets Marketplace project aims to enhance user engagement and functionality within the electronic gadgets domain by incorporating essential features and UI/UX improvements. By leveraging modern technologies and design principles, the platform will offer a seamless and immersive shopping experience, enabling users to browse, purchase, and review electronic gadgets with ease and confidence.

# **Key Features Breakdown:**

In this project, you will implement the following key features and UI/UX enhancements tailored specifically for an electronic gadgets marketplace:

1. **UI/UX Enhancements:**
    - Enhance the user interface with visually appealing components, intuitive navigation elements, and responsive design tailored to electronic gadgets enthusiasts' preferences, ensuring seamless browsing and exploration within the marketplace.
    - You must need to improve your UI/UX from the previous one. There will be 10 Marks allocated for your UI/UX polishing & improvements.
2. **Error Handling:**
    - Implement error handling features of Next.JS to provide informative error messages and graceful fallbacks, ensuring a robust user experience even in the event of unexpected errors.
3. **SEO:**
    - Implement `static` and `dynamic meta tags` to optimize search engine visibility and improve organic discoverability of pages, products, and product details within the electronic gadgets marketplace.
    - You can show the Route names in the browser tab and dynamically show the specific product name in the browser tab
    - You can explore more about Next JS Meta Data from here:
    https://nextjs.org/docs/app/building-your-application/optimizing/metadata
4. **Redux Persist:**
    - Utilize redux persist to persist `user cart data` across sessions, ensuring a seamless shopping experience even after reloading the page or revisiting the platform.
5. **Navbar Enhancements:**
    - Introduce new options on the navigation bar, including
        - `Login/Register Button`
        - `Logout Button`
        - `Cart Icon`
        
        to enhance user accessibility and streamline navigation within the electronic gadgets marketplace.
        

# **Pages:**

### **Login / Register Page:**

- **Register Page (*”/register”*):**
    - Create a user-friendly registration page allowing users to create an account with essential information such as User Name, Email, and Password.
- **Login Page (*”/login”*):**
    - Develop a secure login page enabling users to access their accounts with email and password credentials.

`You will be provided with the backend code of the authentication & authorization. You can use that or make your own backend for authentication & authorization. Optionally you can provide access token and refresh token based login/register system.`

### **Dashboard Page:**

- **`Dashboard Routes For Admin Role:`**
    - **Products Table Route (*"/dashboard/products"*):**
        - Provide a table view of all electronic gadgets with action buttons like *`"Edit" / "Delete"`* for each product row, facilitating efficient product management for administrators.
    - **Add Product Route (*"/dashboard/products/add-product"*):**
        - Enable administrators to add electronic gadgets through a dedicated route, ensuring seamless integration of new products into the platform.
    - **Orders Management Route (*"/dashboard/orders"*):**
        - Handle order status transitions from `Pending to Delivered`, empowering administrators to manage orders effectively within the electronic gadgets marketplace.
- **`Dashboard Routes For User Role:`**
    - **My Orders Route (*"/dashboard/my-orders"*):**
        - Allow users to view their own `delivered` and `pending` orders, providing transparency and control over their shopping experience.
        - Users can provide ratings for the `delivered products` once

### **Product Page:**

- **Product Page (*"/mobile" / "/fridge" / "/tv" etc.*):**
    - Each product card will have an **`Add To Cart Button`**
    - Clicking the **`Add To Cart Button`**  will add the product in the Cart
    - There will be a **`Cart Icon` in the NavBar** which will have a badge showing the number of unique products added in the cart
    - Use **Redux And Redux Persist** to persist the cart after reloading the page
        
        

### **Product Detail Page:**

- **Product Detail Page (*"/mobile/123" / "/fridge/456" / "/tv/789" etc.*):**
    - There will be an `Add To Cart Button` in The Product Detail page also
    - Clicking the **`add to cart button`** will add the product to the Cart
    - There will be a **`Cart Icon` in the NavBar** which will have a badge showing the number of unique products added to the cart
    - User **`Redux And Redux Persist`** to persist the cart after reloading the page
    - Any Authorized User can provide a `review` for the product on the product detail page below the details of the product. It is not necessary to buy the product or having it delivered.
    - Optionally you can use `Server Actions` to POST a review for a Product
    - The Reviews will be shown below the product details in the product detail page

### **Checkout Page:**

- **Checkout Page (*"/checkout"*):**
    - The added product in the cart will be shown on the checkout page
    - Use `Redux Persist` in the cart on the checkout page and the Cart Icon in NavBar
    - Show Each added Product with the quantity
    - Show Payment Method Options:
        - Keep only one option `“Cash On Delivery”`. You can keep it pre-selected.
    - Calculate the Total price with product Quantity and Delivery Charge of 15 Taka
    - Show the `“Proceed Checkout” Button` below the Total Price
    - Clicking the the `Proceed Checkout Button` will create an order with pending status
    - After the Order is created, show a `Toast` and `Clear the Cart`
    - Only Admin will be able to change the Order status from `Pending to Delivered` in the `Admin Dashboard Panel`

# **Optional Tasks:**

- **Dark & Light Mode**
    - Use `Next Themes Package` to Implement Light Mode and Dark Mode
    - You can explore the Next Themes Package from here:
    https://www.npmjs.com/package/next-themes
- **Server Actions**
    - Use `Server Actions to POST` Review for a Product inside Product Detail Page

### **Submission Guidelines:**

Include comprehensive README files in both frontend and backend repositories, along with clear instructions for setting up and using the application tailored specifically for the E-commerce Platform project. Provide private GitHub repository links for evaluation and submit a live deployment link for the frontend application to facilitate assessment.

### **Deadline:**

- 60 marks: April 21, 2024 11.59 PM
- No 50 & 30 Marks Deadline

### **Important Note:**

Plagiarism will not be tolerated. Ensure that the code you submit is your own work, tailored specifically for the Electronic Gadgets Shop project. Any instances of plagiarism will result in 0 marks.

We wish you success with your assignment! Should you have any questions or require clarification, feel free to reach out for assistance.