This is a [Django.js](https://www.djangoproject.com/start/) project in conjuction with TailwindCss and JavaScript.

## Getting Started

First, install the required dependencies:

```bash
npm install
```
Start the Django server. This project will works on default port 8000:
```bash
python3 manage.py runserver
```
If you would like to change your port to say 9000 for instance:
```bash
python3 manage.py runserver 9000
```
If you would like to make changes to the Tailwind utility classes, open another terminal and run:
```bash
npm run watch
```
It will constantly watch for Tailwind changes:

Open [http://localhost:8000](http://localhost:8000) with your browser to see the result.

