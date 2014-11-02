source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.6'

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development
gem 'bootstrap-sass'
gem 'devise', '~>3.4.0'
gem 'paperclip', github: 'thoughtbot/paperclip'
gem 'aws-sdk', '~>1.16.1'

# Only use sqlite in development (computer) and test
group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

