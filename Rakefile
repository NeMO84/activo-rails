require 'bundler'
Bundler::GemHelper.install_tasks

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new do |t|
  t.name = "spec"
  t.pattern = "spec/*_spec.rb"
end
