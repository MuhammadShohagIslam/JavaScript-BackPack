### What is the main difference between props and state?
<p>State: State is mutable because based user action it's change, whereas, Props is immutable, it can not change, it also read only.</p>
<p>State: State hold all of the data about the component. this data is not access by child component. Props: Props allow developer pass data one component to another component.this data is only access by child component</p>
<p>Props make components reusable but state can not make components reusable.</p>

### What is a useState() in react.js?
<p>useState() is react hook for react functional component. it is a function which return a array and initial value as a argument of useState(). In the first element of the array is the data or state, second element is the updated function. state we can use anywhere, but if we want to update state inside component we have to use updated element</p>

### when a component is rerendering?
<p>There are three situations component is rerendering</p>
<u>
<li>When a props changed</li>
<li>When a state is change</li>
<li>when parent component is rerendering</li>
</u>

### What is the component tree in a react?
<p>Component tree one kind of parent child relation through which we can pass data parent to child component, but data flow always top to bottom, not bottom to top</p>

### What is the JSX in React?
<p>JSX is the function, behind the seen we are invoking javascript function, but we are using JSX as a HTML because of comfortable reading, writing code</p>

### What is the child props?
<p>When inside custom component we pass anything, which called child props.</p>

### what is the conditional rendering in react js, where we use conditional rendering?
<p>Conditional Rendering is the powerful features through which we can render dynamically data with this. </p>
<p>When we want to select class name, when we want to select attributes, for styling, we can use in term of value provide, which component will be render to make decision</p>

### What is the useEffect() hook?
<p>useEffect() is a react hook which allows to perform side effects of our react component.Another meaning that which also tell react anything need to do after render we can use react useEffect() hook </p>

### What is a functional component in React.Js?
<p>When a function return a jax, it's called functional component as react.js</p>

### What is the important things to make functional component?
<p>Name have to be a capital</p>
<p>This function should be return HTML like JSX</p>
<p>A functional component must have one argument, we can not use one more argument. this argument must be a object</p>
<p>We can not call or invoke of this function, because invoking, or calling is not our responsibility, react is the responsible for this call or invoke.</p>
<p>We must have to use function as an HTML tag</p>

### Why React Move Class based Component to Functional Component?
<p>First issue is that performance issue. Class component very costly when it is Instantiated.It mean we need to much space in the CPU.but functional component is good because it needs low CPU </p>
<p>Secondly, react everything do with virtual DOM, Virtual DOM means it is the clone of real DOM. Class based component work with mutable way, when we change any data, it change data but address does not change. it is issue for performance of react. If we use functional component we can work immutable way, if we change any data it also change address as well as data.</p>

### What is the benefits of Functional Component?
<p>It's developer friendly</p>
<p>State management is very easy than class component</p>





