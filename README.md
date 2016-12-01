# rails-base-app
Rails Base App is a base Rails application template for start new Rails-based apps. It's based on Rails 5 and Ruby 2.3.0., MySQL as database and Puma as application server.
It has a basic set of gems I usually use in all projects I work. Also it has scaffold templates with this gems integrated to fast and easy build "ready-to-use" CRUD's.

# Proyect gems
A list of all gems included in this template proyect separated by enviroment.

## Application gems
###### Assets
* [uglifier](https://github.com/lautis/uglifier) Ruby wrapper for UglifyJS JavaScript compressor.
* [turbolinks](https://github.com/turbolinks/turbolinks) Turbolinks makes navigating your web application faster.
* [nprogress-rails](https://github.com/caarlos0/nprogress-rails) Ruby gem for asset pipeline which includes the version 0.2.0 of the rstacruz' nprogress library.
* [rails-assets-jquery](https://rails-assets.org/) jquery for Rails from rails-assets.
* [rails-assets-jquery-ujs](https://rails-assets.org/) Ruby on Rails unobtrusive scripting adapter for jQuery from rails-assets.
* [rails-assets-select2](https://rails-assets.org/) Integrate Select2 javascript library with Rails asset pipeline select2 from rails-assets.  

###### Stylesheets
* [sass-rails](https://github.com/rails/sass-rails) Ruby on Rails stylesheet engine for Sass (Dependency for bootstrap-sass gem).
* [bootstrap-sass](https://github.com/twbs/bootstrap-sass) Official Sass port of Bootstrap 2 and 3.  

###### Pager
* [kaminary](https://github.com/amatsuda/kaminari) A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Ruby webapps.

###### Filter
* [ransack](https://github.com/activerecord-hackery/ransack) Object-based searching.

###### DRY controllers
* [responders](https://github.com/plataformatec/responders) A set of Rails responders to dry up your application.

###### Forms
* [simple-form](https://github.com/plataformatec/simple_form) Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.

###### Configuration files
* [config](https://github.com/railsconfig/config) Easiest way to add multi-environment yaml settings to Rails.

## Development gems
* [rails-erd](https://github.com/voormedia/rails-erd) Generate Entity-Relationship Diagrams for Rails applications.
* [better_errors](https://github.com/charliesome/better_errors) Better error page for Rack apps.
* [binding_of_caller](https://github.com/banister/binding_of_caller) Retrieve the binding of a method's caller in MRI 1.9.2+.
* [web-console](https://github.com/rails/web-console) Rails Console on the Browser.
* [listen](https://github.com/guard/listen) The Listen gem listens to file modifications and notifies you about the changes.
* [spring](https://github.com/rails/spring) Rails application preloader.
* [spring-watcher-listen](https://github.com/jonleighton/spring-watcher-listen) Make Spring watch the filesystem for changes using Listen.

## Test gems
* [factory_girl_rails](https://github.com/thoughtbot/factory_girl_rails) Rails integration for factory_girl.
* [rspec-rails](https://github.com/rspec/rspec-rails) Testing framework for Rails 3.x, 4.x and 5.0.
* [nyan-cat-formatter](https://github.com/mattsears/nyan-cat-formatter) Nyan Cat inspired RSpec formatter.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) Collection of testing matchers extracted from Shoulda.
* [database_cleaner](https://github.com/DatabaseCleaner/database_cleaner) Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
* [faker](https://github.com/stympy/faker) A library for generating fake data such as names, addresses, and phone numbers.

# Templates
This project has predefined *generators templates* for CRUD views and controllers. If you run a *scaffold* it would use those templates to generate the views and controllers with an specific layout.  
> You can customize this templates modiffing the files in `lib/templates`. 

# Getting started
### 1. Clone this repository
Clone this project as a new project with original repository named "rails-base-app" and set your own project name.  
`$ git clone git@github.com:cunib/rails-base-app.git --origin rails-base-app [MY-NEW-PROJECT]`
### 3. Create a new repo
Move to [MY-NEW-PROYECT] folder. Change or delete `README.md` content  
`$ cd [MY-NEW-PROYECT]`  
### 3. Create a new repo
Create your new repo on your GitHub and push master into it. Make sure master branch is tracking origin repo.  
`$ git remote add origin git@github.com:[MY-GITHUB-ACCOUNT]/[MY-NEW-PROJECT].git`  
`$ git push -u origin master`  
### 4. Change project name (**optional**)
Find and replace all ocurrencies of "rails-base-app" with an appropriate name for your app.  
`$ grep -ri rails-base-app`
### 5. Add database settings
Open `database.yml` file and change user and password database attributes. Also you can change the database name for de app.
### 6. Create and migrate database
Run `rake db:create db:migrate` command to create and migrate the database.
### 7. Start the serve
Run `rails server` access localhost:3000 in your browser and...**voilá!!**. You are done.

## Contributing
You can contribute updating gems or documentation following the "fork-and-pull" Git workflow.  
   1. **Fork** the repo on GitHub.  
   2. **Clone** the project to your own machine.  
   3. **Commit** changes to your own branch.  
   4. **Push** your work back up to your fork.  
   5. Submit a **Pull request** so that we can review your changes.  


### Credits
rails-base-app was created and is maintained by [Hugo Barreña](https://github.com/cunib).
