#Deba.Tech
1. What  is HTML--Hypertext mark-up language
 2. Why is it's important ---> Importance of HTML--Html is importance because it's provided the foundations of buildings websites and webs applications.
It's also provided the basics structure
of a web page,including headings,paragraphs,images and Links.

State the purposed of Html.
purpose of Html
*To creat web pages: Html is used to create web pages that can be displayed in the browsers.
*provide meaning :Html elements provide meaning contents,such as heading,paragraphs,images and Links.

The role of Html.
*The role of Html in web content structure.
   improve Seo. A well structured HTML Document can improved search engine optimization (SEO) by providing a clear structure and content.
   Support accessibility: HTML structure support accessibility features such as screen readers and Keyboard navigation.

*Difference between id and class in Html
   id attribute is a unique identifiers for an element, meaning no two elements in documents can have the same id.
   ids are often used in JavaScript to select and Manipulate specific element.

Class: in using class an element  can have mulitiple classes, separated by space.
   Reusable: A class is a reusable attribute that can be applied to muliple elements.

The semantic elements of html elements and why it's important are:
 <header>: Define the header section of a document or section.
 <nav>: Define the main content section of a document.
 <main>:Define the main content section of related content.
 <footer>: Define the footer section of a document or section of a document or section.
 <section>: Define an independent pieces of content, Such as blog post.

Importance of Semantic Element:
   1: Semantic elements make the html code more readeble and maintanable.
   2: Semantic elements help assitive technologies such as screen readers to  understand the structure and content of web pag.
   3: Semmantic element can improved the user experience by providing a clear and Consistent Structure.

4. Explain the Concepts of Dom (Document object Model).
Concepts of Dom
   HTML Elements are represents as nodes in the Dom,and can be accessed and manipulated using Javascript.
      Dom nodes have properties that can accessed and Modified, Such as inner html and style.
        Dom nodes have methods that can be used to manipulate the node, Such as appendchild and remove Child.


     DOM--> is a Programming that interface for html document.
How does Dom relate to html struture of web page.
   Dom is related to html structure of a web pag:

      1: HTML Parsing: When a web page is loaded, the browser parse the HTML code and create a DOM  representation of the document.

      2.Dynamic manipulation: The Dom allows Javascript to dynamically manipulate the structure and the content of a web pag.

5. what is the purpose of <meta> tag, such as specifying character.
       the purpose of <meta> tag in HTML provides metadata about the document, which is information about the document itself.

5b. Describe the different uses of <meta> tag, such as specifying character encoding and meta descriptions.
      1:Character Encoding--->
         <meta> charaset= "uTf-8">
        .Specifies the character encoding for the HTML document, ensuring proper display of special characters and non-English Language.
      
       2.Meta description
           <meta name="Decription" content=page description">
              provides a brief summary search engine optimization (SEO) and user experience
       3.Keywords
           <meta name= "Keywords" 
              content="Keyword 1,Keyword 2,">
                .Specifies relevents keywords related to the pages contents although it's importance for SEO has decreased over time.

     Redirect and Refresh
       <meta http-equiv="refresh" content="30">
         .<meta http= "refresh"contents="0, url=https://example.com">
            can be used to refresh the page or redirect to another URL after a specifies time.

6.  How do you creat a hyperlink in html
     <a href=""></a>
      example <a href="https://www.example.com">visit Example </a>

The href attribute in html specifies the url of linked resources.
 example of href attributes.
    href="https://www.example.com"
    href="tel:+1234567890"
    href="mailto:User@example.com"

7. different between  inline, block and inline block element in Html

    inline
       Display: Element are displayed on the same line as surrounding content.
           # Width and Height:Do not accept width and height properties.
           # padding & margin: only horizontal 
           #  padding & margin  are respected example;<span>,<a> 


     Block
        Display: Elements occupy the full width of their parent container and start on a new line.
       #width and height: Accept width and height properties.
       #padding and margins: Both horizontal and vertical padding and margins are respected
       e.g: <div>, <p>, <h1>


     inline-block:
       Display:Element are displayed on  the same line as surronding content, but can have a width and height.
       Width and Height: Accept width and height properties.
       padding and margin:Both horizontal and vertical padding and margin are respected.
         e.g often used for navigation menus,images galleries, or any situation  where you want element to sit net to each other but still have
         block like properties.

8a.  <Forms> tag in HTML is used to a form that allows users to  inputs data and submit it to a server for processing.

 8b.  Explain the role of <form> tag in user input and data submission.
         the tel input type in HTML is used to collect phone numbers from users.  

     Roles of tel input Type.
     # Phone number input: The tel input type allows users to enter thier phone number.
     # Validation: Some browsers and devices provides basics validation for phone numbers,such as checking for correct formatting.

     Data Submission:
       When a form with a tel input type is submitted, the phone number data is set to the server along with other from data. The server side script can 
       then process and store the phone number as needed.
      
CSS
1. What is the box model in css and what are it components?
    The box Model in css is a fundamental concepts that describs the structure and layout of html Elements.

    Box Model Conponents.
       #Margin: The space between the element and other elements.
       #Border: The visible outline of the element.
       #padding: The space between the content and the borde.
       #Content: The area where the content of the element is displayed.

 Differences padding & Margin 
   padding is the space between the content of an elements and it'S border.
   Margin is the space between in element and other element.

11. What is css selector and how does it works.
       CSS selectors are pattern used to select the elements you want to style. they can be based on element names,Classes,IDS attributes,and more.
Css selectore
    How css selectors work
      #Pattern matching: Css selectors match patterns in the Html document.
      #Specificity Value that determines which styles are applied when multiple.

   Cascading: Styles are applied the order they are defined,will later style overriding earlier ones.
       
Discribes differents types Selectors
   element: Select elements based on their Html tag e.g h1,p1,div,span(usage h1{color:blue;})

 Class: Select elements based  on their class attributes e.g header,footer,nav,(usage header)
    Id: Select element based on id attributes e.g#Logo,#nav,#header,
    attributes: Select elements based on their attributes. eg [href lang], [data-type],type= "text"] usage [ href lang] font-style:italic
    And how they are used to target html element.

12.What is  Flexbox,and how does it work in css.
     Flexbox is a css layout mode that make easier to designs flexible and responsive layouts.
       How Flexbox works
  1.Flex container: set display ;flex or display: inline-flex on a container element.

 2.flexitems: The direct children of the flex container become flex items.

3.Main axis:The primary axis of  the flex container (horizontal or vertical)

4.Cross axis: The secondary axis of the flex container(perpendicular to the main axis).

12b.Flexbox layout is a css layout mode that allows you to design flexible and responsive layouts.

Flexbox properties
  Justify-content: Specifies the alignment of flex items along the main axis (eg center, space-between)

  align-item:  Specifies the alignment of flex items along the cross axis eg center, baseline,

  Flexdirection: Specifies the direction of  the flex item e.g row, column,

13. What is the difference between position,relative and position absolute in css.
       1.Position: relative positions  an elements relative to it's normal position.
       2.Behaivoiur: The element remains in the document flow, and it's space is preserved
       3.offset:you can use top,right,bottom, and left properties to position  the element from it's normal position.


14. What is the purpose of media queries in Css.
      Reponsive design: media queries helps create a layout that adapt to varoius screen sizes and devices
      Conditional styling: Media queries enables you to apply different styles based on specific conditions, Like screen size or orientation.
      Device targeting: Media queries allow you to target specific devices such as Smartphone,tables,deskptops.
     Example:
    @media (min-width:1200px) {/* styles for larger screens*/}

15. What is css Grid,and how does it different from flexbox?
             Css Grid is a layout system in css that allows you create complex, two-dimensional grid-based layouts.

      Differences of grid & flex css
         Css Grid is two-dimensional,while flexbox is one-dimensional
          Css Grid is better suited for Complex,Flexbox is ideal for simple flexible layouts.

15b. Describe the css grid layouts system and compare it to flexbox explaining when to use each.
          
        Css Grid is a two-dimensional layout system that allows you to create complex grid-based layouts.It provids a powerfull way to control the layouts of element on, Web page.

       Comparision of css Grid & flexbox
          #layout complexity| complex,grid-based layout.
          #item placement | precise control over. 
          #item placement | Dynamic Distribution of items.
 
 uses cases: Responsive design, Complex layouts,grid-based design| simple
     layouts, grid-based designs| simple 
     layouts, flexible designs,

16. What are Pseudo-Classes and Pseoudo-elements in css?
       Pseoudo-classes are used to target specific state of an element such as hover;active,Focus,First child
       Pseoudo-element are used to target specific parts of an element,such as before,after,First-letter,First-line.

  hover:Targets an element when it's hovered over.
  Focus:Targets links that have been visited.

  before---> Targets the Content before an element.
  after----> Targets the Conent after an element.

17. What is difference between var,let, and const in Javasscript?
     var is a keyword used to declare a variable in javascript.
      Let is keyword used to declare varable that brought a significant improvements over  the order var keyword.
      Const is a Keyword used in  declare varables.

17b. Scopes of Javascript.
       Explain the Scooping rules and difference between three keywords for declaring varables.
         Var 
           var has Function scope,meaning it'S accessible throughout the function it's declared in.
                Global Scope:if var is declared outside a funtion,it's attached to the global object (usually window in browser)

Let & Const  
    1.Block scope: Let and Const have block scope,meaing they're only accessible with in block They're declared e.g if,loop,etc.
    2.No global attachment: Let and const declared in the global scope don't attach to the global object.

18a. What is the difference between null and undefined in Javascript.
       null represents the intentional absence or non-existent variables.it's a primitive has no value.

          undefined
            undefined represents an uninitializated or non-existent variables.its a primitive value that indicates avariable has been declared but not assigned a value.

18b.Describes the two types and explain their differences in Javascript.
        Null represents the intentional absence of any object value. and can be assigned to a variable.
        undefined represents and unitialized or non-existent varables,Typically the default value for uninitialized variables.


19a.What are Javascript Function and how do you defined one.
    In Javascript, Functions are reusable blocks of code that perform a specific task.

       Defining aFunction:
    Function Declaration
        Function greet(name) {console.log}('Hello,${name}!)};
       
    Function Expression
      Const greet =Funtion (name){console.log('Hello,${name}

To use a Function, you call it by its name and pass required argumements.
  greet('john');//output;
     "Hello,john'

