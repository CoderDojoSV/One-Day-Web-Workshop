#Medallia Web Workshop

Today we will be learning to make websites using HTML and CSS. No previous experience is necessary, just have fun and be creative! We will be making web pages to help us tell a story that we can show our friends and family.


###Setup
Please create an account at [http://jsbin.com/](http://jsbin.com/). You will need an account in order to save your web page you create today. If you are under 13, grab your parent to help.


###What is HTML?
A web page is made up of many HTML elements, called tags, that are enclosed in angle brackets. These tags tell your web computer what to show.

The paragraph below is an example of how you mark a paragraph in HTML, by surrounding it in opening and closing `<p>` tags.

```html
<p>All web pages on the internet use HTML!</p>
```

###Example - A Web Page About My Favorite Season

This bit of code:

```
<html>
  <head>
  </head>
  <body>
   <h1>My Favorite Season</h1>
   <p>Today, I'd like to share about my favorite season.</p>
   <p>There are four seasons in a year.</p>
   <ul>
    <li>spring</li>
    <li>summer</li>
    <li>fall</li>
    <li>winter</li>
   </ul>
   <p>My favorite season is summer, because I can go to the beach with my family.</p>

   <img src="http://images.pinchit.com/deals/2012/04/16/012292aa53_1334616708_550.jpg" alt="">
    
   <p>Click <a href="http://baytobeachlife.files.wordpress.com/2013/02/male-sealion3-by-chris-parsons.jpg">here</a> to see my favorite sea animal.</p>   
  </body>
</html>
```

Will produce a web page that looks like this:

![demo](https://dl.dropboxusercontent.com/u/4042186/lesson1-sample.png)

Check out the [live demo](http://jsbin.com/cejip/1/edit?html,css,output) to experiment yourself.


###Your Story - What's Your Super Power?
Our projects today will be about your imaginary super powers. It will be a whole web page around "if I had a super power, it would be ..."

What would you use your super power for? Does any one have this power? Are there any downsides?

Be creative! Invisibility, flight, speed, and more!

If you would rather tell a different story, you can do that too. Please don't post your full name since these projects will be up on the internet for the whole world to see.

##Getting Started

Start a new project at [http://jsbin.com/](http://jsbin.com/). The HTML section will look like this:
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
</head>
<body>

</body>
</html>
```

You should delete all of this HTML! We will start with it completely blank.


##HTML Tags

Let's learn a few tags to use on your web page! Most of the time you will have an opening tag and matching closing tag with some text in between.

![html tags](https://raw.githubusercontent.com/CoderDojoSV/Medallia-Web-Workshop/master/html%20tags%20pic.jpg)

###Heading Tag
If you type in the HTML window of JS Bin, it will add text to your web page. The h1 tag is used to make the text a heading.

```html
<h1>The Ability to Fly!</h1>
```

Add a heading to your page. Try changing the tag to an h2 - what changed? How many heading tags are there?

###Paragraph Tag

If you type out text, it will be displayed all on one line. What if you want to break it up into paragraphs? That's where the p tag comes in.

```html
<h1>The Ability to Fly!</h1>
<p>Today, I'd like to tell you about the super power I would like to have the most.</p>
<p>I would choose the ability to fly!</p>
```

Add a couple paragraphs to your web page about your super power.


###List Tags

You can add a list to your story using `<ul>` and `<li>` tags. Here is an example:

```html
<ul>
    <li>Travel anywhere</li>
    <li>No more walking to school</li>
    <li>Visit Grandma and Grandpa whenever I want</li>
    <li>Soar around with birds</li>
</ul>
```

The `<ul>` tag (unordered list) tells the browser this is a list of items. The `<li>` (list item) tags are used around each list item.

Add a list to your web page about the things you would do with your super power. What happens if you change the ul tag to an ol? What do you think that stands for?
