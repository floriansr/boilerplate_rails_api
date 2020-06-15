source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'devise-jwt', '~> 0.6.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'rack-cors', '~> 1.1', '>= 1.1.1'
gem 'rails', '~> 6.0.3', '>= 6.0.3.1'
gem 'table_print', git: 'git://github.com/julienemo/table_print.git', branch: '84_bug_no_method_error_in_ruby_2.7.1'

group :development, :test do
	 gem 'byebug', platforms: %i[mri mingw x64_mingw]
	 gem 'rubocop', '>= 0.85.0'
end

group :development do
	 gem 'dotenv-rails'
	 gem 'listen', '~> 3.2'
	 gem 'spring'
	 gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
