![Angular](./Images/Angular.png)
# LEARNING ANGULAR FROM BASIC


# I. Prequisite
- Basic understand typescript, html, css
- Basic using of git
- Having knowledge with building web api

# II. After finish this course you can
- Understand the full lifecycle of development an angular app: setup, implementation(design + code) and deploy an angular application
- Can build a simple angular web app to allow login, logout, manage list of products like view list of product, view product detail, add a new product, update an existing product or delete it.

# III. Steps to go through
## 1. Setup
- Install Node.JS, Visual studio, Restful Api Extension, Angular CLI
- Setup project Web API to run: Visual studio, Source code, ...
- Using Angular CLI to create a new angular project

## 2. Implementation
### a. Understand how Angular project work and fundamental elements
- App structure in a nutshell: Angular app is just a tree of components
- Fundamental elements of App
    - Components
    - Routing
    - Services
    - Dependency injection for Services
    - Modules

### b. Develop a single component
#### **Objective**: Can develop an individual component

#### **Output**: Done develop following components
- Login component 
- Logout component
- List of product component
- View product component
- Update product component
- Create product component

#### **Content:**
- Using angular-cli to create a new component
- Binding data
- Event handling
- Pipes
- Directives
- Getting parameters
- Lifecycle of a component, hook methods
- Working with basic controls of Prime-NG:
    - Form
    - Table
    - Notification
    - Confirmation
    - Popup
    - etc
- Develop a component having a table containing list of items
- Develop a component having form to add new
- Develop a component having form to update a existing item
- Develop a component showing detail of an item
- Perform delete with confirmation popup

## c. Put components together
#### **Objective**: from the requirement then design the UI/UX, organize flow of page interaction, separate app into component for reuse and easy to develop, put components together to peform a purpose.  

#### **Output**: Complete the flow of managing a product list with data is saving in-memory.

#### **Content**
- Create a wire frame
- Separate design into components, tree of components, common component for reuse
- Exchange data beween components: 
    - Parent component to children component
    - Child component to child component
    - Children components to parent component
    - Between any components
- Jumping between components

### d. Integrate with backend api

#### **Objective**: Until now just save data in-memory. Now we persist data to datastore using backend api and using backend to perform business logic.

#### **Output**: login and logout with api, enhance the management of product list by persist data into database using backend api.

#### **Content**:
- Environement
- Restful API Introduction
- HttpClient for making http request
- Inject and use services in components
- Http Error handling
- Error handling
- Authorization with Http Interception
    
### e. Dealing with cross cutting concerns:
- Global error handling
- Notification
- Logging

# III. Deployment:
## 1. Build the project
## 2. Deploy to Server: IIS, Azure Web App


