# Vision Image Processing Web Application

A Django-based web application that lets users upload images and apply various computer-vision filters and object tracking in real time.

---

## 🚀 Project Overview

This application provides an interactive web interface to:

- Upload an image from your local machine.  
- Apply one or more of the following filters:
  - **Sketch/Pencil**  
  - **Blur**  
  - **Grayscale**  
  - **Sharpen**  
  - **Negative Image**  
  - **Object Tracking**  
- Preview the processed image directly in your browser.  

Built with Django for the backend, OpenCV for image processing, and Bootstrap for a responsive frontend.

---

## 🧩 Repository Structure

```
.
├── manage.py                    # Django administrative utility fileciteturn1file3
├── requirements.txt             # Python dependencies fileciteturn1file0
├── vision/                      # Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── polls/                       # Django app for handling uploads & processing
│   ├── views.py                 # Main view logic for image processing
│   ├── sustain.py               # OpenCV filter & object-tracking functions
│   ├── templates/
│   │   └── index.html           # Upload form & result display fileciteturn1file2
│   └── urls.py
└── README.md                    # This file
```

---

## 🔧 Technologies & Dependencies

- **Python 3.7+**  
- **Web Framework**: Django  
- **Image Processing**: OpenCV (`opencv-python`)  
- **HTTP Requests**: `requests`  
- **Frontend**: Bootstrap 5  

Install requirements:

```bash
pip install -r requirements.txt
```

---

## 🛠️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/vision-image-app.git
   cd vision-image-app
   ```

2. **Create & activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

4. **Run the development server**

   ```bash
   python manage.py runserver
   ```
   Open <http://127.0.0.1:8000/> in your browser.

---

## 📊 Usage

1. On the home page, click **Choose File** to select an image.  
2. Toggle any combination of filters (Sketch, Blur, Grayscale, Sharpen, Negative, Object Tracking).  
3. Click **Submit**.  
4. View the processed image directly on the page.

If you encounter deployment issues, see [PythonAnywhere Deployment Guide](https://help.pythonanywhere.com/pages/DeployExistingDjangoProject/) fileciteturn1file1

---

## 📬 Contact & Contributions

Contributions are welcome! Please open an issue or pull request.  
For questions or feedback, contact: **sumithrjala@gmail.com**
