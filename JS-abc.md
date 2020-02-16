# The ABC of programming 

## 1/a what is a script and how do i create one?
A script is a series of instructions that a computer can follow to achieve a goal.

**WRITING A SCRIPT**
To write a script, you need to first state your goal and then list the
tasks that need to be completed in order to achieve it.
Start with the big picture of what you want to achieve, and break that down into smaller steps.
1. _DEFINE THE GOAL_: First, you need to define the task you want to
achieve. You can think of this as a puzzle for the computer to solve.
2. _DESIGN THE SCRIPT_: To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart.
3. _CODE EACH STEP_: Each of the steps needs to be written in a programming language that the computer understands. In our case, this is JavaScript.


## 2/b how do computers fit in with the world around them?
COMPUTERS CREATE MODELS OF THE WORLD USING DATA.

**OBJECTS & PROPERTIES**
_OBJECTS (THINGS)_
In computer programming, each physical thing in the world can be represented as an object.
Each object can have its own:
• Properties
• Events
• Methods
Together they create a working model of that object.

_PROPERTIES (CHARACTERISTICS)_
Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object.

_EVENTS_
In the real world, people interact with objects. These interactions can
change the values of the properties in these objects.
WHAT IS AN EVENT?
There are common ways in which people interact with each type of object.programs are designed to do different things when users interact with the computer in different ways. For example, clicking on a contact
link on a web page could bring up a contact form, and entering text into a search box may automatically trigger the search functionality.
An event is the computer's way of sticking up its
hand to say, "Hey, this just happened!"
WHAT DOES AN EVENT DO?
Programmers choose which events they respond to. When a specific event happens, that event can be used to trigger a specific section of the code. Scripts often use different events to trigger different types of functionality. So a script will state which events the programmer wants to respond to, and what part of the script should be run when each of those events occur.

_METHODS_
Methods represent things people need to do with objects. They can
retrieve or update the values of an object's properties.
WHAT IS A METHOD?
Methods typically represent how people (or other things) interact with an object in the real world. They are like questions and instructions that:
• Tell you something about that object (using information stored in its properties)
• Change the value of one or more of that object's properties
WHAT DOES A METHOD DO?
The code for a method can contain lots of instructions that together represent one task. When you use a method, you do not always need to
know how it achieves its task; you just need to know how to ask the question and how to interpret any answers it gives you.

_PUTTING IT ALL TOGETHER_
Computers use data to create models of things in the real world.
The events, methods, and properties of an object all relate to each other:
Events can trigger methods, and methods can retrieve or update an object's properties.

**WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS**
Web browsers create similar models of the web page they are showing
and of the browser window that the page is being shown in.
WINDOW OBJECT
On the right-hand page you can see a model of a computer with a browser open on the screen. The browser represents each window or tab using a
window object. The location property of the window object will tell you the URL of the current page.
DOCUMENT OBJECT
The current web page loaded into each window is modelled using a document object.
The title property of the document object tells you what is between the opening `<title>` and closing `</title>` tag for that web page, and the
l astModi f i ed property of the document object
tells you the date this page was last updated.

**THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE**
Using the document object, you can access and change what content
users see on the page and respond to how they interact with it.
Like other objects that represent real-world things, the document object has:
PROPERTIES
Properties describe characteristics of the current web page (such as the t itle of the page).
METHODS
Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or
adding new content).
EVENTS
You can respond to events, such as a user clicking or tapping on an element.

## 1/c how do i write a script for a web page?

HOW HTML, CSS & JAVASCRIPT FIT TOGETHER?
Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript.

CONTENT LAYER (. html files)
This is where the content of the page lives. The HTML gives the page structure and adds semantics.

PRESENTATION LAYER (.css files)
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).

BEHAVIOR LAYER (.js files)
This is where we can change how the page behaves, adding interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.

_CREATING A BASIC JAVASCRIPT_
JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.

_LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE_
When you want to use JavaScript with a web page, you use the HTML
`<script>` element to tell the browser it is coming across a script.
Its s re attribute tells people where the JavaScript file is stored.