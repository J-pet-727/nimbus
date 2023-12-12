# NimbusWardrobe

## Synopsis

```bash
streamlit run Main.py
```

## Project Structure

```
├── Main.py
├── nimbus_wardrobe.db
└── pages
   ├── Login.py
   ├── Register.py
   └── Result.py
```

- `Main.py`: responsible for the Streamlit launcher and the main page as well as the DataBase object managing the users and the wardrobe items.
- `nimbus_wardrobe.db`: the sqlite3 file for the saved data
- `pages/Login.py`: the Login page – if the user is not logged in, this is the default starting page
- `pages/Register.py`: when a user needs to register at the first visit, this page lets one register the email and password
- `pages/Result.py`: After the user finished adding wardrobe items and entered the city name on the main page, hitting the button transits to this Result page with a random background image of the current weather
