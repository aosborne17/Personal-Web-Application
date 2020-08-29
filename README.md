# Creating A React Application


### If you are already familiar with React, locate to the prerequisites part to see how we will run this application

## What is React

	
- React is a JavaScript library created by Facebook

- React is a User Interface (UI) library

- React is a tool for building UI components

## Why Do JavaScript Developers Use React JS?

React is a JavaScript library that specializes in helping developers build user interfaces, or UIs. In terms of websites and web applications, UIs are the collection of on-screen menus, search bars, buttons, and anything else someone interacts with to USE a website or app.

- This also provides reusable code for developers to use, thus saving deployment time and cutting down on any errors

#### In addition, React also comes with two veryn appealing features

## JavaScrit eXtesnion(JSX)

At the heart of any basic website are HTML documents. Web browsers read these documents and display them on your computer, tablet, or phone as web pages. During this process, browsers create something called a Document Object Model (DOM), a representational tree of how the web page is arranged. Developers can then add dynamic content to their projects by modifying the DOM with languages like JavaScript.

JSX (short for JavaScript eXtension) is a React extension that makes it easy for web developers to modify their DOM by using simple, HTML-style code. And—since React JS browser support extends to all modern web browsers—JSX is compatible with any browser platform you might be working with.

This isn’t just a matter of convenience, though—using JSX to update a DOM leads to significant site performance improvements and development efficiency. How? It’s all about the next React feature, the Virtual DOM.


## Virtual DOM

If you’re not using React JS (and JSX), your website will use HTML to update its DOM (the process that makes things “change” on screen without a user having to manually refresh a page). This works fine for simple, static websites, but for dynamic websites that involve heavy user interaction it can become a problem (since the entire DOM needs to reload every time the user clicks a feature calling for a page refresh).

However, if a developer uses JSX to manipulate and update its DOM, React JS creates something called a Virtual DOM. The Virtual DOM (like the name implies) is a copy of the site’s DOM, and React JS uses this copy to see what parts of the actual DOM need to change when an event happens (like a user clicking a button).

Let’s say a user enters a comment in a blog post form and pushes the “Comment” button. Without using React JS, the entire DOM would have to update to reflect this change (using the time and processing power it takes to make this update). React, on the other hand, scans the Virtual DOM to see what changed after a user action (in this case, a comment being added) and selectively updates that section of the DOM only.

This kind of selective updating takes less computing power and less loading time, which might not sound like much when you’re talking about a single blog comment, but—when you start to think about all the dynamics and updating associated with even a slightly complex website—you’ll realize it adds up to a lot.


## Prerequisites for this project

- Install Git [HERE](https://git-scm.com/downloads)
- Install Nodejs [HERE](https://nodejs.org/en/download/)

## Cloning the repo

- Locate to the folder in your terminal that you would like to host the app and then clone the repository

```
git clone https://github.com/aosborne17/Personal-Web-Application.git
```
```commandline
npm install
npm install @material-ui/core
npm start
```

## Creating your own react application

- Instead of cloning this repository, you could also create your own react app by downloading the template; this can be done running the below command


```commandline
npx create-react-app react-app 
cd react-app
npm install
npm install @material-ui/core
npm start
```



## Authors

### Andrew Osborne