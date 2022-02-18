# django-michael-jackson

<img src="https://lh5.googleusercontent.com/Z4pzpN9iwhk5BjrKhoS6bruxt5e4lJAWxAGnlB8mnO8bm78PGHpNZmC4zjmQHxtWIa5Ccgb_XvFW7MW7YzPX=w1366-h657" alt="mj-photo">
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
