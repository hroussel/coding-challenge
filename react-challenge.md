### App description

Create a simple ReactJS app that fetch and display a list of github issues. For each item display the id and the title. `ul` and `li` should be sufficient to display this list. 

The API supports pagination, at the beginning load the first page with 5 issues. At the bottom there is a button `Next` that loads the next 5 issues. 

Clicking on an issue item to highlight it. Click on it again will toggle the highlight. Only 1 item is highlighted at a time. 

Feel free to implement the UI your own way. However we'll pay attention to code quality, and how neatly you implement it. 

### API

This is the endpoint to fetch issues, it's publicly available, no need to authenticate. 

https://api.github.com/repos/rails/rails/issues?page=1&per_page=5

This is the `fetch` method to use for the api call, no need for jQuery. 

https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch

### ReactJS resources

Follow the instruction here https://facebook.github.io/react/docs/installation.html . Starting a new react project is as simple as: 

```
npm install -g create-react-app
create-react-app hello-world
cd hello-world
npm start
```

ReactJS state and life cycle can be found here https://facebook.github.io/react/docs/state-and-lifecycle.html 
