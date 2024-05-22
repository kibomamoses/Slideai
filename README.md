

# AI Slide Generator

A web application built with Flask that generates PowerPoint presentations using OpenAI's GPT-3 model and integrates images from Pexels.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Presentation Generator is a web-based tool designed to simplify the creation of PowerPoint presentations. Leveraging the power of OpenAI's GPT-3 model, it generates slide content based on a provided prompt, allowing users to focus on the structure and flow of their presentation rather than the content itself.

In addition to text-based slides, the application can optionally include images related to the generated content. These images are sourced from Pexels' extensive library using their API.

## Features

- **Dynamic Content Generation**: Automatically generates slide content based on user input prompt.
- **Template Selection**: Offers a variety of pre-designed templates for presentations.
- **Customization**: Allows users to customize the presentation title, presenter name, and number of slides.
- **Image Integration**: Optionally includes relevant images sourced from Pexels in the presentation slides.
- **Conclusion and References Slides**: Automatically generates conclusion and references slides based on the content.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/presentation-generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd presentation-generator
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Set up your API keys:
   - Obtain an API key from OpenAI and Pexels.
   - Create a `.env` file in the root directory and add your API keys:

     ```
     OPENAI_API_KEY=your_openai_api_key
     PEXELS_API_KEY=your_pexels_api_key
     ```

2. Run the Flask application:

   ```bash
   python app.py
   ```

3. Access the application in your web browser at `http://localhost:5000`.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
