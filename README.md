## cookiecutter-drf-vue

Lightweight cookiecutter template which includes config files for Django, Django REST Framework and Vue JS.

### Create your project
If you don't have cookiecutter, install it:
```bash
pip install cookiecutter --user
```

Then create your project:
```bash
cookiecutter https://github.com/arsenlosenko/cookiecutter-drf-vue
```

### Features
* Supports Django 2.0
* [Django REST Framework](https://github.com/encode/django-rest-framework) already included
* Vue JS with configured Babel and Webpack:
* [Vuex](https://github.com/vuejs/vuex)
* [vue-router](https://github.com/vuejs/vue-router)

### Local Development
1. Create virtualenv

``bash
pip install virtualenv --user
cd <your-cookicutter-project>
virtualenv -p python3 venv
source venv/bin/activate
```
2. Install python dependencies

```bash
# inside of virtualenv
pip install -r requirements.txt
```
3. Install javscript dependencies

```bash
# inside projects directory
npm i

```
4. Build development bundle

```bash
# just build dev bundle
npm run dev_build

# rebuild on file change
npm run dev_serv

# build for production
npm run prod_build

```
5. Initial migrations

```bash
python manage.py makemigrations
python manage.py migrate
```
6. Runserver
```bash
python manage.py runserver
```
