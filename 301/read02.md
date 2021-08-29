# React
<!-- from onlin -->
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
static getDerivedStateFromProps, shouldComponentUpdate, render,
getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate, UNSAFE_componentWillReceiveProps
## The constructor for a React:
 component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance. Let’s take a look at some example code.
### the order that happen:
1. render
2. componentDidMount
3. constructor
4. componentWillUnmount
5. React Updates

## React State Vs Props
**props**:its like an arguments to a function
we can change props to another one
props pass into a component
we can use it in order to make it dynamic
**state** handled inside of the component
and its updated inside the component
and we can re-render our application
we can use it for example in counter.