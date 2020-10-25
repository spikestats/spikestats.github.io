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
        var openNewPage = function() {
            var url = window.location;
            window.open('spikestats://' + url);
        }
        openNewPage();
    </script>
</body>
</html>
