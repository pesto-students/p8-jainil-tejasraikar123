Exercise1.1: 

1.When a user enters an URL in the browser, how does the browser fetch the desired result? Explain this with the below in mind and demonstrate this by drawing a diagram for the same. (2-3hours) 

 ![Alt Text]()

 

What is the main functionality of the browser? 

Answer:   

User Interface is defined as everything that you see but you can't manipulate. It works with UI Backend and UI backend is designed to develop basic widgets. 

Browser engine works as a mediator between User Interface and Rendering engine. (Refreshes your page for you). 

Rendering engine is the part which parses HTML, CSS and JavaScript and displays the page. 

The networking layer makes sure when we have https or http request it is loaded. 

JavaScript interpreter is going to interpret the JavaScript. 

Data Persistence stores cookies, local storage, index DB, filesystem etc. 

  

High Level Components of a browser. 

Answer: They are Use Interface, Browser engine, Rendering engine, Networking, JavaScript Interpreter, UI Backend, Data persistence  

Rendering engine and its use. 

 

Parsing 

Translating a document into a structure that  code can use. 

 

Conventional parser: 

To parse CSS and JavaScript  

Unconventional parsers : 

To parse HTML  

 

Feed this to certain code and it will generate result. 

Lexical analysis:  

Syntax analysis : 

Lexer:(Tokenizer)-create token 

Parser-apply the syntax rules  

 

Lexer continuously generates tokens and sends to Parser and parser continuously requests tokens. If it needs it, it uses it or else stores tokens and uses when it requires the tokens.  

Readily available Parsers: 

Flex 

Lex 

Yacc 

Bison 

 

 

 

 

Render Tree 

It is generated while The DOM tree is constructed. Elements in Render tree are called render objects. Render objects rare basically rectangles.  

 

Layout 

It calculates position and size. Most of the time, it's possible to compute geometry in one pass. Recursive process begins at the root object <HTML>  

Dirty Bit system: makes sure browser doesn’t have to render full layout on every interaction. 

Global and incremental layout opposite of Dirty bit, it affects all renders of the browser  

 

 

 

Paint 

Now we need to color the rectangles. The paint method is used to display content on the page. Same Global and incremental painting. 

Painting order  

1.Background color 

2. background image 

3. border 

4. children 

5. outline   

 

 

Exercise1.2:(2-3hours) 

- Use "Lato" font for entire text in UI 

- Use line awesome Icon library for all icons 

- Cattyboard album image URL:https://vif1g.csb.app/src/assets/cattyboard.jpg 

- Icons used in assignment: 

la-bars 

la-home 

la-search 

la-volume-up 

la-user 

la-cog 

la-spotify 

la-soundcloud 

la-play 

la-plus 

la-ellipsis-h 

la-step-backward 

la-step-forward 

la-undo-alt 

la-random 

- Note: Feel free to use any other font library if you wish 

 

Guidelines: 

1.There should be a separate branch created in GitHub for this exercise. 

2.The UI should closely match with the screengrab given as sample. This includes thecolors, fonts, icons, text etc. 

3.Semantic tags should be used for laying out the UI. 

4.There should be one or more Git commits with meaningful commit messages. 

 

 

 

 

 

 