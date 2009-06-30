require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('nifty-generators', '0.2.4') do |p|
  p.project        = "niftygenerators"
  p.description    = "A collection of useful generator scripts for Rails. Modified by MEPatterson to use Formtastic for HAML forms."
  p.url            = "http://github.com/mepatterson/nifty-generators"
  p.author         = 'M.E.Patterson (originally Ryan Bates)'
  p.email          = "madraziel (at) gmail (dot) com"
  p.ignore_pattern = ["script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }

