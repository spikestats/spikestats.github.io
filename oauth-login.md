Launching Spike Stats

<html>
<head>
    <meta charset="utf-8">
    <title>Spike Stats Login</title>
</head>
<body>
    <script type="text/javascript">
        var openApp = function() {
            var url = window.location;
            window.location.replace('spikestats://' + url);
        };
        
        setTimeout(function() { openApp(); }, 500);
       
    </script>
</body>
</html>
