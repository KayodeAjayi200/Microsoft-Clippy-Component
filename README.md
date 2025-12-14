# 🖇️ Clippy for Power Apps (50th Anniversary Edition)

To celebrate Microsoft’s 50th anniversary, I recreated **Clippy** as a reusable **Power Apps component** that can be added to any app to guide users, share tips, and improve user experience in a fun and interactive way.

## ✨ Key Features

### 📍 Flexible Positioning
Clippy can appear:
- At random positions on the screen  
- In a fixed location  
- At specific **X** and **Y** coordinates  
This makes it easy to guide users through different areas of your app.

### 🧠 Dynamic Content
- Questions, hints, animation choices, and buttons are loaded from a **table of records**
- Content can be updated in real time without changing the app
- **Copilot** can be used to quickly generate or refine Clippy’s messages

### 🖱️ Interactive Behaviour
- Users can click Clippy to hide the text while keeping the character visible
- Button actions are fully configurable by referencing **QuestionID** and **ButtonID** in the `ButtonOnSelect` logic

### 😴 Sleep Mode
When the close button is clicked:
- Clippy goes into a sleep state
- Reappears automatically after a configured duration

### 🎭 Fun Animations
Choose from multiple animations to give Clippy personality:
- `hello`
- `wink`
- `surprise`
- `idle`
- `sad`

## 💡 Why This Exists
Building this Clippy component was a fun experiment that highlighted how a simple, friendly guide can significantly improve user experience. Features like this can help onboard users, explain workflows, and make apps more approachable—especially for new or non-technical users.

---

## 🚀 Getting Started
Import the managed or unmanaged solution into your environment and integrate it with your app.

## 🎥 Demo
[*(Microsoft Clippy Power Apps Component)*](https://youtu.be/xG-NV-djaqg)

## 🤝 Contributing
Contributions, ideas, and improvements are welcome!

## 📄 License
MIT
