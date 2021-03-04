### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

  // a Javascript library created and maintained by Facebook. 
  // It's used to manage the DOM and create highly performant user interfaces and front end apps
  // uses component bases architecture and unidirectional data flow
  // has its own virtual DOM

2.  What is create-react-app?

  // create-react-app is a bootstrapping tool that helps dev easily get off the ground and started with a React project.
  // a package that sets up a new React project
  // sets up a developer server for us that will auto-refresh on changes

3.  What is Component Based Architecture?

  // an app uses components to make up each part of our app. this creates organization and an understanding on how to layout our components in our app
  // the concept of encapsulating individual pieces of code to bring together into a larger project/app.

4.  What is JSX?

  // a syntax extension to JavaScript. JSX produces React 'elements' that describe how the user interface should appear for the React element.
  // looks very much like HTML but is not HTML
  // it is eventually transpired into regular JS function calls
  // JSX is not exclusive to React

5.  What is the virtual DOM?

  // a light-weight copy of the actual DOM. A representation we use to update our user interface in React
  // React updates the virtual DOM when any changes to a component are made, then uses the virtual DOM to decide what parts of the actual DOM to change
  // only updates the pieces that need to be updated

6.  What is unidirectional (one-way) data flow?

  // data can only flow one way to other parts of the application
  // (e.g. parent to child using props)
  // this ensures we have a 'Single Source of Truth'


### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

  // create-react-app installs react apps into directories or globally on a device.

8.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

  // this code is a component that displays elements to the user interface by exporting the code to a different document

9.  Explain how data is passed from a parent component to a child component.

  // 

### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

14. Compare and contrast one-way data flow with two-way data binding.
