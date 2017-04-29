source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails",                       "~> 5.1.0"

gem "active_model_serializers",    "~> 0.9"    # JSON generation conventions
gem "pg",                          "~> 0.18"   # Postgresql adaptor
gem "puma",                        "~> 3.7"    # Fast, threaded web server
gem "sass-rails",                  "~> 5.0"    # Sass CSS Preprocessor
gem "slim",                        "~> 3.0"    # Templating language
gem "turbolinks",                  "~> 5.0"    # Turbolinks makes navigating your web application faster
gem "uglifier",                    ">= 1.3"    # Compressor for JavaScript assets
gem "webpacker",                   "~> 1.2"    # Transpile app-like JavaScript


group :development, :test do
  gem "bundler-audit"                          # Checks gems for security vulnerabilities
  gem "minitest-rails"                         # Adds Minitest as the default testing library
end

group :development do
  gem "listen"                                 # Evented file system monitor
  gem "pry-awesome_print"                      # Auto AP in pry
  gem "pry-rails"                              # Adds pry, an interactive REPL debugger; Try show-models
  gem "pry-remote"                             # Call binding.remote_pry in code; pry-remote in your shell
  gem "pry-stack_explorer"                     # View stack traces in pry
  gem "spring"                                 # Keeps application running in the background.
  gem "spring-watcher-listen"                  # Spring adaptor for listen gem
  gem "web-console"                            # Access an IRB console on exception pages o
end

group :test do
  gem "capybara"                               # Adds support for Capybara system testing and selenium driver
  gem "minitest-stub_any_instance"             # Stubs any instance of a class
  gem "poltergeist"                            # PhantomJS driver for Capybara
end
