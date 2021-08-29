# what happens first, the ‘render’ or the ‘componentDidMount’?  
![img](https://miro.medium.com/max/1089/1*nleLui-x8YNJhZaEwwLioQ.png)  
+ When a component is mounted it is being inserted into the DOM. This is when a constructor is called. componentWillMount is pretty much synonymous with a constructor and is invoked around the same time. componentDidMount will only be called once after the first render.  

Updating lifecycle methods  
1) static getDerivedStateFromProps()  
2) shouldComponentUpdate()  
3) render()  
4) getSnapshotBeforeUpdate()  
5) componentDidUpdate()   

# Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates :
1st: constructor  
2nd: componentWillUnmount  
3rd: render  
4th: React Updates  
5th: componentDidMount

# ComponentDidMount   
![img](https://cdn.educba.com/academy/wp-content/uploads/2020/07/React-ComponentDidMount.jpg)  

+ This method allows us to execute the React code when the component is already placed in the DOM (Document Object Model). This method is called during the Mounting phase of the React Life-cycle i.e after the component is rendered.  

+ All the AJAX requests and the DOM or state updation should be coded in the componentDidMount() method block. We can also set up all the major subscriptions here but to avoid any performance issues, always remember to unsubscribe them in the componentWillUnmount() method.  
