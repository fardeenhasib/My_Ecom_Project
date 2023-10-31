# My Ecommerce Project

Welcome to my Ecommerce Application!


## Getting Started

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/fardeenhasib/My_Ecom_Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-django-project
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   On Windows:

   ```bash
   venv\Scripts\activate
   ```

   On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

5. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

1. Create a `.env` file in the project directory to store your environment variables. You can use the `.env.example` file as a template.

   ```env
   DEBUG=True
   SECRET_KEY=your_secret_key
   DATABASE_URL=your_database_url
   # Add other configuration variables as needed
   ```

2. Configure your database settings in the project's settings file (`settings.py`).

3. Migrate the database:

   ```bash
   python manage.py migrate
   ```

### Running the Project

Start the development server:

```bash
python manage.py runserver
```

The project will be available at `http://localhost:8000/`.
