source "http://rubygems.org"

gem 'sexp_processor', ">= 4.10.0"
gem 'ruby2ruby', ">= 2.4.0"
gem "ruby_parser", ">= 3.10.1"

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem "rdoc", "~> 3.12"
  gem "bundler", "~> 1.0"
  gem "jeweler", RUBY_VERSION.start_with?("1.8") ? "~> 1.0" : ">= 0"
  gem "rcov", :platforms => :ruby_18
  gem "simplecov", :platforms => [:ruby_19, :ruby_20, :ruby_21, :ruby_22, :ruby_23, :ruby_24, :ruby_25, :jruby]
  gem "test-unit", :platforms => [:ruby_19, :ruby_20, :ruby_21, :ruby_22, :ruby_23, :ruby_24, :ruby_25, :jruby]
  gem "rake", RUBY_VERSION.start_with?("1.8") ? "< 11" : ">= 0"
end
