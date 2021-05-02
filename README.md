# README

1. Create a rails app using the 'rails new rails-test-app'
2. Create Pages controller using the 'rails generate controller pages' command
3. Create root route in 'config/routes.rb' file - root 'pages#home'
4. Add home method to the 'pages_controller.rb' file
5. Add html to customize the home page in the 'views/pages/home.html.erb' file
6. Add the get route for the about page - get 'about', to: 'pages#about'
7. Add html to customize the about page in the 'views/pages/about.html.erb' file
8. Use the scaffold helper command. Example: 'rails generate scaffold Article tittle:string 
description:text'
9. Run the migration created using the command 'rails db:migrate'
10. Use the 'rails routes --expanded' command to check the routes created by the scaffold
