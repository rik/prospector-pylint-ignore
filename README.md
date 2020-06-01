# Testing

## 1.2.0

### Configure

```shell
rm -rf .venv
python -m venv .venv
source .venv/bin/activate
pip install -r requirements_1.2.0.txt
```

### Prospector

```shell
prospector
```

0 errors

```shell
prospector app
```

0 errors

### Pylint

```shell
pylint --load-plugins=pylint_django app
```

## 1.3.0

### Configure

```shell
rm -rf .venv
python -m venv .venv
source .venv/bin/activate
pip install -r requirements_1.3.0.txt
```

### Prospector

```shell
prospector app
```

0 errors

```shell
prospector
```

```
Messages
========

app/migrations/0001_initial.py
  Line: 1
    pylint: invalid-name / Module name "0001_initial" doesn't conform to snake_case naming style
```

### Pylint

```shell
pylint --load-plugins=pylint_django app
```

0 errors
