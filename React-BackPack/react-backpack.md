### What is react js?
<p>ReactJS is a Frontend Library through which we can make Web and mobile user interfaces. Reactjs allow us to make a reusable UI component that is so convenient and user-friendly. And it is easy to learn and it has a big community.</p>

### What is react component?
<p>component is the unique feature of the  Frontend Library or framework. React component is an independent and reusable piece of code. If we get any code on your website that is repetition, we can make a component with that repetition code. Then we can use it everywhere.</p>


### What is the main difference between props and state?
<p>State: State is mutable because based on user action it changes, whereas, Props is immutable, it can not change, and it is also read-only.</p>
<p>State: State holds all of the data about the component. this data is not accessed by the child component. Props: Props allow the developer to pass data from one component to another component. this data is only accessed by child component</p>
<p>Props make components reusable but the state can not make components reusable.</p>

### What is a useState() in react.js?
<p>useState() is react hook of the functional component. it is a function that returns an array and initial value as an argument of useState(). The first element of the array is the data or state, the second element is the updated function. The state we can use anywhere, but if we want to update the state inside the component we have to use the updated element</p>

### when a component is rerendering?
<p>There are three situations component is rerendering</p>
<u>
<li>When a props changed</li>
<li>When a state is change</li>
<li>when parent component is rerendering</li>
</u>

### What is the component tree in a react?
<p>Component tree one kind of parent-child relationships through which we can pass data parent to a child component, but data flow always top to bottom, not bottom to top</p>

### What is the JSX in React?
<p>JSX is the function, behind the seen we are invoking the javascript function, but we are using JSX as an HTML because of comfortable reading, and writing code</p>

### What are the child props?
<p>When inside a custom component we pass anything, which is called child props.</p>

### what is the conditional rendering in react js, where we use conditional rendering?
<p>Conditional Rendering is the powerful feature through which we can render dynamic data with this. </p>
<p>When we want to select a class name, when we want to select attributes, for styling, we can use in terms of value provided, which component will be rendered to make a decision</p>

### What is the useEffect() hook?
<p>useEffect() is a react hook that allows performing side effects of our react component. Another meaning is that it also tells react anything need to do after rendering we can use react useEffect() hook </p>

### What is a functional component in React.Js?
<p>When a function returns a Jax, it's called a functional component as react.js</p>

### What are the important things to make a functional component?
<p>Name have to be a capital</p>
<p>This function should return HTML like JSX</p>
<p>A functional component must have one argument, we can not use one more argument. this argument must be an object</p>
<p>We can not call or invoke this function, because invoking, or calling is not our responsibility, react is responsible for this call or invoke.</p>
<p>We must have to use function as an HTML tag</p>

### Why React Move Class-based Component to Functional Component?
<p>First issue is the performance issue. The class component is very costly when it is instantiated. It means we need too much space in the CPU.but functional component is good because it needs a low CPU </p>
<p>Secondly, react to everything done with virtual DOM, Virtual DOM means it is the clone of real DOM. Class-based component work in a mutable way, when we change any data, it changes data but the address does not change. it is an issue for the performance of react. If we use a functional components we can work immutable way, if we change any data it also changes the address as well as the data.</p>

### What are the benefits of a Functional Component?
<p>It's developer friendly</p>
<p>State management is very easy than class component</p>

### What is Virtual DOM?
<p>react everything does with virtual DOM, Virtual DOM means it is the clone of real DOM</p>





