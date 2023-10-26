# Pallet: React and Mongo Single Page Application
Pallet is a React, Node, and Mongo DB single-page application created to store and share color pallets. 
The purpose of Pallet is to demonstrate the ability to create a full-stack web application with the following features: 
Authentication utilizing passport.js, utilization of a document-based database, showcasing a grasp of responsive web design, 
validation, and parameter-based searching. 

The React front-end utilizes asynchronous web calls, user authentication JSON tokens, state management with react context, 
newer hooks in the React life cycle such as useState/useMemo, Bootstrap for handling responsive design, and several interface 
elements that automatically update when changing such as the color displayed. 

The Node.js backend utilizes MongoDB, Express.js, Bcrypt.js, and Passport.js. The service is set up in an MVC pattern and has certain 
Rest API functions guarded by authentication middleware. Routing is laid out logically to the pattern of the data resources accessed 
in the front end. For example, routes are designated to work with user and color palette data separately. The database and server 
are set up to associate pallets by the user that created them to allow personal customization of each color pallet. 

Screen that the User First Encounters:
![palette1](https://github.com/nseamanssanantonio/PalletReactandMongoApplication/assets/109008197/844bd274-1bbe-49ff-8874-c9421d1f98c0)
Demo of utilizing the Palete Search Function:
![palette2](https://github.com/nseamanssanantonio/PalletReactandMongoApplication/assets/109008197/9cbf72e0-a2fb-46c8-9add-6c46542dd887)
Color Scheme Creation Page
![palette3](https://github.com/nseamanssanantonio/PalletReactandMongoApplication/assets/109008197/fcefc386-c940-44e2-b476-73bd1c26242f)
Page showing the ability to edit a color scheme:
![palette4](https://github.com/nseamanssanantonio/PalletReactandMongoApplication/assets/109008197/17245cc2-d86e-4217-9ebf-21fbbda1ed06)
