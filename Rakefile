require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec)
task default: :spec

desc "Run CI tasks"
task ci: [:spec, :examples]
