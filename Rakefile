namespace :greeting do
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
 
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end

<<<<<<< HEAD
task :environment do
  require_relative './config/environment'
end

desc' drop into the Pry console'
task :console => :environment do
  Pry.start
end


namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
=======
namespace :db do
  desc 'migrate changes to your database'
  task :environment do
    require_relative './config/environment'
  end
  
  task :migrate => :environment do
    Student.create_table
  end
  
  desc 'drop into the Pry console'
  task :console => :environment do
    Pry.start
  end
  
>>>>>>> 5ad9ba65c66561e84544975d9e8de573f68169f0
  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
<<<<<<< HEAD
=======

>>>>>>> 5ad9ba65c66561e84544975d9e8de573f68169f0
end