source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'rails', '~> 6.1.4', '>= 6.1.4.6'
gem 'puma', '~> 5.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'pry-rails', '~> 0.3.9'
gem 'rspec-rails', '~> 5.0.0'



group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :production do 
  gem 'pg', '~> 1.3', '>= 1.3.5'
end


group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'mongoid', '~> 7.0.5'
