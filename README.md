# Co-Coffee



This repository contains a complete coffee ordering system featuring both a front-end and back-end. The front-end is built using React, Next.js, TypeScript, TailwindCSS, Zustand, and Ant Design (antd) component library. The back-end is developed using Nest.js with MongoDB as the database.

1. **Login Page**: Allows users to log into the system.

   ![loginPage](C:\Users\Sinzo\Desktop\researh\loginPage.png)

2. **Registration Page**: Enables users to create a new account.

   ![registerPage](C:\Users\Sinzo\Desktop\researh\registerPage.png)

3. **Home Page**: Users can browse, purchase coffee, or add items to their cart.

   ![HomePage](C:\Users\Sinzo\Desktop\researh\HomePage.png)

4. **Cart Page**: Users can view and modify the quantity of items in their cart and calculate the total price.

   ![shoppingCart](C:\Users\Sinzo\Desktop\researh\shoppingCart.png)

5. **Orders Page**: Users can view both ongoing and completed orders.

   ![makingCoffee](C:\Users\Sinzo\Desktop\researh\makingCoffee.png)

   ![finishedOrder](C:\Users\Sinzo\Desktop\researh\finishedOrder.png)

6. **User Profile Page**: Users can view their profile information, check their balance, and recharge their account.

   ![userPage](C:\Users\Sinzo\Desktop\researh\userPage.png)



#### Back-end



- **Nest.js**: Provides a robust and scalable back-end framework.
- **MongoDB**: Utilized for data storage with four collections: `carts`, `coffee`, `orders`, and `users`.



#### Collections

1. **carts**: Stores cart details for each user, including items and quantities.

   ![carts](C:\Users\Sinzo\Desktop\researh\carts.png)

2. **coffee**: Contains information about available coffee products.

   ![coffee](C:\Users\Sinzo\Desktop\researh\coffee.png)

3. **orders**: Tracks user orders, including status and history.

   ![orders](C:\Users\Sinzo\Desktop\researh\orders.png)

4. **users**: Maintains user information and balance details.

   ![users](C:\Users\Sinzo\Desktop\researh\users.png)



### Getting Started

To get started with the project, clone the repository and follow the instructions for setting up both the front-end and back-end environments.



### Front-end Setup

1. Navigate to the `frontend` directory.
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`



### Back-end Setup

1. Navigate to the `backend` directory.
2. Install dependencies: `npm install`
3. Start the server: `npm run start`



### Database Setup

Ensure MongoDB is installed and running. Create the necessary collections: `carts`, `coffee`, `orders`, and `users`.



### Contributions

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request for review.



### License

This project is licensed under the MIT License.
