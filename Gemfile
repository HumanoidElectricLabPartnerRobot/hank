group :development, :test do
  gem "parallel_tests"
  gem "rspec-rails",      "~>3.6.0"
end

group :development do
  gem "foreman"
  gem "haml_lint",        "~>0.20.0", :require => false
  gem "rubocop",          "~>0.52.1", :require => false
  # ruby_parser is required for i18n string extraction
  gem "ruby_parser",                  :require => false
  gem "scss_lint",        "~>0.48.0", :require => false
  gem "yard"
end

group :test do
  gem "brakeman",         "~>3.3",    :require => false
  gem "capybara",         "~>2.5.0",  :require => false
  gem "coveralls",                    :require => false
  gem "factory_bot",      "~>4.11.1", :require => false
  gem "timecop",          "~>0.7.3",  :require => false
  gem "vcr",              "~>3.0.2",  :require => false
  gem "webmock",          "~>2.3.1",  :require => false
end
