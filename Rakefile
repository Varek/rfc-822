require 'rubygems'
require 'spec/rake/spectask'
require 'spec/version'

desc 'Default: run specs.'
task :default => :spec

Spec::Rake::SpecTask.new do |t|
  t.spec_files = FileList['spec/**/*_spec.rb']
  t.spec_opts = ['--colour', '--format', 'profile', '--timeout', '20']
end
