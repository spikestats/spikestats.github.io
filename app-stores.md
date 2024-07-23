Redirecting to App Store...

<html>
<head>
    <meta charset="utf-8">
    <title>Redirecting to App Store</title>
</head>
<body>

<script>
  // Function to detect the user's device
  function detectDevice() {
    var userAgent = navigator.userAgent || navigator.vendor || window.opera;

    // iOS detection
    if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {
      return 'iOS';
    }
    // Android detection
    else if (/android/i.test(userAgent)) {
      return 'Android';
    }
    return 'Unknown';
  }

  // Function to redirect based on device
  function redirectBasedOnDevice() {
    var device = detectDevice();
    if (device === 'iOS') {
      window.location.href = 'https://apps.apple.com/app/id1541123839';
    } else if (device === 'Android') {
      window.location.href = 'https://play.google.com/store/apps/details?id=crocusgames.com.spikestats';
    } else {
      console.log('Device not recognized');
    }
  }

  // Run the redirect function when the script loads
  redirectBasedOnDevice();
</script>
    
</body>
</html>
