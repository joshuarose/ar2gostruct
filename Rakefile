require "bundler/gem_tasks"

task :default => :spec

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new do |t|
  t.rspec_opts = ["--color", '--format doc']
end