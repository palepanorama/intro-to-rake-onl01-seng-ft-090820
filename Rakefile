namespace :greeting do
<<<<<<< HEAD
  desc 'outputs hello to the terminal'
    task :hello do
      puts "hello from Rake!"
    end
   
    desc 'outputs hola to the terminal'
    task :hola do
      puts "hola de Rake!"
    end
  end

  namespace :db do
    desc 'migrate changes to your database'
    task :migrate => :environment do
      Student.create_table
    end
    desc 'seed the database with some dummy data'
    task :seed do
      require_relative './db/seeds.rb'
    end
  end

  task :environment do
    require_relative './config/environment'
  end

  desc 'drop into the Pry'
  task :console => :environment do 
    Pry.start 
  end 
=======
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
 
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end
>>>>>>> fc68ffdb8f46d4c4e6599d50b17e54957bd50bd8
