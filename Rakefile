require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new("test") do |test|
  test.libs << 'lib'
  test.libs << 'test'

  test.test_files = FileList['test/**/*_test.rb']
  test.warning = false
  test.verbose = true
end
