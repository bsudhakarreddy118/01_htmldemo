 
 Agenda
 -------
 
 HTML5/CSS3 - 2days
 Bootstrap - 1 day
 JS - 2 days
 
 
 Browser  --- HttpRequest  --- Server
            --- HttpResponse<---- 
                (body will contain html page )       
                
                
  parse and render the page and display
  
  DOM - Document Object Model 
        Tree like Structure
        
        html
            --head
                title
                    -- text(Document)
            --body  
 
  HTML - Hypertext Markup Language
  -----
  
  - Markup Language
  - Used to develop web pages
  - used to structure a web page
   
                                        
   
   
 HTML5 - Semantic Tags
 ---------------------
 - Role
 - readability
 
 header, footer, section, article, aside, nav, main,  ...  
  
  CSS 
  ----
   - Cascading Style sheet
   
   inline    - written in the tag
     <h1 style="color: red;">STACKROUTE</h1>
   internal  - use a style tag in the head section
       <style>..</style>
   External  - in a separate file
        style.css and link the css file with the html
  
  selectors:
        tag  - selects all the tags, h1, p
        class - .nameof class,  ex .test 
        id   - #idname,  ex #one  
   
   selector {
       property: value
   }
   
   
        
       h1{
            color: blue;    
       }
        

     <h1 class='test maintitle'>som etext</h1>
          
       .test{
            color: blue;    
       } 
      
       <h1 id='one'>som etext</h1>
        
       #one{
            color: blue;    
       }
       
       
       
       Combinators:
       ------------
       
       h1,#one,.test{...}  --> grouping
       
       section h1{...} --> all descendent h1 of all sections
       
       #main-section h1{...}  --->  all h1 in an element with id as main-section
       
       section > p -----> p child tags of all sections
       
   
   CSS Box Model
   --------------
   
   every element has the following areas
        - content
        - padding
        - border
        - margin
        
        
   Units of measurement in CSS
   ---------------------------
   
   absolute units : px, mm, cm, in, ....
   relative units : em, vh, vw , % .....
   
   whole device height -- 100 vh   (10vh 1/10th of the device height)
   whole device height -- 100 vw
   
   
   Block Elements
        occupy the whole width
         - h1 - h6, p, div, header....
   InlineElements
        occupy the width based on the size
        a, img, span
        
   display: 
    inline
    block
   
   
   Ordered list - ol
   UnOrdered list - ul
   lineitem - li
   
   
   tables
 
    forms
    
        <form>
            <input type=text />  
       <form>
   
    radiobuttons
    checkbox
    select
    textarea
    email
    number
    
    
    
 Create your profile page with parallax effect, fixed header ............
 
 push this in to gitlab with reponame as html_profile_page
 make ghouse as reporter in your repo
 
 
 
 CSS3
    Flexbox layout
    Grid layout
   
   
 floats and position  
   
  FlexBox
  -------
  - single dimensional
  - items will automatically expand/shrink based on available space
  - Responsive
  
  simple - medium pages
  
  
  Grid Layout
  -----------
  - two dimensional layout
  - Elements arranged in both rows as well as columns
  - more finer control of where to lay the item
   
   complex pages
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   Tools
   ------
   VS Code
   Live Server
   Browser
   
   

 

   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
 
