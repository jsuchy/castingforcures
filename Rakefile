namespace :assets do
  task :precompile do
    sh 'bundle exec middleman build'
  end
end

task :start do
  sh 'bundle exec puma -p $PORT'
end
