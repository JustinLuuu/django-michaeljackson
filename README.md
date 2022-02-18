# django-michael-jackson

<img src="https://imgkub.com/images/2022/02/18/Mj.jpg" alt="mj-photo">
A middleware library that puts Michael Jackson's information into every response.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install django-michael-jackson
```

In your settings.py
```python
INSTALLED_APPS.append('michaeljackson')
MIDDLEWARE.append('michaeljackson.middleware.MJMiddleware')
```

## Result
You will see the header `X-Michael-Jackson` in your response.
```
X-Michael-Jackson: Parent(s): Joe Jackson Katherine Jackson
```
