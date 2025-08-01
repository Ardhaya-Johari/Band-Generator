
# 🎸 Band Name Generator

A quirky and creative **band name generator** built using **Express.js** and **EJS**. With a click of a button, generate fun and random band names from a curated list of adjectives and nouns.

---

## 🚀 Features

- 🎲 Randomly generated band names using adjective + noun logic
- 🌈 Clean UI with custom styling
- 💡 Dynamic EJS rendering and partials (`header.ejs`, `footer.ejs`)
- 🕶️ Built-in dark theme with modern fonts
- 📆 Automatically updates the footer with the current year

---

## 🧱 Project Structure

```
band-name-generator/
├── public/
│   └── styles.css          # Static CSS styling
├── views/
│   ├── partials/
│   │   ├── header.ejs      # Reusable header content
│   │   └── footer.ejs      # Reusable footer with dynamic year
│   └── index.ejs           # Main EJS template with form and display
├── index.js                # Express server and logic
└── package.json            # Project metadata and dependencies
```

---

## 📦 Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Band-Generator.git
cd band-name-generator
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the App

```bash
node index.js
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## ✨ How It Works

- When a user visits the homepage (`/`), a welcome message is shown.
- On clicking **"Generate Name"**, the form hits the `/submit` POST route.
- The server randomly selects an adjective and a noun and renders them on the page.

---

## 🧠 Example Output

```
adorable aliens
abandoned thunder
animated frogs
```

---

## 🙌 Contributions

Feel free to fork this project and submit pull requests to add new features, improve UI, or extend the word lists!

---

## 👤 Creator

**Ardhaya Johari**  
🔗 [GitHub](https://github.com/Ardhaya-Johari)  
📧 ardhayasaxena3897@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/ardhaya-johari-819275321/)

Created with ❤️ by Ardhaya

---
## 📄 License

Licensed under the [MIT License](LICENSE).
