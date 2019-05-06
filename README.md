# Ch_4
-How to make Data and Time and button in Java Script
## 	<body>
            <h1>This is test run</h1>
            <button type="button"
            onclick="alert('Go to the next page.')">
            Click Me!</button>
            <h1>Date  and Time</h1>
<script type="text/javascript">
            now= new Date();
            localtime = now.toString();
            utctime = now.toGMTString();
            document.write("<p><stron> Local time:</strong> " + localtime + "</p>");
            document.write("<p><strong>UTC time:</strong> "+ utctime +
            "</p>");
            hours = now.getHours();
            mins = now.getMinutes();
            secs = now.getSeconds();
            milsec = now.getMilliseconds();
            milsec = now.getMilliseconds();
            document.write(hours + ":" + mins + ":" + secs + ":" + milsec + ":" + milsec);
            document.write("<h2>");

</script>

