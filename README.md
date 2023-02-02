# [Flask Berry PRO](https://appseed.us/product/berry-dashboard-pro/flask/)

Premium **Flask Dashboard** project crafted on top of **[Berry PRO](https://appseed.us/product/berry-dashboard-pro/flask/)**, a pixel-perfect `Bootstrap 5` design from [CodedThemes](https://codedthemes.com/?ref=appseed). The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. `Berry` has easy and intuitive responsive design whether it is viewed on retina screens or laptops.

- 👉 [Flask Berry PRO](https://appseed.us/product/berry-dashboard-pro/flask/) - `Product page`
- 👉 [Flask Berry PRO](https://flask-berry-pro.onrender.com) - `LIVE Demo`
- 🚀 Free [Support](https://appseed.us/support/) via `Email` & `Discord`

<br />

> Features

- ✅ `Up-to-date dependencies`
- ✅ `UI Kit`: [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) by `CodedThemes`
- ✅ `Database`: `SQLite`, MySql
  - Silent fallback to `SQLite`  
- ✅ `DB Tools`: SQLAlchemy ORM, `Flask-Migrate`
- ✅ `Authentication`, Session Based
- ✅ `Docker`, Page Compression via `Flask-Minify`
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`
  - `CDN Support` (optional)   

<br />

![Berry Bootstrap 5 PRO - Premium Template Django Template.](https://user-images.githubusercontent.com/51070104/210833058-be0b3e87-4f2b-4765-b84d-3795ba03c6a1.jpg)

<br /> 

## ✨ Start the app in Docker

> 👉 **Step 1** - Download & unzip the code

```bash
$ unzip flask-berry-dashboard-pro.zip
$ cd flask-berry-dashboard-pro
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## ✨ How to use it

> Download & unzip the code 

```bash
$ unzip flask-berry-dashboard-pro.zip
$ cd flask-berry-dashboard-pro
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

Edit `.env` using `env.sample` or simply export the variables in the `environment`. Here are the expected values: 

- `DEBUG`: controls the `Development`, `Production` mode
  - Default `False` (production)
- `FLASK_APP=run.py`: mandatory (APP entry point) 
- `SECRET_KEY`: optional, random value used if not provided
- `DB credentials`
  - `Note`: if NOT provided, or wrong values, **SQLite is used**
  - `DB_ENGINE`, `DB_HOST`, `DB_NAME` ...
- `CDN_DOMAIN`: disabled by default
  - Used only when `DEBUG=False` (production mode)   
 
<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

Edit `.env` using `env.sample` or simply export the variables in the `environment`. Here are the expected values: 

- `DEBUG`: controls the `Development`, `Production` mode
  - Default `False` (production)
- `FLASK_APP=run.py`: mandatory (APP entry point) 
- `SECRET_KEY`: optional, random value used if not provided
- `DB credentials`
  - `Note`: if NOT provided, or wrong values, **SQLite is used**
  - `DB_ENGINE`, `DB_HOST`, `DB_NAME` ...
- `CDN_DOMAIN`: disabled by default
  - Used only when `DEBUG=False` (production mode)  

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |
   |         |-- home/                     # UI Kit Pages
   |              |-- index.html           # default page
   |              |-- page-404.html        # 404 error page
   |              |-- *.html               # Used by common pages like index, UI
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

## Screenshots

![Berry Pro - Premium full-stack starter crafted by AppSeed.](https://user-images.githubusercontent.com/51070104/210833261-af09bc29-0894-4d21-84ad-8e8853f8cbe1.jpg)

<br />

> **Flask Berry PRO** - `Kanban Board`

![Berry Pro, Kanban Board - Premium full-stack starter crafted by AppSeed](https://user-images.githubusercontent.com/51070104/210833567-e26f67e1-53c8-430a-8add-e4d6c874266a.jpg)

<br />

> **Flask Berry PRO** - `Kanban Board`

![Berry Pro, Widgets page - Premium full-stack starter crafted by AppSeed](https://user-images.githubusercontent.com/51070104/210833737-76643967-02f6-4342-9545-1ffaba68343f.jpg)

<br />

> **Flask Berry PRO** - `eCommerce`

![Berry Pro, eCommerce page - Premium full-stack starter crafted by AppSeed](https://user-images.githubusercontent.com/51070104/210834456-344fbcb5-4a32-45ed-964e-b808dbc53356.jpg)

<br />

---
[Flask Berry Bootstrap PRO](https://appseed.us/product/berry-dashboard-pro/flask/) - Premium **Flask** starter provided by **[AppSeed](https://appseed.us/)**
