### jQuery homework
Make an expand/collapse control [something like this](http://jqueryui.com/accordion/#collapsible)  
The HTML structure is arbitrary, but the simpler, the better.  
Tip: doing this task, try to avoid unnecessary jquery code, what can be done with css - should, definetely be done with it.  

Requirements:
- When user clicks on header, content either hides or shows depending on its previous state  
- There can be an arbitrary number of these controls (clicking on header should hide only the content it is related to)
- Make some kind of mark for user to easily spot that he can expand content (commonly used marks are: ►/▼)
- Wrap this functionality as jQuery plugin (so you can call it directly on element)  
  - Think of what can be configurable e.g:  
      - events to trigger this interaction  
      - whether to show or not marks  
      - etc    
  - Think of what should happen when user tries to use your plugin on element with arbitrary html:
    - maybe user want to call it on content only and pass header text in configs
- If you do any additional wrapping and/or dom manipulations, make sure not to break already existing event handlers:
  - Think of a button with some functionality inside of your content block