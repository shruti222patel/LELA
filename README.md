LELA
====

MISSION LELA (Learn Laravel)


Key Terms:
 	
 	- Home Directory = top level folder for the user (E.g. My home directory is 'shrutipatel')
 	- Root Directory = top level folder (in this case it will refer to 'LELA')
 	- highlited text = needs to be executed in the terminal or PC equivalent


* Install [Virtual Box](https://www.virtualbox.org/)

* Install [Vagrant](http://www.vagrantup.com/)

* Install Vagrant Plugin - Hostupdater
	* `vagrant plugin install vagrant-hostsupdater`
* Install Vagrant laravel/homestead Box
	* `vagrant box add laravel/homestead`

* Install [MySQL Pro](http://www.sequelpro.com/) or [MySQL Workbench](http://dev.mysql.com/downloads/workbench/)
	
* Install Composer & php55
	* If you have a Mac
		* `brew update`
		* `brew tap homebrew/homebrew-php`
		* `brew tap homebrew/dupes`
		* `brew tap homebrew/versions`
		* `brew install php55`
		* `brew install homebrew/php/composer`
		
	* If you have a PC
		* Follow [these](https://getcomposer.org/doc/00-intro.md#using-the-installer) directions to download the file

* Clone the repository by going into the terminal (or PC equivalent) & `git clone https://github.com/shruti222patel/LELA.git`
 
* Go into the root directory (`cd LELA`) & execute the start.sh file (`sh start.sh`)

* Type 'mission.lela.mil' into your browser & click the laravel logo & the password will be revealed :)





