# 倉庫管理系統Python
## 如何使用
1. pip setup
```
python -m venv venv
pip install Flask
pip install Flask-SQLAlchemy
pip install gunicorn
```
2. start flask
```
gunicorn app:app -b 0.0.0.0:8000
```
## 漏洞
如果發現漏洞可以創建一個Issues.
