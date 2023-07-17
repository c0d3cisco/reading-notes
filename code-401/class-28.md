# Component Lifecycle / useEffect() Hook

## useEffect hook

1. What is the main intended use case for the useEffect hook?\
	 The main intended use case for the useEffect hook is to allow us to perform side effects in function components.\
	 Side effects are actions that happen outside of the main flow of the function.\
	 Some examples of side effects are:
	 - Data fetching
	 - Setting up a subscription
	 - Manually changing the DOM in React components
2. How does the effect’s logic interact with the component?\
	 The effect’s logic interacts with the component by running after the component has rendered.\
	 The effect’s logic can also be run before the component renders and when the components unmounts or updates.
3. What is the importance of the return value from the effect’s logic function?\
	 The importance of the return value from the effect’s logic function is that it allows us to clean up the effect.\
	 The return value from the effect’s logic function is optional.\
	 If we return a function from our effect, React will run that function when it is time to clean up the effect.\
	 This is called a cleanup function.\
	 We can use this to cancel subscriptions or perform other cleanup tasks.
