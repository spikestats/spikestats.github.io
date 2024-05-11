<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spike Stats Account Deletion</title>
</head>
<body>
    <h1>Spike Stats Account Deletion</h1>
    <p>Fill the form below to request your Spike Stats account to be deleted.</p>
    <p>Requesting account deletion will permanently delete your <b>Spike Stats account and related data.</b></p>
    <ul>
        <li>For the <b>Riot ID</b> field, enter your Riot ID such as ValorantPlayer#EUW.</li>
        <li><b>User ID</b> can be found by tapping and holding on the <b>"Delete"</b> button on the <b>Settings</b> page of Spike Stats. When you see the <b>"User Id copied."</b> message, return to this page and paste the value in the <b>User ID</b> field.</li>
        <li>Enter your contact email for the <b>Email</b> field.</li>
        <li>You can use the <b>Message</b> field to provide more info.</li>
        <li>Then, tap on <b>Request Account Deletion</b> button to send your request.</li>
    </ul>
    <p>We will process your request in 7 days. We may contact you via your provided email if more info is required.</p>
    <form action="https://formspree.io/f/mzbnyobv" method="post">
        <label for="name"><u>Riot ID:</u> (e.g. ValorantPlayer#EUW)</label>
        <br>
        <input type="text" id="riotId" name="riotId" required>
        <br>
        <br>
        <label for="name"><u>User ID:</u> (Tap and hold on the "Delete" button in the Settings page of Spike Stats for 2 seconds. After the on-screen message, copy the value in the field below.)</label>
        <br>
        <input type="text" id="userId" name="userId">
        <br>
        <br>
        <label for="name"><u>Email:</u></label>
        <br>
        <input type="text" id="email" name="email" required>
        <br>
        <br>
        <label for="message"><u>Message:</u></label>
        <br>
        <textarea id="message" name="message"></textarea>
        <br>
        <br>
        <input type="submit" value="Request Account Deletion">
    </form>
</body>
</html>
