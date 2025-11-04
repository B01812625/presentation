## Graghql Setup Tutorial

What is GraphQL?
GraphQL is an API query language developed by Facebook that allows you to request the exact data you need without any redundancy. Unlike REST, where fixed endpoints always return predefined data, GraphQL allows you to customize the response structure.

Now, let's start installing and using it.

### About Installation:

Step1:Setting Up GraphQL with Node.
You’ll start by creating a basic file structure and a sample code snippet.
First, create a GraphQL directory:

![1](/presentation/src/assets/page2/images/1.png)

Change into the new directory:

![2](/presentation/src/assets/page2/images/2.png)

Initialize an npm project:

![3](/presentation/src/assets/page2/images/3.png)

Then create the server.js file which will be the main file:

![4](/presentation/src/assets/page2/images/4.png)

Your project should resemble the following:

![5](/presentation/src/assets/page2/images/5.png)

Necessary packages will be discussed in this tutorial as they are implemented. Next, set up a server using Express and express-graphql, an HTTP server middleware:

![6](/presentation/src/assets/page2/images/6.png)

### About coding: 

Step1:
Open server.js file and add the following lines of code.
This snippet accomplishes several things. It uses require to include the packages that were installed. It also initializes generic schema and root values. Furthermore, it creates an endpoint at /graphql which can be visited with a web browser.
Save and close the file after making these changes.

![7](/presentation/src/assets/page2/images/7.png)

Step2: Defining a Schema.
In the GraphQL schema language, you might represent a user with an id, name,email,and age like this example:

![8](/presentation/src/assets/page2/images/8.png)

Step3:Set parser.
Schema sets the way to build queries, but building a schema to define data schemas is only part of the GraphQL specification. The other part involves actually obtaining data by using a parser, which is a function that returns the basic value of a field.

![9](/presentation/src/assets/page2/images/9.png)

Step4:Run Server。
Finally, let's run the demo! Because we use Express, we can use the express graphql package to expose our pattern as an endpoint.

![10](/presentation/src/assets/page2/images/10.png)

### Conclusion
So far we have covered from very basic concepts of GraphQL to some fairly complex examples. Most of these examples clearly reveal the differences between GraphQL and REST for users who have interacted with REST. 