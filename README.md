# Django MyProject

This is a boilerplate for a scalable Django project. To use it, just download the source code.

* Create a virtualenv
```python
python3 -m venv myprojectvenv
```
* Globally replace "myproject" with a meaningful project name. 
* Create secrets.json in settings directory
```python
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
```
* Modify manage.py to use the right setting file
```python
os.environ.setdefault('DJANGO_SETTINGS_MODULE',  'myproject.settings.production')
```
