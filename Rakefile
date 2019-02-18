desc('Running a project')
task :start do
  sh 'ruby src/main.rb'
end

desc('Running lint in projec')
task :lint do
  system 'bundle exec rubocop -a'
  system 'bundle exec rubocop'
end

desc('Running lint in projec')
task :tests do
  system 'bundle exec rspec spec/'
end
