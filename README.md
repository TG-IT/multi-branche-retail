# Multi-Branche Store - For Assessment

### Requirements
- Composer v2
- PHP v7.4
- MySQL v8.0



### Setup Steps
- Create ENV File ```cp .env.example .env```.
- Configure database connection in the .env file.
- Run ```composer install``` to install all dependencies.
- Run ```php artisan key:generate``` to generate a new application key.
- Run ```php artisan migrate``` to create the database tables.
- Run ```php artisan serve``` to start the development server.



### Tasks to be completed
- [] Enable User Registration Functionality.
- [] Correct the language switcher functionality.
- [] Implement a Settings Page for configuring the application's title and logo.
- [] Incorporate the application title and logo into the admin sidebar.
- [] Develop a CRUD module to manage branches as this app should be multi branche POS app, enabling branch creation, selection, and linking with other modules.
- [] Add dashboard charts that could help your clients make good decisions.
- [] Perform a thorough app evaluation and offer recommendations to improve functionality and performance, along with suggesting new features within the same context.