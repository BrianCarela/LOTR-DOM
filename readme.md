![](https://camo.githubusercontent.com/0f02bf4db8975e500603f16d431d494c277f9876/687474703a2f2f737461746963322e666a63646e2e636f6d2f636f6d6d656e74732f416c72656164792b7369636b2b6f662b736565696e672b746869732b626974636865732b756e696e74656c6c6967656e742b6c6f6f6b696e672b666163652b5f39666236393334653138376631616236666637346666316664376438336636612e6a7067)

## Fellowship of the Ring DOM Manipulation

We are going to practice querying and manipulating the DOM with JavaScript. In this homework, we're creating functions for each part of the hobbits' journeys practice DOM Manipulation and JavaScript.

- You will need to use loops in your functions to do things like dynamically adding or removing list items from an unordered list.  
- Always keep in mind the parent/child node relationship on the DOM. This is key for understanding and manipulating objects on the DOM.

## Setup
- Everything within this directory should be linked properly. You don't need to serve any files, simply open index.html in Chrome and access the developer console to begin work.
- Do all of your work in the included `fellowship.js` file in the scripts folder. No need to touch `index
- Test early and often! Be sure to INVOKE your function.

## Completion
There are 12 steps to the homework. A complete homework requires at least 8 complete steps. As always, more is better but sleep and sanity is more important.  

If you decide to work past the first 5 steps, be sure to review documentation and/or research on W3Schools/MDN - there may be some content we haven't covered in class.  Nothing crazy though, promise.

After each step is completed, remember to `git add .` and to `git commit -m "meaningful commit"`!

## Resources
- [DOM Reference](https://developer.mozilla.org/en-US/docs/DOM/DOM_Reference)
- [DOM Cheatsheet](http://christianheilmann.com/stuff/JavaScript-DOM-Cheatsheet.pdf)

## Assignment

#### 1

```javascript
function makeMiddleEarth() {
    // create a section tag with an id of middle-earth
    // add each land as an article tag (add them one by one in a loop)
    // inside each article tag include an h1 with the name of the land
    // each article should also have a class equal to it's name ('Mordor' element should have a class of 'mordor', 'The Shire' should have a class of 'the-shire' - HINT: look up .split() and .join() for strings )
    // append middle-earth to your document body
}
```

#### 2

```javascript
function makeHobbits() {
  // display an unordered list of hobbits in the shire (which is the first article tag on the page)
  // each hobbit should be a list item, with text showing their name
  // give each hobbit a class of hobbit
}
```

#### 3

```javascript
function keepItSecretKeepItSafe() {
  // create a div with an id of 'the-ring'
  // give the div a class of 'magic-imbued-jewelry'
  // add the ring as a child of Frodo
}
```

#### 4

```javascript
function makeBuddies() {
  // create an aside tag
  // attach an unordered list of each 'buddy' in the aside
  // insert your aside as a child element of rivendell
}
```

#### 5

```javascript
function beautifulStranger() {
  // change the 'Strider' textnode to 'Aragorn'
}
```

#### 6

```javascript
function leaveTheShire() {
  // assemble the hobbits and move them to Rivendell
  // how does appendChild work on an element that already exists on the page?
}
```

#### 7

```javascript
function forgeTheFellowShip() {
  // create a new div with an id of 'the-fellowship'
  // add each hobbit and buddy one at a time to 'the-fellowship'
  // after each character is added make an <a href="http://www.w3schools.com/jsref/met_win_alert.asp">alert</a> that they have joined your party
  // append the fellowship div to rivendell
}
```

#### 8

```javascript
function theBalrog() {
  // change the 'Gandalf' textNode to 'Gandalf the White'
  // apply style to the element
  // add a gray 3px border
  // use documentation if you're unsure how to add style with javascript!
}
```

#### 9

```javascript
function hornOfGondor() {
  // pop up an alert that the horn of gondor has been blown
  // Boromir's been killed by the Uruk-hai!
  // Remove Boromir from the Fellowship
}
```

#### 10

```javascript
function itsDangerousToGoAlone(){
  // take Frodo and Sam out of the fellowship and move them to Mordor
  // add a div with an id of 'mount-doom' to Mordor
}
```

#### 11

```javascript
function weWantsIt() {
  // Create a div with an id of 'gollum' and add it to Mordor
  // Remove the ring from Frodo and give it to Gollum
  // Move Gollum into Mount Doom
}
```

#### 12

```javascript
function thereAndBackAgain() {
  // remove Gollum and the Ring from the document
  // Move all the hobbits back to the shire
}
```
