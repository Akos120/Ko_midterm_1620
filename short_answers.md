# Short Answer Quesions

Agnes Ko\
A01205739\
midterm for 1620 October 2020\
BCIT

## Q1

Git is an open source version control system. It is a software that will help you to keep track of changes in files you make, and allow you to look back at different versions of the files as you work.

GitHub is a hosting platform for version control. It also allows people to collaborate together on a single file or project. Using Git commands, you can push your version of a file, or changes you made to one, onto a GitHub site repository so that others can see and work on it as well.


## Q2

In Git, Branches are a way for you to make changes to a file, or try out features on it, without messing with your original master file. If something doesn't work or you feel you do not need the change, you can delete the branch. If you would like to implement those changes, you can merge the branch with your master file.

You create a branch by typing commands into Git **- git branch "branch name"**

## Q3 

The http status code you get when a resource is **not found**, is 404, which is under the Client error category. Other status code in the 400 category are 400 Bad request, 401 Unauthorized, 403 Forbidden, and 405 Method not allowed. The 404 status code does not indicate whether it is temporrary or permanent.

## Q4

This styling is incorrect because you have both an inline CSS styling and an internal CSS styling that are overlapping. You have specified the h2 with the id of school, and have an internal CSS that styles it. But you also specified the style inline as well. The h2 will thus be red, because CSS is a cascading style and the last set style will overwrite the previous.

## Q5

Protocol: the first part of the URL, it indicates which protocol the browser must use. The most common ones are **HTTP** or **HTTPS**.

Domain Name: it tells you which Web server is being requested.\
Example - **www.something.com**

Port: this tells you the gate used to access the resources on the web server. You don't usually see this part if the server is using standard ports of the HTTP or HTTPS protocols.\
Example - **:80**

Path: the way to a resource on the Web server.\
Example - **/path/to/somewhere.html**

Parameters: list of key/value pairs separeted with the & symbol. These are extra parameters given to the Web server.\
Example - **?key1=value1&key2=value2**

## Q6

HTTP headers are something used to let the client and server pass information with an HTTP request or response. There are three groups of Headers:\
**General headers** - used in both request and response messages, but don't apply to the content itself. An example of this type are **Date headers**.

**Request headers** - can be used in an HTTP request, and does not relate to the content of the message. An example are **Cookie header**.

**Response headers** - can be used in an HTTP response and does not relate to the content of the message. An example are **Age header**.

## Q7

The CSS Box model are the set of rules of how the elements of HTML are designed and laid out. The different parts of the model are: **Content, Padding, Border, and Margin**.

## Q8

The 4 CSS Combinator selectors are:\
**Descendant combinator** - matches all elements that are descendants of a specified element.\
Example:
```
div p {
    color: red;
}
```
**Child combinator** - selects all elements that are the child of a specified element.\
Example:
```
div > h2 {
    color: red;
}
```
**Adjacent sibling combinator** - selects all elements that are adjacent siblings, which means they have the same parent element and are immediately following the parent.
Example:
```
div + p {
    color: red;
}
```
**General simbling combinator** - selects all elements that are siblings of a specified element.
Example:
```
div ~ p {
    color: red;
}
```

## Q9

These two paragraphs will appear on two separate lines, because they are enclosed by their own `<p>`. This tag stands for paragraph, and each paragraph block will be on its own line.

## Q10

One error, is that the `<img>` tag does not have an alt attribute. This provides an alternative text for the image if it cannot be loaded on the site.\
Another error is that the **"<"** in the link tag after "bcit site" is in the wrong position. It should be right in front of the closing `</a>` tag.