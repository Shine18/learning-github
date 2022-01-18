What are javascript events?

Events on the webpage are the most crucial part for a webpage, which help you make the website/page interactive and improve the user experience.
Basically events are when browser or user does something on your webpage. For example

When browser has finished loading the page

When user clicks on a button

When user hovers over a link or any element

How to handle events in javascript

To handle events or do something on any event, you need to register your event handle on an element, by calling addEventListener method on that element. For example,

```var el = document.getElementById('element');
el.addEventListener('click', function(){
    // whatever you want to do here when that element is clicked
    alert("Element clicked");
});
```

I post regularly on my blog now about useful tips and learning guides for newbies.

Tune in here to see more details on javascript event programming: https://10code.dev/javascript/what-are-javascript-events/
