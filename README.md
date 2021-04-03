# EasySell

This is EasySell, it's a free, web-based point-of-sale system.

# Features
1. A RESTful API, built with Express and NodeJS, which is used to access user management, transaction, transaction logging and inventory management functions.
2. Inventory management using a MongoDB database, which stores products, inventory, and prices.
3. Transaction logging, storing items purchased, total transaction revenue, and transaction time, used for analytics.
4. Performance analytics, delivering daily and weekly sales volume and percent change in sales volume.
5. User management to seperate transaction data and inventory by user.
6. Route security with Passport-JWT, preventing unauthorized access to transaction and inventory data.
7. A responsive front-end designed with React, Bootstrap and ChartJS to perform transactions, manage inventory and view performance statistics.

# Deployment and Use
To deploy on your own machine, you will require a MongoDB Atlas Cluster, which you can create for free. Set environment variables PORT, MONGO_URI and PRIVATE_KEY for password hashing, and off you go!
# Front-end
1. React.js
2. Bootstrap
3. Axios

# Back-end
1. Express.js
2. cors
3. jwt
4. mongoDB
5. passport

# Showcase
![Alt text](/images/1.png?raw=true "Title")
![Alt text](/images/2.png?raw=true "Title")
![Alt text](/images/3.png?raw=true "Title")
![Alt text](/images/4.png?raw=true "Title")
![Alt text](/images/5.png?raw=true "Title")
![Alt text](/images/6.png?raw=true "Title")
