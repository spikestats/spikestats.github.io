Launching Spike Stats

<html>
<head>
    <meta charset="utf-8">
    <title>Spike Stats Login</title>
</head>
<body>
    <script type="text/javascript">
        var iOS = function() {
            return [
                'iPad Simulator',
                'iPhone Simulator',
                'iPod Simulator',
                'iPad',
                'iPhone',
                'iPod'
              ].includes(navigator.platform)
              // iPad on iOS 13 detection
              || (navigator.userAgent.includes("Mac") && "ontouchend" in document)
        }
        
        var openApp = function() {
            var url = window.location;
            window.location.replace('spikestats://' + url);
        };
        
        
        if (iOS()) {
        
        
        } else {
            
        openApp();
        }
        
        
    </script>
</body>
</html>
