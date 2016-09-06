React.js

What is React? 1.1
Open Sourace, maintained by FB
Think of as the "v" (view)	in MVC
Ideal for large-scale, single page applications
Uses high-speed virtual DOM
Uses clean and easy to understand JSX syntax

Why React or fast? 1.2
React.js is popular because of the DOM rendering speed. 
DOM - structure of the HTML or XML elements that make up a web page.
DOM objects are SLOW
JS objects are FASTER
The React virtual DOM is a JS object
React NEVER reads from the 'real' DOM
React only writes to the real DOM if needed
React handles DOM updates VERY efficiently

React only interacts with the virtual DOM
Use getDOMNode() we will get state information from the virtual DOM
When we call the render function, react will update the virtual DOM and only push the necessary changes to the real DOM

Setting Up React Tool for Chrome 1.3
Install the React Detector
	* lets you know when you are on a page with React code in it
	* expand the react dev tools once downloaded
	mac - cmd + opt + j 
	win - ctrl + shift + j
	* react tab in the dev tool, shows which elements on the page are created using React

Introducing JSX and Babel 2.2
In the example we incorporated JSX into our react file and Babel does all the transformation

What is a React component? 3.1
	*In chapter 2.2, we made a React component called Hello World that displays data in a div, all that map to the create element function when pre-processed. This means that our user interface is comprised of different components.
	*Components are modular so you can use React for certain components of the site
	*React can be used for smaller features or the entire site

Creating a React Component 3.2

Using Properties 3.3
	We can add properties to our component. Think of it as adding properties to an element.
	Properties let us reuse components with different data

Handling Events 3.4
	1.53 minutes in. The page wont render because there is a cross origin request error
		Caused by the JSX Transformer library file and the Notes.js file
		As a security feature chrome tries to block this when we try to load from the local file system
			You can complie your JSX, run a local server of MAMP, etc, OR run Firefox

Using State 3.5
	State is one of the most important react components.
	When a component's state changes the render function will be called again to rerender the data 


	

	












