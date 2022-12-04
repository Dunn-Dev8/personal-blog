# Webmkr.py The python Site Generator Docs
## Purpose 
Webmkr.py is a Static website creator, for making simple blog or personal sites. This guide will show you how to go from having no website at all, to having a simple easy to maintain website.
## Dependencies
Things you will need before you start.
- Python3
- Markdown Package from PIP (Python's Package Manager)
	- https://pypi.org/project/Markdown/

On most linux Distributions, Python3 is installed already. 

## Install and Breakdown of how Webmkr.py Works
To install and get started with Webmkr you will need to 
clone the github repo. - `git clone https://github.com/Dunn-Dev8/Webmkr.py` 

![File Browser With Repo source files in it](https://i.postimg.cc/bNQgG8tC/File-Browser.png)
Go into the newly download directory, and have a look around.

### The Breakdown

##### The Apache folder is for hosting your Website with Apache, to try this yourself.

Go into the Apache Folder
Run `chmod +x install.sh`

Then Run `./install.sh`

This will set up an Apache server with your Website on it
#### Note: The install Apache script might not work on any Non-Debian Based linux Distros
##### The Markdown Folder is for all of your Websites posts.
Websites using Webmkr will use Markdown to write all of the blog articles (also what this post is being written in). In the next part we will go more in depth about this one.
##### Index.html
The folder that the website hoster will look for when trying to fetch your website.
##### home-theme.css
The theme for your websites homepage (This will be discussed later on in the docs).

## Making First Post
Like mentioned before Webmkr uses markdown, a "Language" that will tell Webmkr how you want your Blog Post to look.

To write a markdown file, you can use a text editor that was made for writing markdown, the one I am using is a website called _stackedit.io_ (https://stackedit.io/app#).
[![stackedit.png](https://i.postimg.cc/MKNc8jTg/stackedit.png)](https://postimg.cc/jL6qH2yh)

To get started make a new file in the **Markdown Folder** and make sure it ends with .md
You might be wondering "Well how do I write Markdown".

Here is an example.
[![markdown-cheatsheet.png](https://i.postimg.cc/FHKQGPN4/markdown-cheatsheet.png)](https://postimg.cc/jLB9S4Dg)

After you have written your markdown and are ready to upload to your website go to the root directory and run.
[![termalmakingmarkdown.png](https://i.postimg.cc/q7fjgRm5/termalmakingmarkdown.png)](https://postimg.cc/4Y5zSJR6)
And their you have it your first post on your website. Run the index.html in your browser and navigate to your post.
[![makingapost.png](https://i.postimg.cc/R0y6v6XW/makingapost.png)](https://postimg.cc/rdGFJm6T)

## Change Theme
Your theme will be located in two places. The home-theme.css located in the root of your project and also in the posts folder. This was done to separate your posts look from your home pages. 

If you look before you will see that the list items where not formated properly and where black instead of white. Lets fix that for an example.

Navigate to your Posts folder and edit the Theme.css

In here we will add `li{color#CFCFCF}`
[![editing-css.png](https://i.postimg.cc/J09PJzr0/editing-css.png)](https://postimg.cc/gLHVbd6b)
Now go back to the webpage and you will see the list is now white.

To learn more about CSS go to 
https://www.codewithharry.com/blogpost/css-cheatsheet/
or
https://www.w3schools.com/css/
## Change Favicon
A favicon is the small little icon that appears inside the tab of your browser. By default the favicon for your webmkr site is the python icon. 

But that is boring, So let's change that. 

Firstly you will need to know that a favicon is stored inside a .ico file or an Icon File, there is a website you can use to turn any image into an icon.
#### Note: favicon will need to be 16x16
Go to the website https://cloudconvert.com/png-to-ico and convert your chosen image to a ico file, I chose the linux Penguin.

Rename the .ico file to favicon.ico, and move it to the root of the project file to replace that old python logo.
[![iconchange.png](https://i.postimg.cc/gJM61S1P/iconchange.png)](https://postimg.cc/hzdjdrSC)
[![fileicon.png](https://i.postimg.cc/Y9SvNN0D/fileicon.png)](https://postimg.cc/sBtfshp5)

## Change Contact Details
So, when someone visits your amazing website and wants to get in contact with you it is useful to have that information on your website. 

the Contact.html page is where you can do this, simply open the file in your preferred text editor and then replace the details with your own.
[![editing-contact.png](https://i.postimg.cc/CLQxBvZz/editing-contact.png)](https://postimg.cc/Czbg9ssg)

## Editing Homepage
Same principle as before can be done for the Homepage. It will really help to know html, so get learning.


