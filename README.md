# Node-JS

Tools needed  : CLI (can use windows powershell in windows)

## V8 Javascript Engine

### processors,machine code, c++

**What is a microprocessor**
* It is a tiny machine which takes electrical inputs and perfor a job.
* We gives instructions to processor 
* It has a languages like : IA 32, MIPS, ARM
                  
**What is Machine Language (Code)**

* Programming language spoken by processsors. Every program we run compiled to into machine code.

**Level of abstraction in modern development**

Javascript -> C/C++ ->Assembly Language -> Machine Code

**Node and ECMAScript**

Node is written in C++ because v8 ( the javascript engine which converts the js code to machine code) is written in C++.

ECMAScript : Standard js is based on ( Needed a standard bcs there are many engines)

Javascript Engine: Pgm that convert js into something the processor can understand. It should follow the ECMAScript std on how the language 
should work and what features it should have.

### V8
1. Googles open source Javascript Engine
2. Implements ECMAScript
3. written in C++ and used in Google chrome browser
4. v8 can run standalone, or can be embedded into any c++ application

javascript ->v8(c++) -> Machine Code
javascript -> My C++ pgm (v8 C++ embedded) -> Machine code

V8 can be embedded in a c++ program. thus allows us to add features to our js code. We can write features in c++ and it to the v8. Like file load ,print etc we can write those in c++ and attach to v8, then in js we can use those features.

This is what node js is

### Node

client server model of computing

client (browser )
we use js.In jquery ,ajax we adding features to the js using the js engine of browser which is a c++ pgm. 
Those things are not in ecmascript spec.

server(c#,ruby,php) 
we can use node js in server, so that we can concentrate in one lang. share libraries of code between client and browser.

**What does js need to manage a server**

* Better ways to organize our code into reusable pieces
* ways to deal with files
* ways to deal with databse
* The ability to communicate over internet
* The ability to accept request andsend response
* A way to deal with work that takes a long time
                  
 **The C++ Core**
 
 Node has the C++ core which makes available lot of featues to the v8 javascript engine. 
 There is javascript core, inside lib folder which uses the c++ objects and work on it. or gives us lot of functions written for us which we encounter in day to day coding.
 
 Node (invented by joyent) depends on v8, v8 is updated by google. so joyent started making different one io.js. and made versions. later they joined with node.
 
 ### Writing real js on node
 
 *  Install node
 * take windows powershell or any CLI
 *  node -v => To check whether node is installed, which version etc.
 * Type node, then you can js there in the shell
 * Or write your own js files like app.js
 * the go to the location , run node app.js to run the file
 
#### Modules Exports and Require

**Module**          : A reusable block of code whose existence does not accidently impact the other code. javascript didnt have this                           before
**Commonjs module** : An agreed upon standard for how code modules should be structured.

**First Class Functions** : Everything you can do with other types you can do with functions.  You can use functions like strings,numbers etc(pass them around, set variables equal to them,put them in arrays and more)

**Function Expression** : Expression is a block of code that results a value. fucntion expressions are possible in javascsript because functions are first class.

Function in js are objects. That sy theses things are possible

**Require** : require(module) to tell the node that we need a module. We cant directly call the functions in the module. it is                         protected. To make available the functions , we can use **module.exports**.

**Objects and Object Literals**

*Name value pair* : A name that is mapped to  a value. The name may defined more than once, but only can have one value in any given                         context . That value may be more name /value pairs.

*Javascript Objects* : A collection of name value pairs.
*Object Literals*    : Name/Value pairs separated by commas, surrounded in a curly brace. This is the easy way to create a js object

**Object** => primitive property
           => Object property
           => function method
     
 *inheritance* : one object gets access to the properties and methods of other object.
 **Prototypal inheritance** : 








































 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
