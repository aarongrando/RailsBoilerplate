source 'https://rubygems.org'
ruby '2.4.3'                    # Heroku documentation highly recommends setting a ruby version number

gem 'rails', '5.2.1'
gem 'pg'                        # A driver for PostgreSQL, the database of choice for Rails
gem 'lograge'                   # Makes our prod logs much easier to grok
gem 'puma'                      # A nice HTTP Server
gem 'jquery-rails'              # Gives us easy access to jQuery
gem 'sass-rails'
gem 'uglifier'
gem 'actionpack-cloudflare'     # Allow Rails request.remote_ip to defer to CloudFlare's connecting IP

# Useful optional gems
# gem 'activeadmin'               # Database administration
# gem 'devise'                    # User management
# gem 'paperclip'                 # Paperclip is useful for handling file attachments associated with models
# gem 'aws-sdk-s3'                # Allow for the storage of Paperclip attachments on S3

group :development do
  gem 'progress_bar'            # For better terminal outputs
  gem 'better_errors'           # For displaying better error pages
  gem 'binding_of_caller'       # For providing an active console on error pages
end

group :production do
  gem 'rails_12factor'
  gem 'rails_stdout_logging'
  gem 'rails_serve_static_assets'
end
