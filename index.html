<!DOCTYPE html>
<html>
<head>
    <title>Shrinivas Electricals</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            text-align: center;
        }

        header {
            background: #ff9800;
            color: white;
            padding: 20px;
        }

        section {
            padding: 20px;
        }

        #chatBox {
            width: 90%;
            max-width: 400px;
            margin: auto;
            background: white;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        #messages {
            height: 200px;
            overflow-y: auto;
            text-align: left;
            margin-bottom: 10px;
        }

        input {
            width: 70%;
            padding: 8px;
        }

        button {
            padding: 8px;
            background: #ff9800;
            border: none;
            color: white;
            cursor: pointer;
        }

        button:hover {
            background: #e68900;
        }
    </style>
</head>

<body>

<header>
    <h1>Shrinivas Electricals ⚡</h1>
    <p>Nanded | 11 AM - 9 PM</p>
</header>

<section>
    <h2>Our Products</h2>
    <p>Fans | Mixers | Wires | LED Bulbs | Switch Boards | Pipes | Electric Iron | Batteries</p>
</section>

<section>
    <h2>Ask Our Assistant</h2>

    <div id="chatBox">
        <div id="messages"></div>
        <input type="text" id="userInput" placeholder="Ask something...">
        <button onclick="sendMessage()">Send</button>
    </div>
</section>

<script>
function sendMessage() {
    const input = document.getElementById("userInput");
    const message = input.value;

    if (!message) return;

    const messagesDiv = document.getElementById("messages");

    messagesDiv.innerHTML += "<p><b>You:</b> " + message + "</p>";

    fetch("https://YOUR-RENDER-URL.onrender.com/chat", {
        method: "POST",
        headers: {
            "Content-Type": "application/json"
        },
        body: JSON.stringify({ message: message })
    })
    .then(response => response.json())
    .then(data => {
        messagesDiv.innerHTML += "<p><b>Assistant:</b> " + data.reply + "</p>";
        messagesDiv.scrollTop = messagesDiv.scrollHeight;
    });

    input.value = "";
}
</script>

</body>
</html>
