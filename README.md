Inspired by my friend & former classmate Christa Harstock who created a similar bot in Python. I created mine in Ruby using an NLP library that finds a sentence that is less than or equal to 140 chracters and tweets it. 

Steps to install 

1. Install [Treat](https://github.com/louismullie/treat) 
2. Install the latest version of [Java](https://java.com/en/download/index.jsp) on your computer. Also,
make sure you set your [$JAVA_HOME](http://www.mkyong.com/java/how-to-set-java_home-environment-variable-on-mac-os-x/) variable to /usr/libexex/java_home or else this will cause problems later on and I'd be sad if it did for you :(. 	
3. The rest of Treat's dependencies are broken up into
   languages packages, but for clarity's sake we'll stick to English. So go to your terminal and type irb or write a ruby script and run the following "require 'treat'" then type "Treat::Core::Installer.install 'english'
4. Install the [Twitter gem](https://github.com/sferik/twitter) and supply your credentials.
5. After the above is done installing you can finally create your own bot. 
6. Have fun!