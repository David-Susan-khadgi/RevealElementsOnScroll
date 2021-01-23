So the whole Section is takes the whole view port which has class of content
the content class has sub element of h2 h3 a and p which are animated using different transition and 
  opacity effects
scroll-out.js does the heavy lifting for us which adds attribute to element of [data-scroll=' in/out ']
  and this is how scroll-out.js keeps tracks of which element is being viewed curently in viewport.
  It basically adds In attribute and animation is triggered and once element goes off the page, the attribute 
  of those element is set of 'out'.
