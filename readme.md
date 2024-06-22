# React Notes

## React Hooks 

### 1. UseState => UseStae basically is a react hook which is basically used is to change the UI Component via variable change in react.It's contains two things one is a variable and another is a function.

### Syntax : ``` const[counter,setCounter] = useState(default value); ```

### 2. useCallback => useCallback is also basicallly is a react hook which is basically used for optimzation of react component(variable,function).When a component is re-render is too many more time in this case we use useCallbacxk for storing caching value and memoization value.

### Syntax: ``` const variableName = useCallback(fn,[]) in this array we put this type of value which are re-render in freaquently.

## 3. useEffect => useEffect is a react hook which is a hooks used in when we needs changes of a component it's changes to the UI also then in a depandency array we put all the depandancy component.In changes of this componenet UI also re-render.

### Syntax: ``` const useEffect(fn,[depandancy Array]) ``` changes of depandancy array all the web page also re-render.

## 4. useRef => useRef is a react hooks in using this hooks we can pass reference the particular components to another component.

## syntax ``` const ref = useRef(initial or default value) ```
