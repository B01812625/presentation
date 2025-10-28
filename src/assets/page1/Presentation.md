##  Presentation



![Slide1](/presentation/src/assets/page1/images/Slide1.PNG)
Theme: Understanding GraphQL Core Concepts

· Introduction to GraphQL, its key features, advantages, and a comparison with REST.

![Slide2](/presentation/src/assets/page1/images/Slide2.PNG)
 Part 1: GraphQL Fundamentals

· This section covers the core concepts and architecture of GraphQL.




![Slide3](/presentation/src/assets/page1/images/Slide3.PNG)


 GraphQL is a query language for APIs, open-sourced by Facebook. It allows clients to request exactly the data they need.



![Slide4](/presentation/src/assets/page1/images/Slide4.PNG)

 Efficient and flexible data interaction through a single endpoint and a strongly typed system. Supports real-time subscriptions.


![Slide5](/presentation/src/assets/page1/images/Slide5.PNG)

Reduces round-trip requests, improves front-end efficiency, and is ideal for modern web applications.


![Slide6](/presentation/src/assets/page1/images/Slide6.PNG)
 GraphQL vs REST: Limitations of REST

· REST uses multiple endpoints, often leading to data redundancy, over-fetching, and complex version management.


![Slide7](/presentation/src/assets/page1/images/Slide7.PNG)
GraphQL vs REST: Advantages of GraphQL

· GraphQL uses one endpoint. The client can retrieve all needed data in one request, improving performance.
 

![Slide8](/presentation/src/assets/page1/images/Slide8.PNG)

 The Flexibility of GraphQL

· A single endpoint allows clients to accurately specify and retrieve data, avoiding the redundancy common in REST.

![Slide9](/presentation/src/assets/page1/images/Slide9.PNG)
The Data Structure of GraphQL

· The returned data structure is determined by the client's query, not fixed by the server, increasing development flexibility.

 
![Slide10](/presentation/src/assets/page1/images/Slide10.PNG)

GraphQL and Database Interaction Process

· GraphQL uses resolvers to interact with the data layer (e.g., Mongoose for MongoDB). Tools like DataLoader prevent N+1 issues.

![Slide11](/presentation/src/assets/page1/images/Slide11.PNG)

GraphQL + Node.js Server Architecture

· Build servers using Apollo Server and Express. Define types and resolvers, then connect to your database.

![Slide12](/presentation/src/assets/page1/images/Slide12.PNG)

Advantages of the Server Architecture

· This architecture supports hot reloading, plugins, and has a clear structure, making it great for development and production.




![Slide13](/presentation/src/assets/page1/images/Slide13.PNG)

The Flexibility of Server Architecture

· The server-side architecture is highly flexible and can be extended with plugins and middleware for different project needs.

![Slide14](/presentation/src/assets/page1/images/Slide14.PNG)

Part 2: User System Tutorial BASIC

· This section introduces a practical project to apply the GraphQL concepts.


![Slide15](/presentation/src/assets/page1/images/Slide15.PNG)
What is Our Project?

· A lightweight web application using a front-end and back-end separation architecture for user information management.


![Slide16](/presentation/src/assets/page1/images/Slide16.PNG)

Project Architecture: Back-end & Front-end

· The backend provides a GraphQL API. The frontend handles rendering and user interaction.

![Slide17](/presentation/src/assets/page1/images/Slide17.PNG)
User System: Back-end Part - Project Structure

· Directory structure: server/, graphql/typeDefs.js, graphql/resolvers.js, models/User.js.



![Slide18](/presentation/src/assets/page1/images/Slide18.PNG)
 Technology Stack

· A modern stack: Node.js, GraphQL, MongoDB, Mongoose. Supports real-time data and complex relationships.


![Slide19](/presentation/src/assets/page1/images/Slide19.PNG)
The Basic User Information

· User model fields: id, name, email, age, createdAt.


![Slide20](/presentation/src/assets/page1/images/Slide20.PNG)

Tutorial BASIC: Server Configuration

· Code initializes a Node.js server with Express and Apollo Server, connects to MongoDB, and sets up CORS.



![Slide21](/presentation/src/assets/page1/images/Slide21.PNG)
Tutorial: Query and Mutation Statements

· This section shows the code for adding, modifying, and deleting users.



![Slide22](/presentation/src/assets/page1/images/Slide22.PNG)

Technologies Used: GraphQL SDL & Node.js

· Using GraphQL Schema Definition Language and Node.js with the gql template literal.

![Slide23](/presentation/src/assets/page1/images/Slide23.PNG)
Code Analysis 1: User Type Definition

· Defines the User type with fields like id: ID!, name: String!, email: String!, and age: Int.


![Slide24](/presentation/src/assets/page1/images/Slide24.PNG)

Key Features of the Schema

· Strong typing, CRUD operations, null safety, and a clear API contract between client and server.

![Slide25](/presentation/src/assets/page1/images/Slide25.PNG)

Code Analysis 2: Query Operations

· Defines queries: users to get all users, and user(id) to get a single user by ID.

![Slide26](/presentation/src/assets/page1/images/Slide26.PNG)

 Code Analysis 3: Mutation Operations

· Defines mutations: createUser, updateUser, and deleteUser for managing user data.
![Slide27](/presentation/src/assets/page1/images/Slide27.PNG)

 Front-end Clients: React and Svelte

· The project includes two clients: React (virtual DOM, JSX) and Svelte (compile-time optimization).


![Slide28](/presentation/src/assets/page1/images/Slide28.PNG)

User System: Structure and Routes

· The UI is composed of modules: a User Form and a User List.

![Slide29](/presentation/src/assets/page1/images/Slide29.PNG)

 Development Setup

· Steps: Use a Dev Container, initialize the Svelte project, integrate Apollo Client, and run the dev server.

![Slide30](/presentation/src/assets/page1/images/Slide30.PNG)

User Interface Components

· The app includes a Header, Input Form, Data Table, Action Buttons, and uses Responsive Design.

![Slide31](/presentation/src/assets/page1/images/Slide31.PNG)

Result: A Functional Full-Stack Application





![Slide32](/presentation/src/assets/page1/images/Slide32.PNG)


 Form Component Logic

· The form component uses controlled components, conditional rendering, and validation for both create and update modes.

