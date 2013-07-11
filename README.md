This is the Sample template file to configure all the required environment like rspec , guard spork etc.

Do the following (-->)
bundle install
bundle update
rails generate rspec:install
bundle exec guard init rspec
bundle exec guard

Next, bootstrap the Spork configuration:
bundle exec spork --bootstrap


spork server
--> bundle exec spork


bundle exec guard init rspec
guard: 
--> bundle exec guard


time bundle exec rspec 
bundle exec spec/requests/static_pages_spec.rb --drb




