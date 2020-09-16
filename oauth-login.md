OAuth Login Page

<html>
<head>
    <meta charset="utf-8">
    <title>Twitter</title>
</head>
<body>
    <script type="text/javascript">
        var username = document.location.search.substr(1);
        document.location.replace(
            "standalone" in window.navigator ?
            'twitter:@'+username :              // iOS
            'spikestats://login);    // others
    </script>
</body>
</html>
