# webshortcuts

## Purpose
This is a simple, customizable html page that you can customize and store on your computer or on a shared internal server to share with your team to centralize internal and external URLs (or portals).

## Update Log
	0.1.0 9/17/2011 Created
	1.0.0 5/8/2024 Published to Github

## Instructions

### 1 Buttons, Menus, Submenus

The layout of this page is simple. 2 rows, each with 4 buttons. 
  Clicking on a button will hyperlink you to a webpage that is attached to the button. Ideally these would be the most common websites you go to.
  Hovering over a button will show you a menu to hyperlink to other websites OR pop up submenus that you can drill down into for more hyperlinks.
  You can organize and nest the menus/submenus to your liking.
  This page can contain links local to your internal network so you can use it for internal portals that are not visible on the internet.

### 2 Configuration

Configuration is simple as modifying html.

-- Menus & Links & Tooltips
  To create menus, you will be using lists and nested lists. I've included a sample nested list in the code below that you can duplicate.

  `li /li ul /ul
  'href="#"> Menu Item.
  
  In this example, change the href # to the desired URL and update the URL description "Menu Item" to the description of that URL
  To update tooltips, update the on hover 'tooltip' but modifying the 'title' parameter.

-- Pictures
  To update pictures, you can modify the .jpg references to what you have downloaded in your img/ subdirectory.

-- BACKUP!
  It is advised to make a backup of your html file prior to making modifications to it so you can revert.

-- Organization Name, Your name, Last update
   The bottom of this page has <div> where you can add your organization's name, your name, and the last date you updated the page.
   If this is not useful you can delete the entire line or comment it out.

### 3 Customization 

#### Wallpaper
Within the img/ directory, replace "img/wallpaper.gif" with your favorite wallpaper GIF.
I recommend using google images for wallpaper gifs. There are always cool new ones you can find.  1080 resolution is recommended for most monitors.

#### Buttons
Within the img/ directory, replace "img/button1", "img/button2.jpg", "img/button3.jpg, etc with your favorite button in .jpg format.
I recommend finding simple gray icons with 'transparent' backgrounds. You can use google images to find them. There's a filter for transparent "All Types > Transparent"
I've incuded some sample such as phone, network, lock, etc.

#### Security and Code Anecdotes
For security reasons, the author has excluded any scripting language on this software. The goal is a simple frontend html page with NO Javascript, NO VBScript, etc.
The goal is to open the page locally on this machine with or without a network connection. 
This page is meant to be used for managing inhouse links to your team and NOT to be hosted on the internet.

You are welcome to leave feedback and/or contribute to this project.
