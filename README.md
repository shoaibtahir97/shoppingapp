# Create a shopping basket using React and Redux Toolkit

Redux, a predictable state container for JavaScript applications, has justifiably had a bad reputation in the past for being overly complex and verbose. Whilst this can still be true, times have changed, the library has changed and evolved, and combined with the amazing Redux Toolkit, many of the historic complains have been alleviated.

For the complete tutorial, check out the blog post over on [DeveloperHandbook.com](https://developerhandbook.com/stripe/create-shopping-basket-using-redux-toolkit/)
//Removing is the same as adding, except we set added to false instead of true.
//by spreading the old one(using the spread operator ...)and then changing the added flag to true.
//Notice that on each iteration of map, we are returning a new copy of the product 
//We use the product id to find the product and set its added value to true.