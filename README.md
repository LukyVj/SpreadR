SpreadR
=======

A collaborative project of Gitches, from bullgit. More infos soon. 

# Specifications

## Summary 
+ [Project definition](#project-definition)
+ [Aims](#aims)
+ [Interface](#interface)
+ [ToDo](#todo)
+ [Ideas](#ideas)


### Project Definition
The project is about sharing, it will be a chrome (and maybe some other browsers too) extension. 

This extension will allows you to __share__ a webpage, a document, an image or anything else that stand on a webpage, to your Twitter or Facebook friends, directly by message. With a minimum effort. 
It will be lightweight and non obstrusive. 

Some similar extensions already exists, suhc as AddThis, but our extension will be way simple than this kind of "overloaded" extensions. 

### Aims 
The Aim of SpreadR is to share to your __Twitter & Facebook__ friends,  the URL of any webpage, or any other elements on this page (such as images), directly in your browser.
It would be better to make the UX effortless, so if possible, we will display the extension interface once the user let his mouse more than Xseconds, and then a non obstrusive small card will open on a top left / top right corner of the page, with the pre-generated url of the selected element, and a list of your friends on Twitter & Facebook.

Once you're see the list, just click on your friend's profile infos [name/picture], it will pre-write your message, and you'll just have to press ‚[return]+[cmd] (mac),  [return]+[ctrl] (windows), or click on the 'Send ->' button to send your message. 

It will make you save some time, and you'll be able to share the things you loved, with the people you love, instantly. 

### Interface
The interface have to be light, clear and easy to understand. 
With a maximum of visual help, such as colors (Green/Blue to make an action, Red to cancel/remove), and icons. Less text, more pleasure. 

It have to be smaller than 1/3 of the screen, because we want to spread a message of quality, rapidity, and the user have to think that our extension is not overloaded, its just a tiny & light tool. 
It would be better to hide the sharing box, and display it only when the user requires it, with a beautiful and fast fadeIn animation, to let the user think "Oh, its always here, even if I can see it". 
Which is better because this way, the user will not think that we are loading something each time he want it. Its loaded at the beginning, and its display only when the user want to use it.

### ToDo
#### General
+ [ ] Create an empty extension folder.
+ [ ] Get the APIs token of Twitter & Facebook.
+ [X] Started to integrate a first draft, without major design details.
+ [ ] Make bullgit try the first shot. 
+ [ ] Create the final design.
+ [ ] Spread the world.
+ [ ] Give a cookie to Tim Pietrusky once it's done.

#### Design 
+ [ ] Create a logo
+ [ ] Create a common style

#### Developement
+ [ ] Open Twitter application
+ [ ] Open Facebook application
+ [ ] Get to make the messaging system of SpreadR working


### Ideas 
+ On images hovering, a small box with the same style as the main sharing box appear, with the logo of Facebook & Twitter, on click on one of those logos, it grab the URL of the element, and open the Sharing box with prefilled settings (if the user cliked on Twitter, it will display the twitter sharing list, and the same for facebook)


