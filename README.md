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
    
   <p>Click <a href="http://bit.ly/1tOMKwv">here</a> to see my favorite sea animal.</p>   
  </body>
</html>
```

Will produce a web page that looks like this:

![demo](https://dl.dropboxusercontent.com/u/4042186/lesson1-sample.png)

Check out the [live demo](http://jsbin.com/cejip/1/edit?html,css,output) to experiment yourself.


#Your Story - What's Your Super Power?
Our projects today will be about your imaginary super powers. It will be a whole web page around "if I had a super power, it would be ..."

What would you use your super power for? Does any one have this power? Are there any downsides?

Be creative! Invisibility, flight, speed, and more!

If you would rather tell a different story, you can do that too. Please don't post your full name since these projects will be up on the internet for the whole world to see.

###Getting Started

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


#HTML

Let's learn a few tags to use on your web page! Most of the time you will have an opening tag and matching closing tag with some text in between.

![html tags](https://raw.githubusercontent.com/CoderDojoSV/Medallia-Web-Workshop/master/html%20tags%20pic.jpg)

###Heading Tag
If you type in the HTML window of JS Bin, it will add text to your web page. The `<h1>` tag is used to make the text a heading.

```html
<h1>The Ability to Fly!</h1>
```

Add a heading to your page. Try changing the tag to an `<h2>` (and don't forget to change the closing tag) - what changed? How many heading tags are there?

###Paragraph Tag

If you type out text, it will be displayed all on one line. What if you want to break it up into paragraphs? That's where the `<p>` tag comes in.

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

###Tags Within Tags!

Lists are a little tricky because there is one tag within another one. Notice that the `<ul>` tag comes first and that there are `<li>` tags within it, before the closing `</ul>` tag. This can be used other places too!

Try adding these tags to your page to see what they do: `<strong>`, `<em>`, and ` <u>`. Remember, they can be within other tags. 

```html
<p>Today, I'd like to tell you about the <u>super power</u> I would like to have the most.</p>
<p>I would choose the ability to <strong>fly!</strong></p>
```

###Image Tags
This story would be a lot more interesting with pictures! Adding a picture to our story is simple, we just use the `<img>` tag and tell it where our image is.

The `<img>` tag has an attribute called `src` and this is where we tell it the url to the image we want to use in our story. Here is an example `<img>` tag (notice that you don't need a closing tag this time):

```html
<img src="http://f.cl.ly/items/2f473l1d233S0S1k3J3d/dogs-playing.jpg">
```

What if the image is too big for your page? You can tell it to be a certain size:

```html
<img src="http://f.cl.ly/items/2f473l1d233S0S1k3J3d/dogs-playing.jpg" width="350px">
```

Add some images to your web page that have to do with your super power! Make sure any Google Images Searches have SafeSearch on.

###Link Tags

One of the things that makes web pages so amazing for telling stories is you can **link** things together with other web pages on the internet and it is really easy to do!

The `<a>` tag has an attribute called `href` and we will set that attribute equal to the url of the web page we want to link to. Here is an example where I link the word Poodles to the web page about Poodles on Wikipedia:

```
<a href="http://en.wikipedia.org/wiki/Poodle">Poodles</a>
```

Add a link to your web page. Is there another super hero that has that power? Link to a website about them!

###Finish Your Web Page

There are more HTML tags to try, but we now have the skills to make an exciting web page. Complete the content about your super power and we will learn some CSS to make the page look better!


#CSS

Next we are going to learn about [Cascading Style Sheets](http://en.wikipedia.org/wiki/CSS),
more commonly known as CSS. We are going to use CSS to improve the _look
and feel_ of our stories.

### What is CSS?

CSS is a language that can be used to describe how HTML is supposed to look.
The important distinction here is that HTML structures the content,
while CSS controls how it looks.

Let's look at some CSS:

```css
body {
  font-family: Arial;
  background-color: #FF6BC4;
}
```

If you paste the above code into the CSS panel in JS Bin, what changes about your website? You might have to click the CSS button on the top of the JS Bin page to show the CSS panel. 



### How CSS Works

We can get an idea of what's happening by looking at each line of the CSS.

* For all ```<body>``` tags
    1. Use ```Arial``` as the font
    2. Set the background color to ```#FF6BC4``` (A ***hex color***. More on this later)


CSS follows a basic pattern. First, we select the HTML elements we want to
change the look of. Then, we say what aspects of their look we want to change.
Take this snippet for example:

```css
body {
  font-family: Arial;
  background-color: #FF6BC4;
}
```

We are selecting all ```<body>``` tags (We only have 1),
then saying we want to modify the font, background color, and foreground color.

The part that selects the tags is called the **selector**, and each modification
is called a **declaration**. A combination of a selector and any number
of declarations is called a **rule**. A CSS file can contain as many rules as
we want.

Let's break down the concepts of **selectors** and **declarations**.

### Selectors

So far we have seen an example selector for all body tags. How can you make a selector for all paragraph tags? Add it to your project, making the paragraphs have a different background color!

CSS also allows us to be much more flexible about targeting HTML elements to modify. If you only want to select one paragraph on your page, but not all of them, you can do that using **classes** and  **IDs**. Ask a mentor if you want to see how!


### Declarations

Declarations are the style modifications we apply in each CSS rule. There are two parts to each declaration: the **property** and the **value**. The pattern is:

```property: value;```

There are an amazing number of options for declarations in CSS - you can do just about anything you want! But let's start with just a few. Can you add the following declarations to your page?

```
font-family: Arial;
text-align: center;
color: yellow;
background-color: black;
```

###Making Your Own Colors

There is a simple way to do colors in CSS, simply by typing in the color:

```background-color: green;```

But there are many more colors that we don't have names for. As we saw in the earlier example, it used a color #FF6BC4. That is a hex color - it combines red, blue, and green to make a very specific color. It will give you many many more options for colors to use on your web page.

In order to find the hex value for a specific color, go to [Color Picker](http://colorpicker.com/). Select the color you want and copy the hex value from the top of the screen.

![color picker](https://raw.githubusercontent.com/CoderDojoSV/Medallia-Web-Workshop/master/color%20picker2.png)

If you are interested in learning how the computer knows that #FF6BC4 is that specific shade of pink, ask a mentor! It is really cool!

#Putting It All Together!

You have learned the basics for creating web pages! Use your new skills to complete your page. Here is my finished example:

![finished example](https://raw.githubusercontent.com/CoderDojoSV/Medallia-Web-Workshop/master/finished%20example.png)

[Here is the link to my finished code](http://jsbin.com/yedet/2/edit?html,css,output) 

###Make More Web Pages

Great job on your web page today. Don't forget that you can refer back here when you want to create more web pages. You can create them for school projects, as birthday cards for family members, or just for fun!

If you had fun today and would like to keep learning more HTML and CSS, [Codecademy](http://www.codecademy.com/en/tracks/web) has an excellent tutorial. 
