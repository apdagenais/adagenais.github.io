# Flask Portfolio

A Flask-based portfolio website to showcase projects and contact information.

## Features
- Homepage with introduction
- Projects page listing development work
- Contact page with links to GitHub and email

## Technologies Used
- Flask
- HTML, CSS
- Gunicorn (for deployment)

## Installation

### Clone the Repository
```bash
git clone https://github.com/apdagenais/flask-portfolio.git
cd flask-portfolio
```

### Create a Virtual Environment (Optional)
```bash
python3 -m venv venv
source venv/bin/activate  # Windows: `venv\Scripts\activate`
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python run.py
```
Visit `http://127.0.0.1:5000/` in your browser.

## Deployment
To deploy on **Heroku** or **Render**:
1. Create a `requirements.txt` file (`pip freeze > requirements.txt`).
2. Use `gunicorn` as the production server.
3. Follow hosting platform instructions.

## License
MIT License

## Author
Adam Dagenais  
Email: adampdagenais@gmail.com  
GitHub: [apdagenais](https://github.com/apdagenais)  
LinkedIn: [adam-dagenais](https://linkedin.com/in/adam-dagenais)