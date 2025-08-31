# AI Website Generator

An intelligent website generator that creates custom websites using OpenAI's GPT models. The tool generates complete website code including HTML, CSS, and JavaScript with modern design patterns and animations.

## Features

- **AI-Powered Design**: Generates professional websites based on natural language descriptions
- **Complete Code Generation**: Outputs fully functional:
  - HTML with Tailwind CSS integration
  - Custom CSS for animations
  - JavaScript with GSAP animations
- **Modern Tech Stack**:
  - Tailwind CSS for styling
  - GSAP for animations
  - Responsive design
  - Performance optimized
- **Interactive Development**: Follow-up questions help refine and improve the generated website

## Installation

1. Clone the repository:
```sh
git clone https://github.com/yourusername/website-generator.git
cd website-generator
```

2. Create a virtual environment and activate it:
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```sh
pip install -r requirements.txt
```

4. Create a `.env` file with your OpenAI API key:
```
OPENAI_KEY=your_api_key_here
```

## Usage

1. Run the application:
```sh
python app.py
```

2. Enter your website description when prompted

3. The generator will create three files:
   - `index.html`
   - `styles.css`
   - `script.js`

4. The generated website will automatically open in your default browser

## Requirements

- Python 3.7+
- OpenAI API key
- Required Python packages:
  - python-dotenv
  - pydantic
  - langchain-core
  - langchain-openai
  - langchain-huggingface
  - langchain
  - grandalf

## Environment Variables

- `OPENAI_KEY`: Your OpenAI API key

## Notes

- The generator uses OpenAI's GPT models through the LangChain framework
- Generated websites include best practices for performance and accessibility
- Interactive mode allows for iterative refinement of the generated website

## License