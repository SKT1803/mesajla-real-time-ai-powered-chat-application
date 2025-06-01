# 💬 Mesajla — Real-Time AI-Powered Chat Application

Mesajla is a full-stack, real-time chat application with modern features such as AI-generated message suggestions, custom messaging styles, and group or one-on-one communication — all wrapped in a responsive and user-friendly interface. Whether you're chatting casually or professionally, Mesajla adapts with its intelligent reply generation and customizable options.

---

## Tech Stack

Frontend
- React.js

Backend
- Node.js (API & Socket.IO)
- Python (Flask for AI response engine)

Database & Storage
- MongoDB (chat storage, users, settings)
- Firebase (file and media storage)


---

## Core Pages

- Sign In & Sign Up — Secure entry with salt-paper hashing
- Profile Registration — Configure profile, avatar, display name
- Chat Interface — Real-time messaging with full media support
- Mascot Guided Onboarding — Animated assistant helps you through account setup

<table>
  <tr>
    <td><img src="screenshots/1.png" width="500"></td>
    <td><img src="screenshots/2.png" width="500"></td>
  </tr>
 <tr>
    <td><img src="screenshots/3.png" width="500"></td>
    <td><img src="screenshots/4.png" width="500"></td>
  </tr>
</table>

---

## Authentication: Salt & Paper

Passwords are protected using a secure hashing strategy:

- Each user gets a unique salt
- A global paper value is kept server-side
- Hash = hash(salt + user_password + paper)

Thus, passwords are stored as encrypted hashes insead of plain text


---

## Key Features

### 💬 Messaging
- Real-time 1-on-1 and group messaging

- Message timestamps & unread indicators

- Message color styling with custom CSS values

- Send messages in bold or italic using:

- Or a combination of all


```bash
/m text: <c1> Selam, nasılsın?
/m text: <c2> Selam, nasılsın?
/m text: <c3> Selam, nasılsın?
/m text: <c4> Selam, nasılsın?
/m text: <c5> Selam, nasılsın?
/m text: <c6> Selam, nasılsın?
/m text: <#b68bcc> Selam, nasılsın?
/m text: <b> Selam, nasılsın?
/m text: <i> Selam, nasılsın?
/m text: <rainbow> Selam, nasılsın?  
/m text: <i> <c5> Selam, nasılsın?
```

<table>
  <tr>
    <td><img src="screenshots/7.png" width="1000"></td>
  </tr>
</table>

---
### 🤖 AI Response Suggestions

Toggleable smart replies using an AI trained on:

- 13K+ Turkish conversational samples

- Tagged intents with pattern-response matching

Works by using the latest message as a prompt

Refresh responses as:

- 🔵 Formal

- 🟢 Informal

Can be turned on/off globally or per chat


<table>
  <tr>
    <td><img src="screenshots/8.png" width="1000"></td>
  </tr>
</table>


<table>
 <tr>
    <td><img src="screenshots/9.png" width="500"></td>
    <td><img src="screenshots/10.png" width="500"></td>
  </tr>
</table>


---
### 🤖 AI Response Suggestions

- Global Pins — Visible to everyone in the chat

- Private Pins — Personal bookmarks visible only to you











