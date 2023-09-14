# React Interview Question

Q1. High Order Component ?

A1. High order component is a design pattern that allow you to reuse the component logic and it share with multiple component, As you know High Order function take the 
component as arrgument and return the new component with accept new props and functionality with the help of this you make your project more moduler and reuse.

Q2. React HOOKS ?

A2. React HOOKS is introduced in react 16.8 version that's make more powerfull and versatile.

  (i) useState - allows to functional compoenet to manage the local state.
    
    EX- const [count, setCount] = useState(0);
  
  (ii) UseEffect - It's handle the react lift cycle mathod Mount, update and unmount
    
    Ex-  useEffect(()=>{
      Arrgument
    },[Dependency]);
  
  (iii) useContext - It's access the context of parent component, it's used to consume values provided by a 'Context.Provider' component.
  
  (iv) useReducer - It's is used for complex state management scenerio like redux, it's take a reducer function and intial state and return the current stateand a displatch a function.
  
