# Find Word Different

A simple, interactive web tool that compares two pieces of text and highlights every word that differs between them. Differences are marked by wrapping the words in square brackets `[...]`.

## 🚀 Live Demo

Check out the live demo: [https://www.sieu.io.vn/github/find-word-different](https://www.sieu.io.vn/github/find-word-different)

## ✨ Features

- **Side-by-Side Comparison** – Enter two texts and compare them word by word
- **Difference Highlighting** – Words that differ are automatically wrapped in square brackets `[...]`
- **Real-Time Feedback** – Results are generated instantly when you click the compare button
- **Two Output Panels** – See how each text differs from the other from both perspectives
- **Clean Interface** – Minimal, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📁 Project Structure

```
find-word-different/
├── index.html        # Main HTML file
├── style.css         # Stylesheet
├── script.js         # JavaScript comparison logic
└── README.md         # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/find-word-different.git
   ```
2. **Navigate to the project folder**   
   ```bash
   cd find-word-different
   ```
3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

## 📝 How It Works

1. **Enter the first text** – Type or paste the first piece of text into the first input box
2. **Enter the second text** – Type or paste the second piece of text into the second input box
3. **Click "So sánh" (Compare)** – The tool compares the two texts word by word
4. **View the results** – The two output boxes show the differences:
   - The first output box highlights words in the first text that differ from the second
   - The second output box highlights words in the second text that differ from the first
   - Any differing word is wrapped in square brackets `[...]`

### How the comparison works:

The tool splits both texts into words (preserving whitespace) and compares them position by position. If a word in one text does not match the word at the same position in the other text, it is marked as a difference.

**Example:**

- Text 1: `The quick brown fox`
- Text 2: `The slow brown dog`
- Output 1: `The [quick] brown [fox]`
- Output 2: `The [slow] brown [dog]`

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is open-source and available under the MIT License.
