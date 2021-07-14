# Debugging and Error Handling  
 it wasn’t uncommon to find script blocks scattered about a page, generating web page content on the fly. To ensure that something showed up even if scripting was turned off, the developers would match the script with a noscript element. This noscript element would provide fallback page content or information. The noscript element has gone out of favor, and is listed as obsolete in HTML5. Now, web developers create the entire page and all of its content without any scripting enabled. Then, and only then, they’ll add script to make the page more helpful, interactive, or even fun.  
 
 ![error](https://bugfender.com/wp-content/uploads/2020/09/Featured-scaled.jpg)  
 
 + To solve the problem, the developer can style the form elements to be displayed by default, and then use JavaScript to turn off the display of some of the elements when the page loads. Based on the web page reader’s actions, form elements will be displayed and hidden as needed. This ensures that the form elements are always available and only hidden when support for scripting is ensured.  
 
 1. Gracefully Handling No JavaScript Support  
 2. Checking for Errors in Functions  
 3. Using an Alert for Simple Debugging  
 4. Catching an Error and Providing Graceful Error Handling  
 5. Initiating Manageable Errors  
 6. Using Firebug with Firefox  
 7. Setting a Breakpoint and Examining Data with Firebug  
 8. Firefox and the Console  
 9. Using IE’s Built-in Debugger  ![--](https://www.oreilly.com/library/view/javascript-cookbook/9781449390211/httpatomoreillycomsourceoreillyimages649973.png)  
 10. Setting a Breakpoint with IE Developer Tools  
 11. Opera’s Dragonfly  
 12. Setting a Breakpoint with Dragonfly  
 13. Turning on Safari’s Development Tools  
 14. Setting a Breakpoint with Safari’s Debugger  
 15. Debugging in Chrome  ![---](https://www.oreilly.com/library/view/javascript-cookbook/9781449390211/httpatomoreillycomsourceoreillyimages650009.png)
 
