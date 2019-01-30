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

After couple of prompts (namely the name of your project), you will be presented with directory, which includes:

* Django main project directory (with `settings.py`)
* `requirements.txt` file with dependencies for backend
* config files for Vue JS:
    * `package.json` - file with dependencies and package information
    * `webpack.config.js` - webpack config (bundles only `*.vue` and `*.js` files)
    * `.babelrc` - config for babel
* `frontend` app which contains Vue JS project. Besides plain Vue, it also uses [Vuex](https://github.com/vuejs/vuex) and [vue-router](https://github.com/vuejs/vue-router)

### Install dependencies and run the app
1. Create virtualenv
2. Install python dependencies
3. Install javscript dependencies
4. Build development bundle
5. Runserver
