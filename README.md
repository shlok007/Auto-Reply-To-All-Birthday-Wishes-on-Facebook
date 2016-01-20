

## Description

An app to demonstrate user authentication from facebook using Devise and Omniauth gem used simultaneously.

## Rails Version
Version of rails used in this project is 4.2.2 .A gem file containing the version numbers of each gem used in this application is present. 

##Installation

To install rails in linux based system follow the following guide: http://railsapps.github.io/installrubyonrails-ubuntu.html
Windows and Mac OS users refer to: http://railsinstaller.org/en 

## Contributing
Follow the following steps to setup development environment and start contibuting to Facebook-Integration:

##Setup Facebook-Integration in development environment for linux

1. Clone the repository by running the following command:     
  
         git clone https://github.com/shlok007/Facebook-Integration.git Facebook-Integration

2. Move inside the directory of Facebook-Integration:
         
         cd Facebook-Integration

3. Run the following to install all required gems:
         
         bundle install

4. To use database run migration by:
         
         RAILS_ENV=development rake db:migrate

5. The rails server command launches a small web server named WEBrick which comes bundled with Ruby.Just run:
         
         bin/rails server

6. All set now. Visit [http://localhost:3000][localhost] to view the rails app in development environment.

[localhost]: http://localhost:3000
