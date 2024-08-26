### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
React Router is a JavaScript framework that allows us to handle client-side AND server-side routing in React. We can create and navigate single-page apps and websites without refreshing the page every time we interact.

- What is a single page application?
A single page application is an environment where all renders and updates can occur without reloading the page. This means that the new data from user interaction is written into the current page.

- What are some differences between client side and server side routing?
Server-side uses the server, results result in a full reload of the page, and the server fetches the HTML file in response to user interaction. Client-side uses the client's browser, it intercepts requests and loads them into the current page without reloading or refreshing, and the content changes happen with async.

- What are two ways of handling redirects with React Router? When would you use each?
Client-side redirects with React router can mimic the behavior of server-side redirects and is useful after form submissions, button clicks for increments, or other user actions. It can also be used in lieu of having a catch-all 404 component. Using the <Redirect> component is useful when the user gets t oa page they shouldn't have reached, and they are automatically redirected to a different page. You can also call the .push method on the history object, which is useful when the user finishes something and is automatically redirected to the new page.

- What are two different ways to handle page-not-found user experiences using React Router? 
First is using the catch-all route * path, which helps display a 404 page. Second is using a redirect to a 404 page with <Navigate to>

- How do you grab URL parameters from within a component using React Router?
useParams hook and the use of Routes

- What is context in React? When would you use it?
Context lets you share state or values between components without having to pass props through every level of the tree. It helps manage global state and avoid prop drilling. It can also be used for user authentication, themes and localization with language/time.

- Describe some differences between class-based components and function
  components in React.
Functional components are regular JavaScript, while class-based require you to Extend from react. Functional components don't use render, and class-based components require render() returning some JSX code. Functional components run top to bottom, and after return happens the function ends. Class-based components can keep the methods running. Functional components are stateless because they just accept and show data, while class-basedcomponents are stateful because they use logic and state. Constructors are used with class-based components but not functional components.

- What are some of the problems that hooks were designed to solve?
Huge components that have seemingly endless trees and props, confusing classes, and difficulty properly wrapping components and JSX code.