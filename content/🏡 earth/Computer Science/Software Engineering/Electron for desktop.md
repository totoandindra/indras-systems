#concept-pamphlet 

In Electron, each window displays a web page that can be loaded either from a  `________` or a  `________`.
?
local HTML file, remote web address.
<!--LEARN:G4f49Qo1-->

What is a preload script in Electron?
?
It is a script that bridges Electron's different processes together. These processes include:
- Electron's main process which is a Node.js environment with full OS access. Includes Electron and Node.js built-in modules.
- Renderer processes to run web pages. They do not include Node.js by default for security reasons.
<!--LEARN:QZsFtb6q-->

What is inter-process communication (IPC) in Electron?
?
IPC consists of modules that help communicate between Electron's main and renderer processes. Messages are sent between the web page and the main process. 
<!--LEARN:ppbAz7aQ-->
