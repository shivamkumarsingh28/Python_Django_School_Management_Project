
# Django-School-Management-System
![Homescreen](https://github.com/user-attachments/assets/b035f818-3fd6-453b-8cd8-d2a74f1feb75)

![Login screen](https://github.com/user-attachments/assets/3f1fd078-1756-40d2-87a9-ceca92d5ec6c)

![registration screen](https://github.com/user-attachments/assets/c321ae1c-a5a2-4273-92b4-64c746b696e9)


This app is meant to be used by school manager to manage their school records:
student data
staff
results and
finances.

It currently doesn't allow students/staff to login.
Solely, it's expected to be used on a single machine or online for managers only.

## Demo
Visit for a live demo. The demo is updated whenever the demo branch code is updated.

## Usage
It's best to install Python projects in a Virtual Enviroment. Once you have set up a VE, clone this project

```bash
git clone [Click here](https://github.com/shivamkumarsingh28/SaeeAM-Do-Project-.git)
```
Then

```bash
cd Django-School-Management-System
```
Run

```python
pip install -r requirements.txt #install required packages
python manange.py migrate # run first migration
python manange.py runserver # run the server
```
Then locate http://127.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: saeeam
password: saeeam123
```

## Roadmap
To build a fully fledge open source school management for administrative use only.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Actively under development
