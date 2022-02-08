source 'https://rubygems.org'

gemspec

gem "rails",       "~> 7.0.0"
gem "paper_trail", "~> 12.2.0", git: "https://github.com/baarkerlounger/paper_trail", branch: "dluhc-fixes"
gem "activeadmin", git: "https://github.com/tagliala/activeadmin.git", branch: "feature/railties-7"
gem "pry"
gem "appraisal"
gem "sprockets-rails"
gem "sassc-rails"

group :development do
  gem "rubocop", "~> 0.40.0"
end

group :test do
  gem "capybara"
  gem "rspec-rails"
  gem "database_cleaner"
  gem 'shoulda-matchers'
  gem "sqlite3", platforms: :mri
  gem "poltergeist"
end
