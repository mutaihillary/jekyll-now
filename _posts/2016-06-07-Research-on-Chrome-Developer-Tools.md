### The Chrome Developer Tools
The Chrome Developer Tools (DevTools for short), are a set of web authoring and debugging tools built into Google Chrome. The DevTools provide web developers deep access into the internals of the browser and their web application. Use the DevTools to efficiently track down layout issues, set JavaScript breakpoints, and get insights for code optimization.

### Accessing the DevTools

To access the DevTools, open a web page or web app in Google Chrome. Either:
Select the Chrome menu Chrome Menu at the top-right of your browser window, then select Tools > Developer Tools.
Right-click on any page element and select Inspect Element.The DevTools window will open at the bottom of your Chrome browser.

There are several useful shortcuts for opening the DevTools:

Use Ctrl+Shift+I (or Cmd+Opt+I on Mac) to open the DevTools.
Use Ctrl+Shift+J (or Cmd+Opt+J on Mac) to open the DevTools and bring focus to the Console.
Use Ctrl+Shift+C (or Cmd+Shift+C on Mac) to open the DevTools in Inspect Element mode, or toggle Inspect Element mode if the 

### The DevTools window
The DevTools are organised into task-oriented groups in the toolbar at the top of the window. Each toolbar item and corresponding panel let you work with a specific type of page or app information, including DOM elements, resources, and sources.

Elements
Resources
Network
Sources
Timeline
Profiles
Audits

### Inspecting the DOM and styles
The Elements panel lets you see everything in one DOM tree, and allows inspection and on-the-fly editing of DOM elements.You will often visit the Elements tabs when you need to identify the HTML snippet for some aspect of the page
Console.

### Working with the Console
The JavaScript Console provides two primary functions for developers testing web pages and applications. It is a place to:
Log diagnostic information in the development process.
A shell prompt which can be used to interact with the document and DevTools.
You may log diagnostic information using methods provided by the Console API. Such as console.log() or console.profile().

### Debugging JavaScript
As the complexity of JavaScript applications increase, developers need powerful debugging tools to help quickly discover the cause of an issue and fix it efficiently. The Chrome DevTools include a number of useful tools to help make debugging JavaScript less painful.

### Improving rendering performance
The Timeline panel gives you a complete overview of where time is spent when loading and using your web app or page. All events, from loading resources to parsing JavaScript, calculating styles, and repainting are plotted on a timeline.

### JavaScript & CSS performance
The Profiles panel lets you profile the execution time and memory usage of a web app or page. These help you to understand where resources are being spent, and so help you to optimize your code. The provided profilers are:

The CPU profiler shows where execution time is spent in your page's JavaScript functions.
The Heap profiler shows memory distribution by your page's JavaScript objects and related DOM nodes.
The JavaScript profile shows where execution time is spent in your scripts


