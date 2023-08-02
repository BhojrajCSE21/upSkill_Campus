# UpSkill Campus
The repository contains the task allocated during the Internship at UpSkill Campus

# URL Shortener

The URL Shortener is a simple web application built using Django, HTML, and CSS that allows users to shorten long URLs into short, easy-to-share links. It provides a convenient way to share long URLs on social media, emails, or any other platform with limited character space.

## Features

- Shorten long URLs to concise, easy-to-share links.
- Customizable short links (if available) for easier recall.
- Click tracking: Track the number of times the shortened link has been clicked.
- Responsive design: Accessible on desktops, tablets, and mobile devices.

## Installation and Setup

1. Clone the repository to your local machine.

```bash
git clone https://github.com/BhojrajCSE21/upskill_campus.git
```

2. Navigate to the project directory.

```bash
cd URL_Shortener
```

3. Create a virtual environment (optional but recommended).

```bash
python -m venv venv
```

4. Activate the virtual environment (optional but recommended).

- On Windows:

```bash
venv\Scripts\activate
```

   - On macOS and Linux:

```bash
source venv/bin/activate
```

5. Install the project dependencies.

```bash
pip install -r requirements.txt
```

6. Perform database migrations.

```bash
python manage.py migrate
```

7. Run the development server.

```bash
python manage.py runserver
```

8. Open your web browser and navigate to `http://127.0.0.1:8000/` to access the URL Shortener.

## Usage

1. In your web browser, open the URL Shortener application.

2. Enter a long URL that you want to shorten in the input field.

3. (Optional) If you want a custom short link, provide it in the "Custom Alias" field. Keep it short and memorable.

4. Click the "Shorten" button to generate the short URL.

5. The shortened URL will be displayed below along with the number of times it has been clicked.

6. Click on the shortened URL to test the redirection.

