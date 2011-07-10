source 'http://rubygems.org'

gem 'rails', '3.0.9'
gem 'sqlite3', '1.3.3'

group :development do
  gem 'rspec-rails', '2.6.1'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'spork', '0.9.0.rc8'
end

# The text of the gemfile above came from the rails tutorial online book.

# The function 'xmlHasFeature' is missing from your installation of libxml2.  
# Likely this means that your installed version of libxml2 is old enough 
# that nokogiri will not work well.  
# To get around this problem, please upgrade your installation of libxml2.

# Please visit http://nokogiri.org/tutorials/installing_nokogiri.html 
# for more help!
# *** extconf.rb failed ***
# Could not create Makefile due to some reason, probably lack of
# necessary libraries and/or headers.  Check the mkmf.log file for more
# details.  You may need configuration options.

# NOTE:  Nokogiri requires a more updated version of libxml2 and libxslt
# than comes with Leopard (an old, buggy 2004 version)
# use macports to install the latest, with the following command
# (I did this from my ~ directory)
# sudo port install libxml2 libxslt
# Once this was installed, I ran bundle install from the project directory
# again, and the gem installation, including rspec, was completed normally