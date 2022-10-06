# Class 6 Reading Notes - *Dynamic web pages with JavaScript*

## What is JavaScript?

JavaScript (JS) is a programming or scripting language which adds interactivity to web pages. Examples of this interactivity include: interactive maps, animated 2D/3D graphhics, text boxes, buttons, etc. It also has uses in non-browser environments such as Node.js, Apache CouchDB, and Adobe Acrobat. JavaScript is NOT equivalent to the Java programming language as both languages have different syntax, semantics, and uses.

- HTML --> Structure/Skeleton
- CSS --> Style/Design
- JS --> Actions/Interactivity

Variables are labels/containers for storing data. A variable can have a declared/defined value or no value (undefinded).

For example:

Declaring a variable AND assigning value
> let myName = "Armon"

Delcaring a variable with NO value: 
> let backpack;

### Types of Data

1. Strings --> Text
    - `'Your text goes here'`
2. Numbers --> No quotation marks
    - `42; -5; 0.27`
3. Boolean --> Logic
    - `True`
    - `False`

## Intro to JavaScript - Basic output

JavaScript is typically used inside web browsers by adding JS code to the HTML page. The JS code can run in the browser (client side) as opposed to running on a web server (server side).

Three Major Parts of "JavaScript":

1. JS language - standard among various environments and various browsers/servers.
2. DOM API - how the language interacts with various parts of a web page while in a given browser.
3. Server API - provided by Node.js or other server-side systems.

### Editor or IDE

Most text editors can be used to write JS

### Embedding or Adding JS to your HTML page

JavaScript can be *embedded* directly inside the HTML file or a line of code can be added in the HTML file which will link to an external JS file.

To embed JS a `<script>` opening tag and `</script>` closing tag are added with the JavaScript code inserted between the tags.

### JavaScript Input/Output Commands

1. JS command: `alert("text")`
    - Shows a pop-up in the browser with the desired `"text"`
2. JS command: `document.write("<h1>Hellow World</h1>")`
    - Will display/write desired text at a certain location in the file.
3. JS command: `console.log("text")`
    - Allows developers to print out debugging information
    - 

## How Computers Work

#### Binary & Data

- Input: Telling a computer what to do.
- Storage: Info that is stored in a computer's memory
- Processing: A computer takes an input, runs an algorithm, and then produces an output
- Output: Depends on what a computer is designed to do.

#### Circuits & Logic

- Binary: a series of 1's and 0's which represents information to a computer
- Bit: Smallest piece of information a computer can store. Represents a 1 or 0, True or False, and On or Off respectively.
- Sound in Binary: Sound can be represented by a waveform with data points assigned which represent numbers on a graph.

#### CPU, Memory, Input, & Output

- Circuits: A simple circuit takes an electrical signal (1 or 0) and flips it. A complicated circuit takes multiple signals and produces multiple outputs.
- The smaller the circuit, the faster an electrical signal travels and performs a calculation.

#### Hardware & Software

- Input, Store, Process, and Output
- Input Devices: Keyboard, touchpad, microphone, etc.
- CPU: A keyboard converts a letter to numbers...
- Output Devices: Screen/monitor, speakers, 3D printers, etc.
