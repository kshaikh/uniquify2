# Rakefile
require 'rubygems'
require 'rake'
require 'echoe'
require 'active_record'

Echoe.new('uniquify', '0.1.0') do |p|
  p.description    = "Generate a unique token with Active Record."
  p.url            = "http://github.com/kshaikh/uniquify2"
  p.author         = "Khalid Shaikh"
  p.email          = "khalid.j.shaikh@gmail.com"
  p.ignore_pattern = ["tmp/*", "script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }

