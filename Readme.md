# Real-Time Whiteboard Collaborator

A real-time collaborative whiteboard where multiple users can draw simultaneously. The changes are reflected instantly across all connected users using **Socket.io**.

## 🚀 Features
- **Real-time Drawing**: Users can draw on the whiteboard, and changes appear instantly for all participants.
- **Multi-User Support**: Multiple users can collaborate on the same board.
- **WebSocket Communication**: Uses `socket.io` to sync the drawing in real-time.
 

## 🏗️ Project Structure
```plaintext
📂 realtime-whiteboard
├── 📂 node_modules         # Dependencies
├── 📂 public               # Static files
│   ├── index.html         # Frontend UI
│   ├── script.js          # Client-side JavaScript
├── index.js               # Server-side logic with Socket.io
├── package.json           # Project dependencies
├── package-lock.json      # Lockfile for dependencies
```

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```sh
git clone https://github.com/yourusername/realtime-whiteboard.git
cd realtime-whiteboard
```

### 2️⃣ Install dependencies
```sh
npm install
```

### 3️⃣ Run the server
```sh
node index.js
```

### 4️⃣ Open in browser
Visit `http://localhost:3000` in your browser to start collaborating.

## ⚙️ How It Works
1. The server (`index.js`) initializes a WebSocket connection using `socket.io`.
2. When a user draws on the canvas, the `script.js` captures the strokes and sends them to the server.
3. The server broadcasts the drawing data to all connected clients.
4. The clients receive the updates and render them in real-time on the canvas.

## 📜 Dependencies
- **Express.js**: For handling server-side requests.
- **Socket.io**: For real-time bidirectional communication.

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

 

---
### 🔥 Start Collaborating Now!
Happy coding! 🎨✨

