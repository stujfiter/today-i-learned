# How to create a web page

2021-07-09 - Korey Earl

Today, you are going to learn how to create your very own web page.  It's not going to be the fanciest web page ever, but hey, everybody's gotta start somewhere so let's get going.

This topic also assumes you know how to create a raw text file. [Find Out How](https://www.computerhope.com/issues/ch001359.htm)

## Step 1
Copy the following code, and paste it into your text editor.
```html
<!DOCTYPE html>
<head>
    <title>My First Webpage</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
```

## Step 2
Save your text file as `first.html`

## Step 3
Open your text file using your web browser. [Find Out How](https://www.w3schools.com/html/html_editors.asp)

You should get a page that looks something like this:

![Hello World Web Page](first-web-page.png)

# How does it work?

## Hyper Text Markup Language (HTML)
When you open a text file with an extension of .html or .htm in your browser, the file is interpreted by your browser and converted into what you see. There are many different web browsers available and each one converts an html file differently. Let's look line by line to learn how most browsers interpret your file.

```html
<!DOCTYPE html>
```
This line tells the browser exactly which standard to use to interpret your text file. In this case it's [__HTML version 5__](https://www.w3.org/TR/html52/).

```html
<head>
```
Is an opening tag that lets the browser know that this is the beginning of the __head(er)__ section of our html document.  A __tag__ is a block of text starting with a "__&lt;__" and ending with a "__&gt;__" symbol.  The browser knows to interpret the next lines as part of the __head__ of your document which is interpreted differently than the __body__ of your document.

```html
    <title>My First Webpage</title>
```
The opening title tag, __&lt;title&gt;__, tells the browser what to name the tab that your web page is shown in.  The other tag, __&lt;/title&gt;__, is called a closing tag. 

Take note of the "__/__" character before the word __title__ in the closing tag. Every letter, number or symbol in an html document is interpretted by the browser and a single character can make a big difference. 

The words between the opening and closing tags are known as text and can be whatever you want as long as it doesn't contain any "__&lt;__" or "__&gt;__" characters. 

Most browsers will limit the amount of text in a tab title so a short descriptive title is important.

```html
</head>
```
A closing head tag that tells the browser we are are finished with the head section.

```html
<body>
```
The opening body tag that begins the __body__ or our web page.  Essentially everything that we want to user to see in the largest section of our web browser.

```html
    <h1>Hello, World!</h1>
```

The __h1__ tag tells the browser to display everything between the tags in a large bold font or __Heading__.  There are six levels of headers, __h1__ being the largest, __h6__ the smallest.  To see what it looks like copy this code into your page just underneath the existing __h1__ tags so your file looks like [this](first-headers.html) and refresh your browser.

```html
    <h2>h2 Hello, World!</h2>
    <h3>h3 Hello, World!</h3>
    <h4>h4 Hello, World!</h4>
    <h5>h5 Hello, World!</h5>
    <h6>h6 Hello, World!</h6>
```

You should now see a page that looks similar to this
![Page with Headers](first-headers.png)
