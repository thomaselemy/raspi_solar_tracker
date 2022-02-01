# raspi_solar_tracker
sun tracker for a solar panel using the raspberry pi, 5 digital photoresistors (one in each corner with a L shaped shade + one for ambiant light if the sun goes down)
![Screenshot](https://user-images.githubusercontent.com/33559754/152070035-1a424a55-1921-4369-8780-51a5b0750cb6.jpg)

ps://www.youtube.com/watch?v=1mcSKFPuE6Q

# Installation 
sudo apt-get install pip

    git clone https://github.com/thomaselemy/raspi_solar_tracker.git
 
    sudo apt-get install python-pip
  
    sudo pip install pi-ina219
# To run
cd raspi_solar_tracker

    python suntracker.py

for moitoring power consumtion

      python power_monitoring.py
