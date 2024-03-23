# Django Starter

Starter built with [Django App Generator](https://app-generator.dev/django/) - Actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`. Here are some useful links:

- 👉 [Read the Docs](https://docs.app-generator.dev/) for more input ragarding the service 
- 👉 [Get Support](https://app-generator.dev/support/) (eMail & Discord) - provided by `AppSeed`
- 🚀 Need More? Try a [PRO Account](https://app-generator.dev/support/)
  - Unlimited Apps
  - Dedicated Support 
  - 1-1 LIVE Support Sessions

<br />

## Features: 

- ✅ `Up-to-date Dependencies`
- ✅ Modern UI 
- ✅ API Generator (optional)
- 🚀 [Deploy-Ready on AWS, DO, and Azure](https://deploypro.dev/) via `DeployPRO` service (read the [DOCS](https://docs.app-generator.dev/deployment/intro))

<br />

## Start with `Docker`

> In case the starter was built with Docker support, here is the start up CMD:

```bash
$ docker-compose up --build
```

Once the above command is finished, the new app is started on `http://localhost:5085`

<br />

## Manual Build 

> Download/Clone the sources  

```bash
$ git clone https://github.com/<THIS_REPO>.git
$ cd <LOCAL_Directory>
```

<br />

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> `Set Up Database`

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> `Generate your API` (optional) 

```bash
$ python manage.py generate-api -f
```

<br />

> `Start the App`

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

---
Starter built with [Django App Generator](https://app-generator.dev/django/), a free service provided by AppSeed.
