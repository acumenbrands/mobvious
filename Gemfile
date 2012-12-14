if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source :rubygems

gemspec

gem 'mobileesp', :git => 'git://github.com/eimermusic/mobileesp'

# == SPECIAL DEVELOPMENT DEPS HANDLING ==

# temporarily switched for this fork, because the current version of guard-minitest has broken notifications
gem 'guard-minitest', git: 'git://github.com/aspiers/guard-minitest', ref: '4b660261d35'
gem 'mocha', require: false
gem 'turn', require: false
