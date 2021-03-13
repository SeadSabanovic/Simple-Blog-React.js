#  React Practice Blog
![Fake Blog](https://raw.githubusercontent.com/SeadSabanovic/Simple-Blog-React.js/main/Blog1.png)
![Fake Blog](https://raw.githubusercontent.com/SeadSabanovic/Simple-Blog-React.js/main/Blog2.png)
___
### What I learned: 
- Programmatic Redirects with { useHistory }
- Smooth page transitions with 'react-transition-group'

### How it works
On page load, the App fetches data from the **[{JSON} Placeholder API](https://jsonplaceholder.typicode.com/)**, then maps the data inside the Homepage.
```javascript
useEffect(() => {
	fetch("https://jsonplaceholder.typicode.com/posts?_limit=10")
```
After Adding a new Blog, the user is automatically redirected to the Homepage, where all the blogs are shown.

### Features:
- Smooth Page Transition
- Programmatic Redirect to the Homepage after adding new items
- Form control and input validation
- Form Errors
- Loader is active until initial data is fetched
