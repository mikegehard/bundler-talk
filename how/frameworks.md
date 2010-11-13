!SLIDE bullets incremental center
# Rails 2

* <http://gembundler.com/rails23.html>
* then follow Rails 3 instructions

!SLIDE bullets incremental center
# Rails 3

* edit your Gemfile (provided by rails new command)
* `bundle install`
* `rails server`, `rake cucumber`, `rake spec` or `rake test`

!SLIDE center bullets incremental
# Sinatra

* `bundle init` to create a Gemfile
* edit Gemfile
* set up your config.ru file
* `bundle install`
* `rackup`

!SLIDE center bullets incremental
# Brand new ruby gem

* `bundle gem my_gem`
* edit .gemspec to add dependencies (both development and runtime).
* `bundle install`
* do your development
* `gem build my_gem.gemspec` to build the gem

!SLIDE center bullets incremental
# Existing ruby gem

* run `bundle init`
* edit Gemspec to add `gemspec`
* run `bundle install`
* do your development
* run `gem build my_gem.gemspec` to build the gem

!SLIDE center 
## After downloading code that uses bundler, run `bundle install`