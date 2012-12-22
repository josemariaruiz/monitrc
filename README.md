monitrc
=======
Some template config files for me. Include MongoDB, Redis, MySQL, Sidekiq and so on.

Enjoy it!

## Usage


1. Install monit

   For mac with homebrew

	```
	$ brew install monit
	```
	
   For Ubuntu
   
   ```
   $ sudo apt-get install -y monit
   ```
   
2. Copy config files
   
   ```
   $ mv /path/to/monit /etc/monit
   ```
   
3. Reload monit
   
   ```
   $ monit reload
   ```
   
   Or you can
   
   ```
   $ monit quit
   $ monit -c /etc/monit/monitrc
   ```