# I2ChatGPT

![Python](https://img.shields.io/badge/python-3.8+-blue.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg) ![OpenAI](https://img.shields.io/badge/openai-OpenAI-blue) ![Google](https://img.shields.io/badge/google-Drive-blue)

## 🚀 Overview

I2ChatGPT is a Python-based project that utilizes the OpenAI API to perform text completions and generation tasks. The project is designed to take user prompts and generate responses based on the provided instructions. The code is structured around a main function that uses the OpenAI client to perform chat completions and generate responses.

## ✨ Key Features

* **Text Completion**: I2ChatGPT uses the OpenAI API to perform text completions based on user prompts.
* **Text Generation**: The project can generate text based on user prompts, including lists of made-up book titles and their authors.
* **Response Formatting**: I2ChatGPT can format responses in a specific way, including rewriting instructions in a step-by-step format.

## 🛠️ Technology Stack

### Core Technologies

* Python 3.8+
* OpenAI API
* Google Drive API

### Dependencies

* openai
* google.colab

## 🚀 Quick Start

### Prerequisites

* Python 3.8+
* openai API key
* Google Drive account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/i2chatgpt.git
   cd i2chatgpt
   ```

2. **Set up environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configuration**
   * Set up OpenAI API key in the `openai` library
   * Mount Google Drive using `google.colab.drive.mount`

### Usage

* Run the `main.py` file to start the chat completion and generation process
* Provide user prompts to the `get_completion` function to generate responses

## 📊 Project Structure

```markdown
i2chatgpt/
main.py
requirements.txt
README.md
```

## 🔧 Development

### Running Tests

* No tests are provided in the project

### Code Quality

* No code quality tools are used in the project

## 🚀 Deployment

* No deployment instructions are provided in the project

## 📖 API Documentation

* No API documentation is provided in the project

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

* OpenAI for providing the API used in the project
* Google for providing the Drive API used in the project