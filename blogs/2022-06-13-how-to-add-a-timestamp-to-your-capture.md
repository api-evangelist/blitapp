---
title: "How to add a timestamp to your capture"
url: "https://blitapp.com/blog/how-to-add-a-timestamp-to-your-capture/"
date: "2022-06-13"
author: ""
feed_url: "https://blitapp.com/blog/feed.xml"
---
Customers sometimes ask us how to include a timestamp in the capture or the URL of the web page captured. You can achieve this by injecting Javascript into the target page to add the timestamp and URL directly on the page. In your capture, under Advanced Web Page Options , click on Edit Javascript . You can add the code below: (function() { var d = new Date(); var date = d.toLocaleString("en-US",...
