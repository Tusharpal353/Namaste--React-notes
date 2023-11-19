**RULES**

 1. Make your own NOTES
2.  Do simultaneously
3.  Be active on Github


## What is react ??

React is a JS libray for building user interface

React can only be applied to a small portion of a page

React is a library not a full fligied framework


## CDN
*Contact Delivery network*

it is like page from where we take the data there all data is uploaded.
by this we inject react into our poject

    
	<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js > </script>
	<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js >                                     </script>

by this link we are importing react code into our project




## Creating H1 in REACT

    <script> 
    const heading = React.createElement("h1", {}, "Hello World from React!"); 
    </script>
    
    const heading = React.createElement("h1", {}, "Hello World from React!"); 
    //{} this missing object is the place where u will give ATTRIBUTE

    for eg: const heading = React.createElement 
    "h1",
     { id: "heading" }, 
     "Hello World from React!"
      ); Į

   **Explanation**
   React.createElement() takes three arguments

		name- div, span

		attributes- id

children→ 
	1- normal react element,
	2- if it has multiple children we will pass it in as array



  ## ADDING CSS
  what is PROPS
props are childrens + attributes that we pass in

	props: {id: 'heading', xyz: 'abc', children: 'Hello World from React!'}
	 
	props: 
	children: "Hello World from React!"     
	id: "heading" 
	xyz: "abc"


## React Element

React Element is at the end of the day is object and this react object becomes the HTML that the browser understands

React.createElement is not creating a HTML ELEMENT it is creating an object when it is rendered on DOM it converts it self into HTML and put it as HTML.

## Basic Questions

 1. Does order of files matters ?
	 yes
	 
 2. WHAT DOES root.render() DO ?
 -   loads basic HTML
-   then as soon as it hits SCRIPT tag it loads REACT
-   It will replace with what we pass to what is already existing there

