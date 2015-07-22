# NJSwipe

Javascript Swipe Events

## Installation 
    
### Using with RawGit CDN 
    
    <script src="https://cdn.rawgit.com/joequah1/Javascript-NJSwipe/master/web/js/njswipe-1.0.0.min.js"></script>

For more infomation bout RawGit, please visit [FAQ](https://rawgit.com/faq)

## Definitions

### swiperight

Triggered when user swipe in right direction over the element

### swipeleft

Triggered when user swipe in left direction over the element

### swipeup

Triggered when user swipe in up direction over the element

### swipedown

Triggered when user swipe in down direction over the element

## Usage 

### Swipe Right 

    document.getElementById('swipe_area').addEventListener('swiperight', function(){
        //Scripts
    });
    
### Swipe Left 

    document.getElementById('swipe_area').addEventListener('swipeleft', function(){
        //Scripts
    });
    
### Swipe Up 

    document.getElementById('swipe_area').addEventListener('swipeup', function(){
        //Scripts
    });
    
### Swipe Down 
    
    document.getElementById('swipe_area').addEventListener('swipedown', function(){
        //Scripts
    });

## Demo 

Coming Soon

## References
Currying 
- http://www.dustindiaz.com/javascript-curry/
- http://stackoverflow.com/questions/3358254/this-doesnt-work-when-binding-functions-to-events-inside-a-javascript-class

Javascript Touch Events 
- http://www.javascriptkit.com/javatutors/touchevents2.shtml

Extend addEventListener 
- http://stackoverflow.com/questions/7220515/extending-node-addeventlistener-method-with-the-same-name

Creating and Triggering Events 
- https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Creating_and_triggering_events

Downside of extending the DOM 
- http://perfectionkills.com/whats-wrong-with-extending-the-dom/