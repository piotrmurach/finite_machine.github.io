# encoding: utf-8

require 'static_deploy'

ENV['GENERATOR'] = 'jekyll'
ENV['COMMAND']   = 'build'

task default: :publish

desc 'publish this site'
task :publish do
  Rake::Task["site:publish"].invoke('piotrmurach/finite_machine')
end
