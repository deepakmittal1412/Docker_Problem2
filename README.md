This is docker solution for runnung an instance of Mediawiki. 
The mediawiki will be running on one container and it is backed by mysql which is running on different container.
To run this, you may need to follow following steps.
1. Install Docker on the machine 
	Please follow https://docs.docker.com/v17.12/install/ for installation.
2. Download this repository to your machine
3. Go to the directory and opne the terminal there or go to the directory using path
4. Run the command
	docker-compose up 
5. After the process, open the browser and goto
	http://localhost:8080
6. Setup the instance
7. After initiall setup, download LocalSettings.php and move to the same directory where this yaml file is present.
8. Use following commands to restart the service
	docker compose down
	docker compose up
9. Login to
	http://localhost:8080
