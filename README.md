# py-script-nerdle-game
Utilise pyodide to interpret python-code in the browser

How to play?
https://www.nytimes.com/games/wordle/index.html


Why is this programme of interest?

Normally browsers run JavaScript, here PyScript replaces JavaScript as an alternative. 
The browsers do not have a Python interpreter integrated, but run WebAssembly. 
WebAssembly is a machine code-like language that is translated into machine code by the browser within milliseconds.
Poydide compiles Python code into WebAssembly. In this way, Python code can be executed in a browser.
Nevertheless, nothing can be seen yet. With PŷScript, the browser Python can access the DOM tree and thus change the HTML structure of the
of the page. PyScript also provides additional tags for loading the code and fetches all the required modules.

TL;TR Python code is executed locally without the need for a local installation of Python.
