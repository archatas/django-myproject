# Django MyProject

This is a boilerplate for a scalable Django project. To use it, just download the source code.

1. Create a virtualenv
```python
python3 -m venv myprojectvenv
```

1. Globally replace "myproject" with a meaningful project name. 
1. Create secrets.json in settings directory
```python
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
```
