source 'https://rubygems.org'
ruby '2.6.6'                              # Ruby language

gem 'rails', '~> 5'
gem 'thin', '~> 1'                        # Web Server process

# Database
gem 'pg'                                  # PostgreSQL

group :production do
  gem 'rails_12factor'                    # Heroku Asset Pipeline
end

group :development do
  gem 'annotate'                          # Annotate routes and models
end
