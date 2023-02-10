# Just Chat

Here we have built a chat application with Django Channels. 

To run the backend, run:

```
virtualenv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

To run the frontend:

```
npm i
npm start
```

To develop locally:

```
1. Change the `DEBUG` flag in `src/settings.js`
2. Create two users (easiest way might be to run `python manage.py createsuperuser` twice)
3. Using django admin, create a `Contact` object for each user.
4. Make sure you have an instance of redis running. 
```

To build for deployment:

```
npm run build
```

