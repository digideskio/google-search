
$:.unshift 'lib'
require 'google-search'
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new "Google Search", Google::Search::VERSION do |p|
  p.author = "TJ Holowaychuk"
  p.email = "tj@vision-media.ca"
  p.summary = "Google Search API"
  p.url = "http://github.com/visionmedia/google-search"
  p.runtime_dependencies = []
end

Dir['tasks/**/*.rake'].sort.each { |f| load f }