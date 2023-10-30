# In class notes 10/30/2023

- If you remember anything about JS you shoukd remember how to use properly use event delegation
- transitions are always added to the starting state and the display and the opacity must be explicitly stated prior to changing them
- () => is the same as function()
- document.getElementById('hide').addEventListener('click', hideKitten); this is called chaining two event listeners together using the document 
- The target is what the event happened to and typicxally is what you want when you call for the event (event.target)
- If you have an event listener on all of the tags then to know which specific tag it happened to is to look for the target 
- toggle works with the classList not the class name 
    - If you dont have it add it if you do have it delete it 