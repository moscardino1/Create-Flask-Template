# Flask Vercel Template

This is a basic Flask project structured for deployment on Vercel. The project includes a clean and intuitive layout, high-quality visuals, bold typography, interactive elements, a harmonious color palette, responsive design, unique features, and user-centric navigation.

## Features

- **Home Page**: A welcoming landing page.
- **Contact Page**: A page for users to get in touch.
- **Donate Page**: A page with a USDT QR code for donations.
- **Information Page**: A page explaining how the app works.

## Project Structure
```
project-folder/
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
├── templates/
│   ├── index.html
│   ├── contact.html
│   ├── donate.html
│   └── info.html
│
├── venv/
│
├── app.py
├── requirements.txt
├── vercel.json
├── .gitignore
├── .env
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x
- Vercel CLI

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Create a virtual environment and activate it**:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Flask application**:
    ```sh
    python app.py
    ```

### Development

To test the application locally with Vercel:
```sh
vercel dev
```
Deployment
To deploy the application to Vercel:

```sh
vercel deploy
```
For production deployment:

```sh
vercel --prod
```
Freeze Requirements
To update the requirements.txt file with the current packages:

```sh
pip freeze > requirements.txt
```
## License
This project is licensed under the MIT License.

## Acknowledgments
 - Inspired by modern, responsive CSS designs.
 - Utilizes Tailwind CSS for styling.
 - Incorporates QR code generation for USDT donations.
## Contact
For any questions or feedback, feel free to reach out to us at alessandrocarli90@gmail.com.