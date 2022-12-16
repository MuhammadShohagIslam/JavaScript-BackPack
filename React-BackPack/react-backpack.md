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



