# React useEffect Dependency Array Issue

This example demonstrates a common issue with the useEffect hook in React. The title of the page only updates when the count goes above 5 and doesn't update when the count decreases below 5.  This is due to an improper use of the dependency array.