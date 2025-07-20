# Temple Booking Project

## Setup Instructions

1. **Clone the repository**

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Mac/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is missing, install Django manually:)*
   ```bash
   pip install django pillow
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python manage.py runserver
   ```

6. **Access the app**
   Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## Notes
- Default database: SQLite (`db.sqlite3`)
- Static and media files are in `/static/` and `/media/` respectively.
- To create a superuser for admin access:
  ```bash
  python manage.py createsuperuser
  ```
