# VibeIsOdd

[![PyPI](https://img.shields.io/pypi/v/vibeisodd.svg)](https://pypi.org/project/vibeisodd/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **"Why use math when you can use AI?"**

VibeIsOdd is the world's most over-engineered, AI-powered odd number detector. Instead of using boring old arithmetic, we ask GPT if your number is odd. Because, why not?

## 🚀 Installation

```bash
pip install vibeisodd
```

Or, for the truly adventurous:

```bash
git clone https://github.com/yourusername/VibeIsOdd.git
cd VibeIsOdd
pip install .
```

## 🔑 Setup

You'll need an OpenAI API key. Set it as an environment variable:

```bash
export OPENAI_API_KEY=your-key-here  # On Linux/macOS
$env:OPENAI_API_KEY="your-key-here"  # On Windows PowerShell
```

## 🤖 Usage

```python
from vibeisodd import vibeisodd

print(vibeisodd(7))  # True (7 is odd, confirmed by AI)
print(vibeisodd(8))  # False (8 is even, AI never lies)
```

### Batch Processing

```python
from vibeisodd import vibeisodd_batch

numbers = [1, 2, 3.0, 4.5]
results = vibeisodd_batch(numbers)
print(results)  # [True, False, True, True]
```

### Example Script

You can also run the included example:

```bash
python -m vibeisodd.example
```

## 🛠 Development

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Set your `OPENAI_API_KEY`
4. Run tests/examples

## 📦 Package Info
- **Version:** 1.0.0
- **Author:** Your Name
- **License:** MIT
- **Repo:** [https://github.com/yourusername/VibeIsOdd](https://github.com/yourusername/VibeIsOdd)

## 😂 Why does this exist?
Because sometimes, you just want to see what happens when you replace a one-line function with a large language model. For science. For fun. For the memes.

## 🧑‍💻 Contributing
PRs welcome! Bonus points for adding even more unnecessary AI.

## 📄 License
MIT
