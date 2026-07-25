# ♟️ FlaskChess

A web-based Chess application built with **Python**, **Flask**, and **python-chess**. This project provides an interactive chess interface where players can play games, validate legal moves, and leverage a robust chess engine for game logic.

---

## 🚀 Features

* ♟️ Play chess in your browser
* ✅ Legal move validation using `python-chess`
* 🎯 Interactive chessboard
* ⚡ Fast Flask backend
* 🔄 Real-time game state updates
* 🧩 Clean and modular project structure
* 📱 Responsive web interface

---

## 🛠️ Technologies Used

* Python 3.x
* Flask
* python-chess
* HTML5
* CSS3
* JavaScript

---

## 📂 Project Structure

```text
FlaskChess/
│
├── flask_app.py          # Main Flask application
├── chess_engine.py       # Chess engine logic
├── templates/            # HTML templates
├── static/               # CSS, JavaScript, images
├── requirements.txt      # Project dependencies
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/FlaskChess.git
cd FlaskChess
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` yet, install the required packages manually:

```bash
pip install flask python-chess
```

### 4. Run the application

```bash
python flask_app.py
```

or

```bash
python -m flask --app flask_app run
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 🎮 How to Play

1. Launch the Flask server.
2. Open the application in your web browser.
3. Move pieces using the chessboard interface.
4. The application automatically validates legal moves.
5. Continue playing until checkmate, stalemate, or draw.

---

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
screenshots/home.png
screenshots/gameplay.png
```

---

## 📈 Future Improvements

* 🤖 AI opponent
* 👥 Multiplayer support
* ⏱️ Chess timer
* 📜 Move history
* ♻️ Undo and redo moves
* 💾 Save and load games
* 🌙 Dark mode
* 📊 PGN and FEN support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Arijit Ghorai**

If you found this project useful, consider giving it a ⭐ on GitHub!
