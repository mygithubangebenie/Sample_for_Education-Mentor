### course objectives: 
By the end of the course, students will be able to: create a page in html and style it. Add JS in the html page and make it look good.install ruby envirnoment  Deploy a project with ruby on rails and store a project on the github.



-----------------------------------Course development--------------------------

# HTML Introduction 

## definition:
  ```Html is Hypertext Markup Language, a standardized system for tagging text files to achieve font, colour, graphic, and hyperlink effects on World Wide Web pages.``` or HTML is the language used to create webpages.

## What is a web page?
  A web page or webpage is a document, commonly written in HTML, that is viewed in an Internet browser. A web page can be accessed by entering a URL address into a browser's address bar. A web page may contain text, graphics, and hyperlinks to other web pages and files.

## How does it work?
  To create html page or file there are several things like source code editor if your're using microsoft windows you have to use Notepad++ for linux you might use VScode or any editor with your wishes.

  `<!DOCTYPE html>` declaration defines that this document is a html document
  `<html>` element is the root element of html page
  `<head>` element contains meta information about the html page
  `<title>` element specifies a title for the HTML page
  `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists
  `<h1>` element defines a large heading
  `<p>` element defines a paragraph 
  `<br>` break lines
  `<a> </a>` These are tags, the content that falls between the opening and closing tags is the content of that element. An anchor link. 

# Example:
`<DOCTYPE html>`
`<html>`
`<head>`
`<title>Website Title</title>`
`</head>`
`<body>`

`<h1>` Hello This is my first Heading`</h1>`
`<p>`Hey , Uzayisenga Amina is the cutetest girl`<br>`I would like to share with you my first paragraph.`</p>`

`</body>`
`</html>`


## What a browser does?
  A web browser helps us to load to access the internet, like web browser is a software application for accessing information on the World Wide Web. www

## Slow loading pages
  Is when there are heavy code like Increased code density, here we should write meaningful code which are neat.

##  Where did HTML come from?
  Addison Wesley Longman had said "1989: Tim Berners-Lee invents the Web with HTML as its publishing language. The World Wide Web began life in the place where you would least expect it: at CERN, the European Laboratory for Particle Physics in Geneva, Switzerland." 
  Ref: https://www.w3.org/People/Raggett/book4/ch02.html

## The World Wide Web Consortium

  The World Wide Web Consortium (W3C) is an international community that develops open standards to ensure the long-term growth of the Web.

## The importance of standards
  Why are these standards important to web designers and web users? Because they ensure that the web works equally well for everyone, regardless of their location or technology. In particular, World Wide Web Consortium standards for Extensible Markup Language and Cascading Style Sheets  ensure that every website will function the same on any browser

## Terminology 
   In this lesson, you will learn some basic HTML terminology. HTML is the language used to create webpages. HTML stands for Hypertext Markup Language. HTML documents written with this text (or coding) tell browsers how to interpret and display the data.

## Quiz
   Create one page of web, with title heading and body which will be diplaying your address  info with names. 
### Thank You
  

------------------ ## CSS Introduction -------------------------------------

## CSS
  CSS in full words is Cascading Style Sheets have made to be used to style and lay out web pages.

## Box Model
  The CSS Box Model All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

## Positioning
  Positioning allows you to take elements out of the normal document layout flow, and make them behave differently; for example sitting on top of one another, or always remaining in the same place inside the browser viewport. ... To learn how CSS positioning works.Eg: top: 30px; left: 30px;

## 
   We called it responsive to web design when you use CSS and HTML to resize, hide, shrink, enlarge, or move the content to make it look good on any screen and be visible to all devices. Eg: You can add this line in your html file like <meta name="viewport" content="width=device-width, initial-scale=1.0"> make it responsive.

## Debugging CSS Layout Issues
   Sometimes when writing CSS you will encounter an issue where your CSS doesn't seem to be doing what you expect. Perhaps you believe that a certain selector should match an element, but nothing happens, or a box is a different size than you expected.


## Display Property
   The display CSS property groups whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex. Formally, the display property groups an element's inner and outer display types. Eg: 
   .container {
     display:  [ <display-outside> | <display-inside> ] | <display-listitem> | <display-internal> | <display-box> | <display-legacy> ;
     }


---------------------------## JS ------------------------------------------

## JS Introduction

  JS in full is JavaScript,it is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything that you want to make, I can call it It's a magic.

  JavaScript can be implemented using JavaScript statements that are placed within the <script>... </script> HTML tags in a web page, document.write and it contains variables as var

## General 
   1. *It Stores useful values inside variables.*
   1. *It does Operations on pieces of text.*
   1. *And Running code in response to certain events occurring on a web page*

## Core

The Core JavaScript Framework or "CoreJS" is a client-side JavaScript library which provides tools for creating object-oriented and event-driven JavaScript code.CoreJS'JavaScript framework consists of two JavaScript files: Core. js provides fundamental JavaScript core langauge extensions, including: Core.

### JavaScript Core Concepts

 1. High-level
 1. Garbage-collected
 1. Prototype-based
 1. Multi-paradigm
 1. Dynamic
 *You can find full information about Javascript Core concepts via this*
  "https://dev.to/jasterix/5-javascript-core-concepts-you-should-understand-210h"
  Done By: Jasterix 
  Published:Nov 29, 2019
  Read on :14November, 2020

## Browser Object Model

  The Browser Object Model (BOM) in JavaScript includes the properties and methods for JavaScript to interact with the web browser. BOM provides you with a window objects, for example, to show the width and height of the window. It also includes the window. screen object to show the width and height of the screen.

  Eg:'DOCTYPE html>
<html>
   <body>
      <script>
         document.write("Screen width: " + screen.width);
         document.write("<br>Screen width: " + screen.width);
      </script>
   </body>
</html>


## What is an Event ?
  JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

  When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window

  Eg:
  <html>
   <head>   
      <script type = "text/javascript">
         '--
            function sayHello() {
               alert("Hello World")
            }
      </script>      
   </head>
   
   <body>
      <p>Click this button and see result It's magic</p>      
      <form>
         <input type = "button" onclick = "sayHello()" value = "Say Hello" />
      </form>      
   </body>
</html>
The button will will bring a pupop which say *Hello World*

## Document object 

A Document object represents the HTML document that is displayed in that window. The Document object has various properties that refer to other objects which allow access to and modification of document content. This hierarchical structure applies to the organization of objects in a Web document. We have Window object,Document object, Form object, Form control elements. Here there is a format od document object compatibility

    Eg: if (document.getElementById) {
          } else if (document.all) {
        } else {
    }

## Data Retrieval 
  Data retrieval is the way of fetching data from diffrent sources either with api or can fetch information from a database with AJAX.

*HTML Code* 
  <form><br>
  Enter your First Name: <input type="text" id="firstname"/><br><br>
  Enter your Last Name: <input type="text" id="lastname"/><br><br>
  <input type="submit" value="Submit" onclick="formdata()"/><br>
  </form>

*Javascript Code*

  <script>
  function formdata() 
  {
  var firstname1= document.getElementById("firstname").value;
  var lastname1= document.getElementById("lastname").value;
  document.writeln("<h1>Confirmation Page</h1><br>");
  document.writeln("Thank you for completing this form.<br><br>");
  document.writeln("The first name you entered is " + firstname + "<br>");
  document.writeln("The last name you entered is " + lastname);
  }
 </script>

   The Javascript code extracts the information from the form field by the id tags of the text boxes, which in this case are firstname and lastname. It takes the value of these id elements by the .value extension. Once it has the values of these text boxes, we then use document.writeln() functions to display the following lines of information.



-------------------## Ruby--------------------------------------------------

## Ruby
### What is Ruby

  Ruby is a dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.
  Ruby is an interpreted, high-level, general-purpose programming language. It was designed and developed in the mid-1990s by Yukihiro "Matz" Matsumoto in Japan.
  Source:https://en.wikipedia.org/wiki/Ruby_(programming_language)

### Install ruby On Your Devices
To install Ruby from the default Ubuntu repositories, follow these steps:
1. sudo apt update
1. sudo apt install ruby-full
1. ruby --version
## Installing Ruby using Rbenv
1. sudo apt update
1. sudo apt install git curl libssl-dev libreadline-dev zlib1g-dev autoconf bison build-essential libyaml-dev libreadline-dev libncurses5-dev libffi-dev libgdbm-dev
1. curl -sL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-installer | bash -
1. echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
1. echo 'eval "$(rbenv init -)"' >> ~/.bashrc
1. source ~/.bashrc
1. rbenv install 2.5.1
1. rbenv global 2.5.1
1. ruby -v
  OutPut: ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-linux]

### ruby command-line tools

1. ruby -e "puts RUBY_VERSION"
1. -e *this make command line for ruby run*
1. -h, --help *this stands for standard help flags*
1. dfm -h
1. Usage: dfm [options] [path]
Defaults: dfm -xd ./
    -f, --filters FILTERS            File extension filters
    -x, --duplicates-hex             Prints duplicate files by MD5 hexdigest
    -d, --duplicates-name            Prints duplicate files by file name
    -s, --singles-hex                Prints non-duplicate files by MD5 hexdigest
    -n, --singles-name               Prints non-duplicate files by file name

Eg1:
>>help
>> 5+3
=>8
>> "Amina+Uzayisenga"
=> "Amina+Uzayisenga"

Eg2:
x = {"hello" => "world", this: {"apple" => 4, tastes: "delicious"}}
require 'json'
puts x.to_json
# {"hello":"world","this":{"apple":4,"tastes":"delicious"}}
puts JSON.pretty_generate( x )
# {
#   "hello": "world",
#   "this": {
#     "apple": 4,
#     "tastes": "delicious"
#   }
# }


## Ruby Functions

def functionname(variable)
   return <value>
end
Your function can compute values and store them in local variables that are specific to the function. 
def say_hello(name)
   var = “Hello, ” + name
   return var
end

or in single line

def say_hello(name)
   return “Hello, ” + name
end
### To call a function

  function(param1,param2)

  Eg:
  puts say_hello(“Dive”)

## Types and Conversions And Numbers,Strings, and Symbols
   Ruby provides the to_i and to_f methods to convert strings to numbers. to_i converts a string to an integer, and to_f converts a string to a float.
   
   Ruby can convert strings to numbers, objects to strings, strings to arrays, and convert between strings and symbols. It  provides the to_i and to_f

   Eg:
   Let create a a new Ruby program called dive.rb with the following code:
   print "What is the first number? "
   first_number = gets.chop

   print "What is the second number? "
   second_number = gets.chop

   sum = first_number + second_number

   print sum

   Run: $ ruby dive.rb

   Then You can make this number be string by adding this  like: *.to_f*
   # convert strings to numbers
   first_number = first_number.to_f
   
   Create this file file called: DiveIntoCode.rb
   user = "Sammy"
   diveintocode = 100

   print "Congratulations, " + user + "! You just passed " + diveintocode.to_s + " Exam diveintocode during this workout."
   Run: DiveIntoCode.rb

   Create onather file called try.rb

   data = "Avocado,WaterMelon Orange,Apple,Banana,Mango"

   *Convert data to an array by splitting on commas*
    monkies = data.split(",")

   *Sort the monkies alpabetically*
    monkies = monkies.sort!

   *Print out the monkies*
    monkies.each{|monkey| puts monkey }

    Run: ruby try.rb

    Output
     Mango
     WaterMelon Orange
     Apple
     Avocado
     Banana

## Control Flow,Loops,Collections, and Arrays

What is A loop? It is the repetitive execution of a piece of code for a given amount of repetitions or until a certain condition is met. We will cover while loops, do/while loops, and for loops.
Eg:

loop_example.rb

loop do
  puts "This will never stop printing until you click Ctrl + c"
end

Run: ruby loop_example.rb
mentor.rb
i = 0
loop do
  i += 1
  puts i
  break  
  end       
  Run: $ ruby mentor.rb
  # this will cause execution to exit the loop

create file called develop.rb

i = 0
loop do
  i += 2
  if i == 4
    next       
  end
  puts i
  if i == 10
    break
  end
end
Run:$ ruby develop.rb
it will display 
2
6
8
10

# countdown.rb

x = gets.chomp.to_i

until x < 0
  puts x
  x -= 1
end

puts "Done!"

# perform_again.rb

loop do
  puts "Do you want to do that again?"
  answer = gets.chomp
  if answer != 'Y'
    break
  end
end

# conditional_while_loop.rb

x = 0

while x <= 10
  if x.odd?
    puts x
  end
  x += 1
end
# conditional_while_loop_with_break.rb

x = 0

while x <= 10
  if x == 7
    break
  elsif x.odd?
    puts x
  end
  x += 1
end

*I may recommand you to go futher and look more Info about Control Flow,Loops,Collections, and Arrays by reading or search on internet.*



-------------------------## Ruby algorithms-------------------------------


  **Ruby algorithms makes a number of libraries available to make algorithm development easier.

  The algorithm description is front-and-center on the algorithm profile page. Use the description to write a clear explanation of what the algorithm does, what kind of input it takes, and what kind of output the user can expect. Be sure to highlight the various ways your algorithm can be used so that users get a thorough understanding of what types of problems the algorithm solves.

  ## Available Libraries
  Algorithmia makes a number of libraries available to make algorithm development easier.

  The full Ruby language and standard library is available for you to use in your algorithms.

  Furthermore, algorithms can call other algorithms and manage data on the Algorithmia platform via the Algorithmia Ruby Client.

  ## Write your First Algorithm
  The apply() function defines the input point of the algorithm. We use the apply() function in order to make different algorithms standardized. This makes them easily chained and helps authors think about designing their algorithms in a way that makes them easy to leverage and predictable for end users.

  ## Managing Dependencies
  The algorithm we are about to create does not have any dependencies other than algorithmia (which is added by default), but it is important to know how to do this - so for now we’ll add phony just as an example.

  Add this gem inyour gemfile: gem 'phony', '~>2.15.41'

  Algorithmia supports adding 3rd partr.md#publish-algorithm Ruby Gems using a Gemfile, but you don’t need to create the Gemfile file manually. Instead, on the algorithm editor page there is a button on the top right that says “Dependencies”. Click that button and you’ll see a modal window:

  ## I/O for your Algorithms
  Now let’s get started on the hands-on portion of the guide:

  The first algorithm that we’ll create will take a JSON formatted object, which has been passed as input by the user. However, you don’t need to worry about deserializing the JSON; it is done automatically before the call to apply().

  Your algorithm will output a JSON formatted object, which the user will consume via an API call to the algorithm path found at the bottom of the algorithm description page. This path is based on your Algorithmia user name and the name of your algorithm, so if you are “demo” and your algorithm is “TokenizeText”, then the path for version 0.1.1 of your algorithm will be demo/TokenizeText/0.1.1
  ## Error handling with Working with Basic Data Structures




  require 'algorithmia'

def apply(input)
    if input.instance_of?(String)
        raise TypeError, 'Please provide a JSON-formatted Array or Object'
    elsif input.instance_of?(Array)
        return {
            "datatype": "Array",
            "sum": input.reduce(:+)
        }
    elsif input["values"]
        return {
            "datatype": "Object",
            "sum": input['values'].reduce(:+)
        }
    else
        raise TypeError, 'Please provide an Array of "values"'
    end
end

## Algorithm Checklist 
1. Write a Full Description
1. What does the algorithm do?
1. Describe the inputs & expected outputs
1. Link to any papers or external documentation
1. Give It a Tagline
1. Add Tags
1. Include Sample Input
1. Update Pricing
1. Check Permissions & Source Code Visibility

##  Publish Algorithm 
  Once you’ve developed your algorithm, you can publish it and make it available for others to use.

  On the upper right hand side of the algorithm page you’ll see a purple button “Publish” which will bring up a modal

  In this guide we covered how to create an algorithm, work with different types of data and learned how to publish an algorithm.**
 
 Above information about Ruby algorthm was found from https://algorithmia.com/developers/algorithm-development/languages/ruby
 Which was Updated July 28, 2020 by the owner.

For more resources:
  https://algorithmia.com/developers/clients/ruby
  https://algorithmia.com/developers/data
  https://algorithmia.com/developers/api/#introduction
  https://ruby-doc.org/core-2.2.0/



------------------------------# Git / Github--------------------------------

# Git / Github

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. This tutorial teaches you GitHub essentials like repositories, branches, commits, and Pull Requests.

 1. **Install git and create a GitHub account** 
    The first two things you'll want to do are install git and create a free GitHub account
 1. **Create a local git repository** 
    When creating a new project on your local machine using git, you'll first create a new repository (or often, 'repo', for short). To use git we'll be using the terminal.
 1. **Add a new file to the repo**
    Go ahead and add a new file to the project, using any text editor you like or running a touch command.Once you've added or modified files in a folder containing a git repo, git will notice that changes have been made inside the repo
 1. **Add a file to the staging environment** 
    Add a file to the staging environment using the git add command. If you rerun the git status command, you'll see that git has added the file to the staging environment (notice the "Changes to be committed" line). 
 1. **Create a commit**
    It's time to create your first commit! Run the command git commit -m "Your message about the commit" 
 1. **Create a new branch**
    Now that you've made a new commit, let's try something a little more advanced.
 1. **Create a new repository on GitHub**
    If you only want to keep track of your code locally, you don't need to use GitHub. But if you want to work with a team, you can use GitHub to collaboratively modify the project's code.
 1. **Push a branch to GitHub**
    Now we'll push the commit in your branch to your new GitHub repo. This allows other people to see the changes you've made. If they're approved by the repository's owner, the changes can then be merged into the primary branch.
 1. *Create a Pull Request (PR)*
    A pull request (or PR) is a way to alert a repo's owners that you want to make some changes to their code. It allows them to review the code and make sure it looks good before putting your changes on the primary branch.
 1. **Merge a PR**
    Go ahead and click the green 'Merge pull request' button. This will merge your changes into the primary branch.
 1. **Get changes on GitHub back to your computer**
    Right now, the repo on GitHub looks a little different than what you have on your local machine. For example, the commit you made in your branch and merged into the primary branch doesn't exist in the primary branch on your local machine.In order to get the most recent changes that you or others have merged on GitHub, use the *git pull origin master* command (when working on the primary branch).

 1. **Bask in your git glory**
You've successfully made a PR and merged your code to the primary branch. Congratulations! If you'd like to dive a little deeper, check out the files in this Git101 folder for even more tips and tricks on using git and GitHub. 

Resources: Author ,Meghan Nelson
on OCT 1, 2015
Link: https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

or create a new repository on the command line
echo "# t1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/Uzayisenga/t1.git
git push -u origin master

or push an existing repository from the command line
git remote add origin https://github.com/Uzayisenga/t1.git
git branch -M master
git push -u origin master

**create new branch**: git checkout -b nameofbranch
**Change branche**: git checkout nameofbranch















