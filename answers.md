# React Review 1

## Answer 1 Create a Simple Component

```js
function Welcome () {
  return (
     <h1>Welcome to React!</h1>
  )
}
```

## Answer 2 Create a Bigger Component

```js
function Hello () {
  return (
     <>
     <p>Hello</p>
     <p>World!</p>
     </>
  )
  
}
```

## Answer 3 Create an Image Component

```js
function ProfilePicture () {
  return (
    <img src="../assets/image/profile-picture.jpg" alt="'The users profile picture'" />
  )
}

```

## Answer 4 Create a Component that Uses Variables

```js
const name = "John Doe";
const age = "30";

function UsesVariables () {
  return (
    <>
    <p>{name}</p>
    <p>{age}</p>
    </>
  )
}

```

## Answer 5 Is the Code Correct? Components

the apple component is not actually not a component it is a function. Therefor the Shoppinglist component will not render the <li> on the browser. I think that it will still render the h1 tag still because that is written correctly at least.

## Answer 6 Export a Component

```js
const TableOfContents = () => {
  return (
    <div>
      <h2>Table of Contents</h2>
      <ul>
        <li>Introduction to Biking</li>
        <li>Chapter 1: Choosing the Right Bike</li>
        <li>Chapter 2: Essential Bike Gear</li>
        <li>Chapter 3: Basic Riding Techniques</li>
        <li>Chapter 4: Maintaining Your Bike</li>
        <li>Conclusion: Enjoying Your Ride</li>
      </ul>
    </div>
  );
};

export default TableOfContents
```

## Answer 7 Import a Component

```js
import Profile from 'components/Profile.js'
```

## Answer 8 Is the Code Correct? JSX

No I think the h1 tag and the ul tag are siblings so the code needs a break around both elements to render.

## Answer 9 Fix the JSX Bugs

```js
const Bio = () => {
  return (
    <div className="intro">
      <h1>Welcome to my website!</h1>
    </div>
    <p className="summary">
      You can find my thoughts here.
      <br />
      <br />
      <b>And <i>pictures</b></i> of scientists!
    </p>
  );
}
```

## Answer 10 Create a Component with a Prop

```js
function Greeting (prop) {
  return ( 
    <p>Hello {prop.name}</p>
  )
}
```

## Answer 11 Pass a Prop to a Component

```js
import Greeting from './Greeting.js'

const App = () => {
  <Greeting name="with any string value you like" />
};
```

## Answer 12 Bain's talk

I learnt that we as a class were not respectively responsive to our guest speaker Bain except for a select few. We will need to try better to support our guests going foward.
