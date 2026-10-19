# 🤖 AI Customer Support Chatbot Widget

A modern, highly accurate, and user-friendly **Website Customer Support Chatbot** built with pure HTML, CSS, and JavaScript. 

- **Always Responds in English**: Strict English response enforcement for professional customer communication.
- **Works Out-of-the-Box**: Built-in intelligent customer support knowledge base (services, pricing, refunds, tracking, contact agent, security).
- **Optional Google Gemini AI Integration**: Connect a free Gemini API key in the settings gear (⚙️) to answer **any** question dynamically.
- **Zero Dependencies**: Plug-and-play into ANY website (WordPress, Shopify, React, Next.js, or plain HTML).
- **Features**: Voice typing (Speech-to-Text), Text-to-Speech (🔊), Copy button, sound feedback, quick FAQ chips, responsive mobile layout.

---

## 🚀 How to Run Locally

You can simply open `index.html` in any browser, or run a local server:

```powershell
# Python
python -m http.server 3000

# or Node.js
npx serve .
```

Then visit: [http://localhost:3000](http://localhost:3000)

---

## 🌐 How to Add to ANY Website

To add this chatbot to any existing website, simply copy `chatbot.css` and `chatbot.js` into your website's folder and add these two lines to your HTML:

### 1. In the `<head>` tag:
```html
<link rel="stylesheet" href="chatbot.css">
```

### 2. Right before the closing `</body>` tag:
```html
<script src="chatbot.js"></script>
```

That's it! The floating chat bubble will automatically appear at the bottom-right of your website.

---

## ⚙️ Customization

1. **Business Name & Settings**:
   - Click the gear icon (`⚙️`) in the chat header to change your company name or add your Google Gemini API key.
2. **Editing FAQs & Answers**:
   - Open `chatbot.js` and locate `const KNOWLEDGE_BASE = [...]`. You can add or edit your business questions and answers directly.
