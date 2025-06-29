# 💬 Mesajla — Real-Time AI-Powered Chat Application

Mesajla is a full-stack, real-time chat application with modern features such as AI-generated message suggestions, custom messaging styles, and group or one-on-one communication — all wrapped in a responsive and user-friendly interface. Whether you're chatting casually or professionally, Mesajla adapts with its intelligent reply generation and customizable options.

---

## 🧪 Try the Demo — No Signup Needed!
Explore Mesajla instantly with a ready-to-use test account:

👤 Email:    demo@test.com <br>  
🔑 Password: demo123 <br>
🔑 locked-chats-password: demo123 <br>

Access all features, <br>

Jump right in and experience Mesajla:

---

## 🌐 Live Demo

You can try Mesajla live here:
[Live Demo on Vercel](https://ai-mesajla-v6-deploy.vercel.app/)

No installation needed — just sign up and explore real-time messaging with AI-powered suggestions.

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
    <td><img src="screenshots/25.png" width="500"></td>
  </tr>
</table>

---

## Authentication: Salt & Pepper

Passwords are protected using a secure hashing strategy:

- Each user gets a unique salt
- A global pepper value is kept server-side
- Hash = hash(salt + user_password + pepper)

Thus, passwords are stored as encrypted hashes insead of plain text


---

## Key Features


### Contacts & Groups

- Add friends by email

- Create chat groups

- Email acts as a unique user identifier


<table>
 <tr>
    <td><img src="screenshots/20.png" width="500"></td>
    <td><img src="screenshots/21.png" width="500"></td>
     <td><img src="screenshots/22.png" width="500"></td>
  </tr>
</table>



---

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
###  Unread Message Counter

Stay on top of conversations effortlessly with built-in unread message tracking:

- Real-time unread message count for each chat

- Bold or highlighted chat previews for conversations with unseen messages

- Automatically clears when a user views the chat

- Counter resets only for the user who read the messages — accurate per-user tracking


<table>
  <tr> <td><img src="screenshots/26.png" width="1000"></td> 
</tr> </table>

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
### 📌 Pinning Messages

- Global Pins — Visible to everyone in the chat

- Private Pins — Personal bookmarks visible only to you

<table>
  <tr>
    <td><img src="screenshots/13.png" width="1000"></td>
  </tr>
</table>


<table>
 <tr>
    <td><img src="screenshots/11.png" width="500"></td>
    <td><img src="screenshots/12.png" width="500"></td>
  </tr>
</table>


---
### Media & Files

- Send images, PDFs, text files, etc.

- Preview files without needing to download them (pdf, docx, power point, txt, etc.)

<table>
 <tr>
    <td><img src="screenshots/14.png" width="500"></td>
    <td><img src="screenshots/15.png" width="500"></td>
  </tr>
   <tr>
    <td><img src="screenshots/16.png" width="500"></td>
    <td><img src="screenshots/17.png" width="500"></td>
  </tr>
</table>

---
### UI Customization

- Change chat background color

- Profile photo & name customization


<table>
 <tr>
    <td><img src="screenshots/18.png" width="500"></td>
    <td><img src="screenshots/19.png" width="500"></td>
  </tr>
   <tr>
    <td><img src="screenshots/23.png" width="500"></td>
    <td><img src="screenshots/24.png" width="500"></td>
  </tr>
</table>

---

# 🚀 MESAJLA VERSION 7
Mesajla v7 brings exciting new features that enhance privacy, expression, and visual communication — while keeping the platform fast, friendly, and fun.

--- 

## ✨ New Features in v7

### 🔐 Chat Locking

Users can now lock their individual chats with a password for an added layer of privacy.

- Set a custom password per conversation

- Locked chats stay hidden until the correct password is entered

- Quick unlock UI with password hint support

  
<table>
 <tr>
    <td><img src="screenshots/27.png" width="500"></td>
    <td><img src="screenshots/28.png" width="500"></td>
  </tr>
   <tr>
    <td><img src="screenshots/30.png" width="500"></td>
    <td><img src="screenshots/35.png" width="500"></td>
  </tr>
</table>



### 🖌️ Stylish & Colorful Text (No Commands Needed)

Text formatting is now easier than ever:

- Users can choose styles directly from UI — no need to type /m text commands

- Apply bold, italic, underline, or rainbow effect

- Pick from a palette of custom colors in real time


<table>
 <tr>
    <td><img src="screenshots/31.png" width="500"></td>
    <td><img src="screenshots/32.png" width="500"></td>
  </tr>
</table>


### 🖼️ Self-Vanishing Images

Send disappearing image messages for fun or emotional expression:

- Images vanish after a set time (e.g., 5, 10, or 30 seconds)

- Great for jokes, reactions, or ephemeral content

- Auto-preview countdown timer with UI animation

<table>
 <tr>
    <td><img src="screenshots/33.png" width="500"></td>
    <td><img src="screenshots/34.png" width="500"></td>
  </tr>
</table>




