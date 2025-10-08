# 🚀 My Awesome Flask Project

<div align="center">

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A comprehensive step-by-step tutorial for deploying Flask applications to the live web using Vercel**

[🌐 Live Demo](https://flask-app-jade.vercel.app/) • [📺 Video Tutorial](https://youtu.be/miQmOlPF_Gs) • [⚡ Learn Vercel](https://vercel.com)

</div>

---

---

## ✨ Features

- ⚡ **Fast Deployment** - Deploy to Vercel with zero configuration
- 🎨 **Modern UI** - Clean and responsive design
- 🔧 **Easy Setup** - Get started in minutes
- 📱 **Mobile Friendly** - Works seamlessly on all devices
- 🔒 **Secure** - Built with security best practices
- 📊 **Scalable** - Ready for production workloads

---

## 🛠️ Technologies Used

| Technology | Description |
|------------|-------------|
| ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white) | Lightweight WSGI web application framework |
| ![Python](https://img.shields.io/badge/-Python%203.9-3776AB?style=flat&logo=python&logoColor=white) | High-level programming language |
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Markup language for web pages |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Style sheet language |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Programming language for web |
| ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) | Platform for frontend frameworks and static sites |

---

## 📁 Project Structure

```
project-root/
│
├── 📄 app.py                    # Main Flask application
├── ⚙️ vercel.json               # Vercel configuration
├── 📦 requirements.txt          # Python dependencies
│
├── 📂 static/                   # Static files
│   ├── 🎨 css/
│   │   └── style.css           # Stylesheets
│   ├── ⚡ js/
│   │   └── script.js           # JavaScript files
│   └── 🖼️ images/              # Image assets
│
└── 📂 templates/                # HTML templates
    └── index.html              # Main page template
```

---

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.9 or higher
- pip (Python package manager)
- Git

### Installation

Follow these steps to get your development environment running:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/CodingCraftYT/Flask-App.git

# 2️⃣ Navigate to the project directory
cd Flask-App

# 3️⃣ Create a virtual environment (recommended)
python -m venv venv

# 4️⃣ Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# 5️⃣ Install dependencies
pip install -r requirements.txt

# 6️⃣ Run the application
python app.py
```

### Running Locally

Once the application is running, open your browser and navigate to:

```
http://localhost:5000
```

🎉 **Congratulations!** Your Flask app is now running locally.

---

## ⚙️ Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your-secret-key-here
```

### Vercel Configuration

The `vercel.json` file contains deployment settings:

```json
{
  "version": 2,
  "builds": [
    {
      "src": "app.py",
      "use": "@vercel/python"
    }
  ],
  "routes": [
    {
      "src": "/(.*)",
      "dest": "app.py"
    }
  ]
}
```

---

## 🌐 Deployment

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/CodingCraftYT/Flask-App)

#### Manual Deployment

```bash
# 1️⃣ Install Vercel CLI
npm i -g vercel

# 2️⃣ Login to Vercel
vercel login

# 3️⃣ Deploy
vercel --prod
```

### Other Deployment Options

- **Heroku**: Follow [this guide](https://devcenter.heroku.com/articles/getting-started-with-python)
- **AWS**: Use Elastic Beanstalk or EC2
- **Google Cloud**: Deploy with App Engine
- **Docker**: Build and deploy containerized application

---

## 📸 Screenshot

<div align="center">

<img width="1920" height="1020" alt="Screenshot 2025-10-08 230238" src="https://github.com/user-attachments/assets/0b0be734-9aba-434e-8d2b-785bd336aa1b" />


</div>

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. 🍴 Fork the Project
2. 🌿 Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. ✍️ Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the Branch (`git push origin feature/AmazingFeature`)
5. 🔃 Open a Pull Request

### Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📞 Contact

### CodingCraftYT

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@CodingCraftYT)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CodingCraftYT)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/CodingCraftYT)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@codingcraft.com)

**Project Link:** [https://github.com/CodingCraftYT/Flask-App](https://github.com/CodingCraftYT/Flask-App)

---

## 🙏 Acknowledgments

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Vercel Documentation](https://vercel.com/docs)
- [Python.org](https://www.python.org/)
- [Font Awesome](https://fontawesome.com)
- [Shields.io](https://shields.io)

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

Made with ❤️ by [CodingCraftYT](https://github.com/CodingCraftYT)

</div>
