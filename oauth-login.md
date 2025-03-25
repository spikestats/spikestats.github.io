---
layout: default
title: Sign In
robots: noindex
sitemap: false
---

Launching Spike Stats...

If Spike Stats doesn’t automatically open:
1.	Open your browser app settings (e.g., Chrome) and tap **Site Settings.**
2.	Ensure **JavaScript** is enabled.
3.	Try signing in again.

<html>
<head>
    <meta charset="utf-8">
    <title>Spike Stats Login</title>
</head>
<body>
    <script type="text/javascript">
    var openApp = function() {
        var url = new URL(window.location); 
        var code = url.searchParams.get('code'); // Get the 'code' parameter from the URL
        if (code) {
            var redirectUrl = 'spikestats://oauth-login?code=' + code;
            window.location.replace(redirectUrl); // Redirect to the app with the desired format
        } else {
            console.error('Code not found in URL');
        }
    };
    openApp();
    </script>
</body>
</html>
