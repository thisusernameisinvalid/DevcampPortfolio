Instructions to enter into the bash shell
To startup the PostgreSQL database:

  sudo service postgresql start
  
To generate a new rails application:

  rails new AppName -T --database-postgresql
  
Change into the app:

  cd AppName
  
Start rails server:

  rails s -b $IP -p $PORT