# Scissor URL Shortening API
*(About the project here)*

 This project uses **Flask-RESTX** and **Python** for the backend and **React** and **JavaScript** for the frontend. The backend and frontend have their own folders and dependencies.

## Backend Setup
Set up environment variables using the `.env_example` file.

### Installation 
1. Install project packages
   ```
   pip install -r requirements.txt
   ```
2. Run Flask
   ```
   flask run
   ```

### Caching
This project uses `Redis` for caching to improve performance

### Testing
There are a total of 32 tests. Testing is done using `pytest-cov`.
```
coverage run -m pytest
```
to view for coverage report
```
coverage report
```

### Linting
This project uses `Flake8` to ensure code quality and adherence to coding standards
```
Flake8
```

## Frontend Setup
1. cd into the frontend folder
   ```
   cd frontend
   ```
2. Install the packages
   ```
   npm install
   ```
3. Run the dev server
   ```
   npm start
   ```
