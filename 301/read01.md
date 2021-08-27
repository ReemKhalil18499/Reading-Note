# What is a component?  
Js is a dependency injection framework for JavaScript applications. Object-oriented applications are typically composed of hard-wired component. For example, when programming a Car instance, several Seat components of a specific type can be inserted.  

![component](https://componentsjs.readthedocs.io/en/latest/example.svg)  

+ Virtual DOM. Virtual DOM is one of the chief characteristics that facilitate fast and flexible application development using Reactjs.  
+ JSX.  
+ One-way data binding.  
+ React native.  
+ Declarative UI.  
+ Component-based architecture.  
+ Speed and efficiency.  
+ Flexibility.  

### Advantages  
+ Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.  
+ Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.  

# Props {Properties}  

![component](https://www.webdevtactics.com/wp-content/uploads/2021/03/3.png)  

+ It's a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.  

### What is the flow of props?  
+ While a component can’t change its own props, it can change its state…Props and state are used as input for the render() method to determine its output. The render() method also calls the diff algorithm which recognizes any changes in the component and logs them for batching to the “real” DOM.  

![component](https://miro.medium.com/max/1182/0*35JeHn5u_Kldva32.png)  