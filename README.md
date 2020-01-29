# Read Me

You may implement the exam through the following choices:<br>

<ol type="a">
<li>create using laravel only (from default-laravel installation)</li>
<li>create an API driven using laravel-vue (from default-laravel installation)</li>
<li><strike>create an API driven using laravel - vue each framework in a separate directory (boilerplate and api are given)</strike> </li>
</ol>

These following installation steps along with the pre-configured vendor packages, are already done for you:

-   \$composer install
-   \$npm install

The following packages are already installed:<br>

-   composer packages:
    -   laravel/framework
    -   laravel/tinkers
    -   prettus/l5-repository
    -   prettus/laravel-validation
    -   barryvdh/laravel-debugbar
    -   barryvdh/laravel-cors
    -   spatie/laravel-activitylog
-   npm packages:
    -   laravel-mix
    -   vue
    -   vuex
    -   axios
    -   vue-router
    -   bootstraps
    -   lodash
    -   fontawesome

The following environment configurations are required for the exam, some of these may already be provided for you but in the case it is not please create/install/correct it as required.

-   Workspace directory: /xampp-72/htdocs/laravel-exams/{$FIRST_NAME}_{\$LAST_NAME}
-   PHP Version: 7.2.\*
-   MYSQL:
    -   Host: 127.0.0.1
    -   Version 5.6.\*
    -   Username: "applicant"
    -   Password: "applicant"
    -   Database: LARAVEL\_{\$APPLICANT_NAME}\_DB

should you have request for other dependencies/packages, please ask before the exam.

# PRACTICAL EXAMINATION

**MAXIMUM OF 3 HOURS**

A client requires a Mini-CRM UI which includes an admin panel to manage companies and the company-employees and a company dashboard for their company-users to view their employees into and for employees to view scrum task in their companies.

1. Basic Laravel Auth: ability to log in as administrator
2. Use database seeds/faker to create sample users with email admin@admin.com and password “password”
3. CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
4. Companies DB table must consists of these fields: Name (required), Address(required), website,
5. Employees DB table must consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
6. Use database migrations to create those schemas above
7. Use of Basic Laravel Controllers and Model
8. Use Laravel’s validation function, using Request classes
9. Use Laravel’s pagination for showing Companies/Employees list, with 10 entries per page
10. Use Laravel's Eloquent ORM for queries and searching.

#### With this exam, the applicant should show the skills and understanding of the following:

-   MVC (Model-View-Controller) design pattern
-   Authentication
-   CRUD and Resource Controllers
-   Eloquent and Relationships
-   Database migrations and seeds
-   Form Validation and Requests
-   File management
-   Basic CSS
-   Pagination
-   Searching

Extra:

1. Email notification: send email whenever new company is entered
2. Basic testing with phpunit
3. Comment/Documentation when coding
4. Authentication of Companies and Employees
5. Dashboard of Companies and Employees
6. Logging of any user's activity

On extra modules, the applicant would show the skills and understanding of the following:

-   Understanding of Laravel Notifiable and Email Service
-   Understanding the importance of automated code-testing
-   Laravel Coding Convention and practices.
-   Understanding of Laravel Authentication Service and concepts

## SAMPLE LOGIN

![An old rock in the desert](resources/images/sample-login.png "Sample Login Page")

## SAMPLE Admin Panel

![An old rock in the desert](resources/images/sample-dashboard.png "Sample Dashdmin Panel")
