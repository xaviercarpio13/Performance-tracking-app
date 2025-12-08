<p align="center">
  <img src="frontend/src/assets/Logo.png" alt="Logo de SYNCADEMIC" width="700px"/>
</p>

¡Welcome to SYNCADEMIC! 🎓🚀
Syncademic is a full-stack web application designed to analyze and manage academic performance for students and teachers.
Built collaboratively by a 24-person development team, the platform uses Django REST Framework on the backend and React + TypeScript on the frontend, following a Behavior-Driven Development (BDD) approach with Behave and Gherkin for automated testing.

## Overview

Syncademic provides actionable academic insights such as:
- 🌞 Identifying students eligible for summer reinforcement courses
- 📉 Detecting students with low academic performance
- 🕒 Notifying pending teaching hours or incomplete schedules
- 🧑‍🏫 Suggesting optimal teaching assignments based on subject expertise
- 🚩 Predicting potential student dropout risk based on attendance patterns

And more features designed to streamline academic decision-making.

## Development Team
<p align="center">
  <img src="frontend/src/assets/EquipoDeDesarrollo.png" alt="Equipo de desarrollo" width="500px"/>
</p>

## Tech Stack

### Backend
- Python ![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
- Django ![Django](https://img.shields.io/badge/Django-4.2-green.svg)
- Django REST Framework ![DRF](https://img.shields.io/badge/Django%20REST-3.14-blue.svg)
- Behave ![Behave](https://img.shields.io/badge/Behave-1.2.7-orange.svg)
- Gherkin ![Gherkin](https://img.shields.io/badge/Gherkin-6.0.0-green.svg)
- Faker ![Faker](https://img.shields.io/badge/Faker-14.1.1-yellow.svg)
- Docker ![Docker](https://img.shields.io/badge/Docker-24.0.2-blue.svg)

### Frontend
- Node.js ![Node.js](https://img.shields.io/badge/Node.js-18.17.1-green.svg)
- pnpm ![pnpm](https://img.shields.io/badge/pnpm-8.6.7-orange.svg)
- Vite ![Vite](https://img.shields.io/badge/Vite-4.3.9-yellow.svg)
- React ![React](https://img.shields.io/badge/React-18.2.0-blue.svg)
- TypeScript ![TypeScript](https://img.shields.io/badge/TypeScript-5.1.6-blue.svg)
- React Bootstrap ![React Bootstrap](https://img.shields.io/badge/React%20Bootstrap-2.8.0-blue.svg)
- ESLint ![ESLint](https://img.shields.io/badge/ESLint-8.45.0-purple.svg)

---

## Running the Application

### Frontend Setup

```sh
git clone https://github.com/xaviercarpio13/Performance-tracking-app
cd /frontend
pnpm install
pnpm run dev
```

### Backend Setup

```sh
git clone https://github.com/xaviercarpio13/Performance-tracking-app
cd /backend
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## Contributing
Contributions are welcome, if you'd like to contribute to SYNCADEMIC:

1. Create a fork of the currently repository
2. Create a new branch
```sh
git checkout -b feature/new-feature
```
3. Make changes and commit them
```sh
git commit -m 'feat: description of the new functonality'
```
4. Push
```sh
git push origin feature/new-feature
```
5. Create a Pull Request

## Contributors

<img style="width:100%;" src="https://contrib.rocks/image?repo=SebastianJimenez2/Performance-tracking-app">

---

Thank you for using SYNCADEMIC! If you have questions, suggestions, or improvements, feel free to open an issue or reach out.
