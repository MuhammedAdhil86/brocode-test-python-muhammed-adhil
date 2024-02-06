# Django Cooking Application

This Django project is a cooking application that allows users to browse recipes and categories, view recipe details, and manage recipe data.

## Features

- Display all recipes with their ingredients and categories.
- View details of each recipe, including ingredients and associated categories.
- Browse recipes by category.
- API endpoints to retrieve recipe and category data.

## Setup

1. *Clone the repository:*

    bash
    git clone https://github.com/your_username/django-cooking-app.git
    

2. *Install dependencies:*

    bash
    pip install -r requirements.txt
    

3. *Apply database migrations:*

    bash
    python manage.py migrate
    

4. *Populate the database with sample data:*

    bash
    python utils/populate_data.py
    

## Usage

1. *Run the development server:*

    bash
    python manage.py runserver
    

2. *Access the application:*

    Open your web browser and go to [http://localhost:8000](http://localhost:8000) to view the application.

## API Endpoints

- /api/recipe/<int:recipe_id>/: Retrieve details of a specific recipe in JSON format.
- /api/category/<int:category_id>/: Retrieve details of a specific category along with associated recipes in JSON format.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature/your-feature-name).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
