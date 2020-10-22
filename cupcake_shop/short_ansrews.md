# Short Ansrew Questions

Peter Gibbons
A01020073
midterm for 1620 october 2020
BCIT
## Q1
Git is an open source distributed version control system. Git always you to track changes in the source code during development. This system software is great for working in teams as you can track the changes that have been made.

GitHub is another software that provides hosting for software development but is mainly used to host the Git repositories

The differnces between to two is that Git is the tool to create the repositories while GitHub is what hosts the services of Git

## Q2
A branch in git is a movable pointer that allows you to commit the code. This is extreamly usful for tracking changes that have been made to the code as you start making commits the branch pointer moves forward and you can easily retrace your steps.

To make a new branch and to switch to that particular branch you type
$ git checkout -b [name_of_new_branch ]

## Q3

the http status code you get when a resource is not found is 404. This status code means that the resource you requested does not exist. This type of status code belongs to the 400 class of status codes. Status code 404 does not indicate whether the representation is temporary or permanent.

## Q4

The code written in the body overwrites the coloring in the h2 styling. In this case the color of h2 will be red.

## Q5

A URL contains five parts, scheme, subdomain, top-level domain, second-level domain, and the subdirectory

the scheme of the URL tells the server which protocol to use to accesses the resouce of the website

A subdomain is a portion of URL that comes before the main domain name.

The top-level domain is the suffix of a website and is at the highest level in the hierarchial domain name system eg (.com .net .org)

Second-level domain is directly below top-level domain in the hierarchial domain name system and indicates the organization that registered the domain name eg (midterm.com) midterm would be the second-level domain name and .com is the top-level domain name

Subdirectory is a direcotry that is located within another direcotry. In essence a subdirectory in a website is the folders inside of main folder.

## Q6

HTTP headers allows the client and the server to pass on information, typically a request and a response. three examples of HTTP headers are Content-type. This header is used to indicate the media type, this tells the client what the returned content is. An accept header allows the client to tell the server what type of media is being sent from the client. and request header is where a string is used to autenticate requests.

## Q7

The CSS box model is how the HTML elements are designed and presented. From inside-out the box model the parts are content, padding, border, and margin.

## Q8

The four CSS selectors are descendant selector, child selector, adjacent sibling selector, and the general sibling selector

The Descendant selector matches all of the elements that are descendants of a specific element.
div b{
    color: red;
}

The child selector taragets all of the elemetns that are children of the specific element. 
div > p {
    color: red;
}

Adjacent Sibling Selector allows you to select all of the elements that are adjacent silings of the specific element that are immediately after.
div + p {
    color: red;
}

the gneral sibling selector selects all of the elements that are siblings of the specific element
div ~ p {
    color: red;
}

## Q9

yes, those two paragraphs will appear on separate lines because they are both in different paragraph tags which breaks up lines of text into separate paragraphs

## 10

the first error is that the closing tag for the link is wrong and the second error is that  in the href tag the title should be right beside the bcit.ca it should be
 <a href= "https://bcit.ca" title= "bcit"> bcit site </a>
