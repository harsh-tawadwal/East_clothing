Project Overview:
This project is a fully functional e-commerce website developed using the MERN (MongoDB, Express, React, Node.js) stack. The application provides a seamless user experience for browsing products, adding items to the shopping cart, and completing orders with payment integration. It is designed to be highly scalable, secure, and user-friendly.

Key Features:
1. Product Browsing & Filtering:
   - Users can view a wide range of products, including images, descriptions, prices, and stock availability.
   - The product listing can be filtered by categories, price range, and ratings.
   
2. User Authentication:
   - Secure user authentication and authorization implemented using JWT (JSON Web Tokens).
   - Users can register, log in, and manage their profiles.
   
3. Shopping Cart:
   - Users can add products to their cart, modify quantities, and remove items.
   - The cart persists between sessions, ensuring users don’t lose their progress.

4. Order Management:
   - Users can place orders, view their order history, and track the status of current orders.
   - Administrators have the ability to manage product inventory, view customer orders, and update the order statuses.

5. Payment Gateway Integration:
   - Secure and reliable payment gateway integration (e.g., Stripe or PayPal).
   - Users can pay for their orders using credit cards, debit cards, or other supported payment methods.
   - After successful payment, users receive confirmation emails, and the order is marked as completed in the database.

6. Product Reviews & Ratings:
   - Customers can leave reviews and rate products, helping future customers make informed purchase decisions.

7. Responsive Design:
   - The application is designed to be fully responsive, providing an optimal experience across desktops, tablets, and smartphones.

8. Admin Dashboard:
   - An admin panel is provided to manage products, orders, and users.
   - Admins can add, update, or remove products and monitor sales performance.

Technologies Used:
- Frontend: React.js, Redux for state management, React Router for navigation, Bootstrap/Material UI for styling.
- Backend: Node.js with Express.js for handling server-side logic and RESTful APIs.
- Database: MongoDB for storing product, user, and order information.
- Authentication: JWT (JSON Web Tokens) for secure user authentication and session management.
- Payment Gateway :PayPal API for handling payments.
- Deployment: The website is deployed on cloud platforms like AWS/Heroku, with proper CI/CD pipelines set up for continuous integration and delivery.
