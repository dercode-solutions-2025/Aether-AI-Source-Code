# AetherAI Chatbot

AetherAI is a web-based chatbot designed to handle basic conversation logic and user interaction, including name recognition, historical facts, and math expressions.

---

## 🔧 Features

- Name recognition and memory via `localStorage`
- Predefined responses to common questions and topics
- Custom UI with CSS for chat-style appearance
- "Thinking" animation while the bot processes input
- Simple natural language pattern matching

---

## 🖼 HTML Code Snippet

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AetherAI</title>
  <link rel="icon" type="image/jpeg" href="aaaa.jpeg">
  <style>
    /* Paste the CSS from the style block below */
  </style>
</head>
<body>
  <h1>AetherAI</h1>
  <div class="chat-container">
    <div class="chat-box" id="chat-box"></div>
    <div class="input-area">
      <input type="text" id="user-input" placeholder="Type your message here..." />
      <button onclick="sendMessage()">Send</button>
    </div>
  </div>

  <script>
   //Javascript Code Here...
  </script>
</body>
</html>
