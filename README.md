<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Telegram Scam Reporting</title>
<style>
  body { font-family: Arial, sans-serif; margin: 40px; background: #f9f9f9; }
  .container { max-width: 600px; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
  h1 { color: #333; }
  label { font-weight: bold; display: block; margin-bottom: 5px; }
  input[type=text] { width: 100%; padding: 10px; margin-bottom: 15px; border: 1px solid #ccc; border-radius: 4px; }
  button { padding: 10px 15px; background-color: #007bff; color: white; border: none; border-radius: 4px; cursor: pointer; }
  button:hover { background-color: #0056b3; }
  .status { margin-top: 15px; padding: 10px; background-color: #eaf4ea; border: 1px solid #b5d6b5; border-radius: 4px; color: #276727; }
  ul { margin-top: 20px; }
  li { margin-bottom: 8px; }
</style>
</head>
<body>
<div class="container">
  <h1>Report Telegram Channel for Scam and Phishing</h1>
  <label for="channel">Telegram Channel Username or Link:</label>
  <input type="text" id="channel" placeholder="e.g. @examplechannel or https://t.me/examplechannel" />
  <button onclick="reportChannel()">Report Channel</button>
  <div id="status" class="status" style="display:none;"></div>

  <h2>Types of Scam Reports Generated:</h2>
  <ul>
    <li>Scam channel</li>
    <li>Phishing channel</li>
    <li>Fraudulent Telegram channel</li>
    <li>Fake Telegram channel</li>
    <li>Impersonation scam</li>
    <li>Cryptocurrency scam</li>
    <li>Investment scam</li>
    <li>Tech support scam</li>
    <li>Bot phishing</li>
    <li>Fake verification requests</li>
    <li>Unauthorized data harvesting</li>
    <li>Malicious link distribution</li>
    <li>Account takeover scam</li>
    <li>Social engineering scam</li>
    <li>Telegram phishing bot</li>
    <li>Fake giveaways or token scams</li>
    <li>Fraudulent investment schemes</li>
    <li>Channel impersonation</li>
    <li>Spam and scam broadcasts</li>
  </ul>
</div>
<script>
  function reportChannel() {
    const input = document.getElementById('channel').value.trim();
    const statusDiv = document.getElementById('status');
    if (!input) {
      statusDiv.style.display = 'block';
      statusDiv.textContent = 'Please enter a Telegram channel username or link.';
      statusDiv.style.color = 'red';
      return;
    }
    // Simulates simultaneous reporting
    statusDiv.style.display = 'block';
    statusDiv.style.color = '#276727';
    statusDiv.textContent = `Reporting channel ${input} for Scam and Phishing...`;

    // Placeholder for where you would integrate real Telegram API/bot report function
    setTimeout(() => {
      statusDiv.textContent =
        `Channel ${input} has been reported for the following issues simultaneously: Scam and Phishing.`;
    }, 2000);
  }
</script>
</body>
</html>
