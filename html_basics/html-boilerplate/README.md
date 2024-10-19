DOCTYPE

Every HTML page starts with a doctype declaration. The doctype’s purpose is to tell the browser what version of HTML it should use to render the document. The latest version of HTML is HTML5, and the doctype for that version is <!DOCTYPE html>.

The doctypes for older versions of HTML were a bit more complicated. For example, this is the doctype declaration for HTML4:

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">

However, we probably won’t ever want to be using an older version of HTML, so we’ll always use <!DOCTYPE html>.

HTML element

After we declare the doctype, we need to provide an <html> element. This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it.

lang specifies the language of the text content in that element. This attribute is primarily used for improving accessibility of the webpage. It allows assistive technologies, for example screen readers, to adapt according to the language and invoke correct pronunciation.

The <head> element is where we put important meta-information about our webpages, and stuff required for our webpages to render correctly in the browser. Inside the <head>, we should not use any element that displays content on the webpage.

<meta> : ag with the charset encoding of the webpage in the <head> element: <meta charset="utf-8">. will ensure that webpage will display special symbols and characters from different languages correctly in the browser.

<title> : title of webpage

<body> : all contnent to be displayed within here