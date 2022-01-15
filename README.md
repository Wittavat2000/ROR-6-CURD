Resource
- Users - create users table and model
        - add validations
        * username must be present and unique, min 3 max 25
        * email address must be present and unique, max 105
        * email must be valid email format, check with email regex

Associations
- One-to-many
  between users and articles

REST for users

Authentication
- Login using secure password

Restriction of actions
- Based on logged in/logged out state

Security
- Admin user functionality and access level


Introduction to Ruby on Rails
- Introduction to Section 3 and Ruby on Ruby on Rails kickoff
- Model, View, Controller and Rails App Structure
- Required: Ruby on Rails installation (local or cloud-IDE)
- Root route, controller, more MVC and say 'Hello World'
- Structure of a Rails application
- Version control with Git
- Setup online code repository with Github
- Front-end: Learn add praction HTML and CSS 
- Add About page and homework assignment
- Production Deploy by heroku
- The back-end: Database and tables in Rails
The back-endL CRUD, scaffold and wrap-up section 3

CRUD Operations in Ruby on Rails
- Preview of Alpha Blog App and Information
- Introduction to Section 4: Tables, migrations and naming conventions
- Models and rails console
- CRUD operations from rails console
- Validations
- Show articles (route, action and view)
- Articles index
- Forms - build a new article creation form
- Create action - save newly created articles
- Messaging - validation and flash messages
-  Edit and update: update existing articles
- Delete: delete articles
- User Interface - add layout links
- DRY (Don't Repeat Yourself) code - refactoring and partials
- Production deploy and wrap up section 4

Styling for your Rails Application
- Introduction to Section 5 and styling
- Install Bootstrap, asset pipeline, JavaScript, webpack - Rails 6 vs 5
-  Install Bootstrap in Rails 5 (or earlier versions)
- Build homepage
- Layout links using Bootstrap classes
- Style articles index page
- Style form partial
- Style validation and flash messages
- Style show view
- Cleanup layout, production deploy and wrap up section 5



Associations and Authentication Systems
- Introduction to section 6: users, associations, ERD and more
- One-to-many associations demo with the rails console
- Create users
- Add user validations
- One to many association
- Show user info in articles
- Alter object state before_save
- Add secure password
- New user signup form
- Create new users (back-end)
- Edit users
- Show user and profile image
- Add users index
- Cleanup layout
- Add pagination to views
- Add login form
- Create and destroy user sessions
- Authentication helper methods
- Controller methods as helper methods
- Restrict actions from UI
- Modify navigation based on helpers
- Restrict actions at controller level - articles
- Restrict actions in controller level - users
- Delete user
- Add admin user functionality - intro
- Add admin user access through views and controllers
- Assignment - alert message color based on type
- Production deploy and wrap up section 6


Many-To-Many Associations and Automated Testing , Integration , Functional , Unit 
- Introduction to Section 7
- Category model and testing
- Validations using unit tests
- Categories controller and tests
- Create category and test
- Integration test: Create category business process
- Integration test for invalid category
- Integration test and feature: listing categories
- Admin user requirement and test
- Update navigation
- Many-to-many association - introduction
- Many-to-many association - back-end implementation
- Add association from UI
- Update article views to display categories
- Complete category index and show 
- Edit categories
- Deploy to production, homework, wrap up section 7





