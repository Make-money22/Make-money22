<!DOCTYPE html>
<html lang="sw">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promotional Campaign</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        #wheel {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            border: 10px solid #4CAF50;
            position: relative;
            transition: transform 4s cubic-bezier(0.33, 1, 0.68, 1);
            background-image: conic-gradient(#ff0000 0% 16.67%, #00ff00 16.67% 33.33%, #0000ff 33.33% 50%, #ffff00 50% 66.67%, #ff00ff 66.67% 83.33%, #00ffff 83.33% 100%);
        }
        #result-box {
            margin-top: 20px;
            font-size: 1.5em;
            color: #4CAF50;
        }
        .section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <h1>Promotional Campaign</h1>

    <div id="registration-section" class="section">
        <h2>Jisajili</h2>
        <form onsubmit="register(event)">
            <label for="phone">Namba ya Simu:</label>
            <input type="text" id="phone" required>
            <br>
            <label for="email">Barua Pepe:</label>
            <input type="email" id="email" required>
            <br>
            <button type="submit">Jisajili</button>
        </form>
    </div>

    <div id="verification-section" class="section" style="display: none;">
        <h2>Thibitisha Akaunti Yako</h2>
        <form onsubmit="verifyCode(event)">
            <label for="verificationCode">Msimbo wa Thibitisho:</label>
            <input type="text" id="verificationCode" required>
            <br>
            <button type="submit">Thibitisha</button>
        </form>
    </div>

    <div id="payment-section" class="section" style="display: none;">
        <h2>Malipo</h2>
        <form onsubmit="processPayment(event)">
            <label for="name">Jina Lako:</label>
            <input type="text" id="name" required>
            <br>
            <label for="amount">Kiasi cha Malipo (Tsh):</label>
            <input type="number" id="amount" required>
            <br>
            <label for="phonePayment">Namba ya Simu:</label>
            <input type="text" id="phonePayment" value="0616181405" required>
            <br>
            <button type="submit">Fanya Malipo</button>
        </form>
    </div>

    <div class="section">
        <h2>Spin the Wheel!</h2>
        <div id="wheel"></div>
        <div id="result-box"></div>
    </div>

    <script>
        // Include the JavaScript code from the previous response here
    </script>

</body>
</html>
