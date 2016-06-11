
How browsers work

There are five major browsers used on desktop today: Chrome, Internet Explorer, Firefox, Safari and Opera. On mobile, the main browsers are Android Browser, iPhone, Opera Mini and Opera Mobile, UC Browser, the Nokia S40/S60 browsers and Chrome–all of which, except for the Opera browsers, are based on WebKit.
The browser's main functionality
The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier).
Browser user interfaces have a lot in common with each other. Among the common user interface elements are: 
Address bar for inserting a URI 
Back and forward buttons 
Bookmarking options 
Refresh and stop buttons for refreshing or stopping the loading of current documents 
Home button that takes you to your home page The browser's high level structure
The browser's main components are (1.1): 
The user interface: this includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page. 
The browser engine: marshals actions between the UI and the rendering engine. 
The rendering engine : responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen. 
Networking: for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface. 
UI backend: used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods. 
JavaScript interpreter. Used to parse and execute JavaScript code. 
Data storage. This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem. 

The main flow
The rendering engine will start getting the contents of the requested document from the networking layer. This will usually be done in 8kB chunks. 
After that, this is the basic flow of the rendering engine: 
compilation flow
references
1. Browser architecture 
1. Grosskurth, Alan. A Reference Architecture for Web Browsers (pdf) 
2. Gupta, Vineet. How Browsers Work–Part 1–Architecture 
2. Parsing 
1. Aho, Sethi, Ullman, Compilers: Principles, Techniques, and Tools (aka the "Dragon book"), Addison-Wesley, 1986 
2. Rick Jelliffe. The Bold and the Beautiful: two new drafts for HTML 5. 
