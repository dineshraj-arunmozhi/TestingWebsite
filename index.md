
<!DOCTYPE html> 

<head> 
    <title>Home Questionnaire...the GifTastic Sequel!<span id="selection-marker-1" class="redactor-selection-marker"></span></title> 

<!--Segment Analytics.js --> 
<script>
    !function(){var analytics=window.analytics=window.analytics||[];if(!analytics.initialize)if(analytics.invoked)window.console&&console.error&&console.error("Segment snippet included twice.");else{analytics.invoked=!0;analytics.methods=["trackSubmit","trackClick","trackLink","trackForm","pageview","identify","reset","group","track","ready","alias","debug","page","once","off","on","addSourceMiddleware","addIntegrationMiddleware","setAnonymousId","addDestinationMiddleware"];analytics.factory=function(e){return function(){var t=Array.prototype.slice.call(arguments);t.unshift(e);analytics.push(t);return analytics}};for(var e=0;e<analytics.methods.length;e++){var key=analytics.methods[e];analytics[key]=analytics.factory(key)}analytics.load=function(key,e){var t=document.createElement("script");t.type="text/javascript";t.async=!0;t.src="https://cdn.segment.com/analytics.js/v1/" + key + "/analytics.min.js";var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(t,n);analytics._loadOptions=e};analytics._writeKey="iXqFt06oxLQVb1FZYFKQJjYfVW3RWjN9";analytics.SNIPPET_VERSION="4.13.2";
      analytics.load("iXqFt06oxLQVb1FZYFKQJjYfVW3RWjN9");
      analytics.page();
      }}();
</script>
</head> 
<body> 
<h1>What is your favorite place to travel?</h1> 
<p>I am building a directory of the sweetest travel destinations.</p>  
<form name="travel" onsubmit="identify(event)">
     What is your favorite travel destination?
    <input name="destination" required="" size="81" type="text"/> 
    <br><br><br> 
    Any recommendations (cool things to do, places to visit or restaurants to eat)? 
    <br><br> 
    <textarea cols="81" name="details" required="" rows="10">
    </textarea> 
    <br><br> 
    Name: <input name="fullname" required="" size="75" type="text"/> 
    <br><br> 
    Email: <input name="email" required="" size="75" type="email"/> 
    <br><br>
    <input name="submit" type="submit" value="submit"/>
</form> 

    <!--Placeholder for identify and track script -->

</body> 
</html>