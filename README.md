# React-basic

## SetState
* Always make use of setState and never modify the state directly.
* Code has to be executed after the state has been updated? Place that code in the call back function which is the second argument to the setState method.
* When you have to update state based on the previous state value, pass in a function as an argument instead of the regular object.

## Destructuring props and state
* Destructuring props
 
![alt text](https://github.com/Quynh-2302/React-basic/assets/85424168/d2467c6e-8ca6-40fb-8219-f26a3317003e)
* Destructuring state
  
![alt text](https://github.com/Quynh-2302/React-basic/assets/85424168/c3d88458-4a91-4f15-8b90-80d316c573a6)

## Event Handling

![image](https://github.com/Quynh-2302/React-basic/assets/85424168/afb24328-d305-4aa8-b754-ae111fcbb482)

*Class component event handling

![image](https://github.com/Quynh-2302/React-basic/assets/85424168/33087110-44f6-451a-bc31-20aa0967cd2d)

## Binding Event Handlers
* Binding Event Handler using Arrow Function
* Binding Event Handler in Render Method: We can bind the handler when it is called in the render method using **bind() method. 
* Binding Event Handler in the Constructor: We are going to bind the event handler inside the constructor. This is also the approach that is mentioned in ReactJS documentation. This has performance benefits as the events aren’t binding every time the method is called, as opposed to the previous two approaches. Just add the following line in the constructor for this approach.
* Binding Event Handler using Arrow Function as a Class Property: This is probably the best way to bind the events and still pass in parameters to the event handlers easily.

![image](https://github.com/Quynh-2302/React-basic/assets/85424168/a6eec40a-e91a-46fa-9d6c-7354b97bc17d)



