source 'https://rubygems.org'

# Specify your gem's dependencies in autobots.gemspec
gemspec

rails_version = ENV["RAILS_VERSION"] || "default"

rails = case rails_version
when "default"
  ">= 3.2.0"
else
  "~> #{rails_version}"
end

gem "rails", rails