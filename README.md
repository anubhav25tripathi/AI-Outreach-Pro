# AI Cover Letter Generator

Generate professional, personalized cover letters using Google Gemini AI. Just enter your job details, skills, and experience—the app creates a compelling cover letter for you.

## Features

- Modern, responsive UI (Tailwind CSS)
- Copy-to-clipboard functionality
- Error handling and loading indicators
- Powered by Google Gemini API

## Getting Started

### Prerequisites

- Python 3.8+
- [Google Gemini API key](https://ai.google.dev/)
- (Optional) [pipenv](https://pipenv.pypa.io/) or `venv` for virtual environments

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/ai-cover-letter-generator.git
   cd ai-cover-letter-generator
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root directory:
     ```
     GEMINI_API_KEY=your_google_gemini_api_key
     ```

### Running Locally

```sh
python app.py
```
- Visit [http://localhost:5000](http://localhost:5000) in your browser.

### Deployment

- The app is ready for deployment on platforms like Heroku using the provided `Procfile`.

## File Structure

```
.env
.gitignore
app.py
Procfile
requirements.txt
templates/
    index.html
```

## Usage

1. Fill in the job title, company name, skills, and experience.
2. Click **Generate**.
3. Copy your generated cover letter and use it in your application!

## License

MIT

## Credits

- [Flask](https://flask.palletsprojects.com/)
- [Google Gemini API](https://ai.google.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
