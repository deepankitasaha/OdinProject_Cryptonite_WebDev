To create a link in HTML, we use the anchor element. An anchor element is defined by wrapping the text or another HTML element we want to be a link with an <a> tag.

anchor tag on its own won’t know where we want to link to. We have to tell it a destination to go to. We do this by using an HTML attribute.

An HTML attribute gives additional information to an HTML element and always goes in the element’s opening tag. An attribute is usually made up of two parts: a name, and a value; however, not all attributes require a value. In our case, we need to add an href (hypertext reference) attribute to the opening anchor tag. The value of the href attribute is the destination we want our link to go to.

By default, any text wrapped with an anchor tag without an href attribute will look like plain text. If the href attribute is present, the browser will give the text a blue color and underline it to signify it is a link.

While href specifies the destination link, target specifies where the linked resource will be opened. If it is not present, then, by default, it will take on the _self value which opens the link in the current tab. To open the link in a new tab or window (depends on browser settings) you can set it to _blank.

The rel attribute is used to describe the relation between the current page and the linked document. The noopener value prevents the opened link from gaining access to the webpage from which it was opened. The noreferrer value prevents the opened link from knowing which webpage or resource has a link (or ‘reference’) to it. The noreferrer value also includes the noopener behaviour and thus can be used by itself as well.
The prevention of access that is caused by noopener prevents phishing attacks where the opened link may change the original webpage to a different one to trick users. This is referred to as tabnabbing. Adding the noreferrer value can be done if you wish to not let the opened link know that your webpage links to it.

Links to pages on other websites on the internet are called absolute links. A typical absolute link will be made up of the following parts: protocol://domain/path. 

Links to other pages within our own website are called relative links. Relative links do not include the domain name, since it is another page on the same site, it assumes the domain name will be the same as the page we created the link on. Relative links only include the file path to the other page, relative to the page you are creating the link on. 

Relative links like ./shops/coffee_shop.html are directions from the current room (the museum movie room /museum/movie_room.html) to another room (the museum shop). Absolute links, on the other hand, are full directions including the protocol (https), domain name (town.com) and the path from that domain name (/museum/shops/

To display an image in HTML we use the <img> element. Unlike the other elements we have encountered, the <img> element is a void element. 

Besides the src attribute, every image element must also have an alt (alternative text) attribute.

The alt attribute is used to describe an image. It will be used in place of the image if it cannot be loaded. It is also used with screen readers to describe what the image is to visually impaired users.