# frozen_string_literal: true

require 'rake/testtask'

task default: :spec

task :spec do
  sh 'rspec .'
end

Rake::TestTask.new(:test) do |t|
  t.test_files = FileList['*_test.rb']
end
