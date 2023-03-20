# Ruby on Rails project

# Description
A simple ruby on rails blog project.

# Dependencies
- Ruby
- Rails

# Blog directory structure

| Folder | Purpose |
| --- | --- |
| `app/` | Contains the controllers, models, views, helpers, mailers, channels, jobs, and assets for your application. You'll focus on this folder for the remainder of this guide. |
| `bin/` | Contains the rails script that starts your app and can contain other scripts you use to set up, update, deploy, or run your application. |
|  `config/` |   Contains configuration for your application's routes, database, and more. This is covered in more detail in [Configuring Rails Applications](https://guides.rubyonrails.org/configuring.html). | 
|  `config.ru`  | Rack configuration for Rack-based servers used to start the application. For more information about Rack, see the [Rack website](https://github.com/rack/rack). | 
|  `db/`  | Contains your current database schema, as well as the database migrations. | 
|  `Gemfile Gemfile.lock` | These files allow you to specify what gem dependencies are needed for your Rails application. These files are used by the Bundler gem. For more information about Bundler, see the [Bundler website](https://bundler.io) | 
| `public/` | Contains static files and compiled assets. When your app is running, this directory will be exposed as-is. | 
|  `Rakefile` | This file locates and loads tasks that can be run from the command line. The task definitions are defined throughout the components of Rails. Rather than changing Rakefile, you should add your own tasks by adding files to the `lib/tasks` directory of your application. | 
| `storage/`  | Active Storage files for Disk Service.This is covered in [Active Storage Overview](https://guides.rubyonrails.org/active_storage_overview.html). | 
| `test/`  |  Unit tests, fixtures, and other test apparatus.These are covered in [Testing Rails Application](https://guides.rubyonrails.org/testing.html) | 
|  `tmp/` | Temporary files (like cache and pid files). | 
| `vendor/` | A place for all third-party code. In a typical Rails application this includes vendored gems.  | 
|  `.gitattributes`  |  This file defines metadata for specific paths in a git repository. This metadata can be used by git and other tools to enhance their behavior. | 
|  `.gitignore` | This file tells git which files (or patterns) it should ignore. See GitHub - Ignoring files for more information about ignoring files.  | 
| `.ruby-version` | This file contains the default Ruby version.  | 



# Getting started
Fork or download project and run:
```
bundle install
```
Then, run the rails application:

``` 
rails s
```

# Resources
[Ruby on Rails Guide](https://guides.rubyonrails.org/getting_started.html)