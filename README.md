# Alexa Voice Service

Connecting to Alexa amazon services with Raspberry Pi

## Requirements

You will need:
    - Raspberry Pi (Rasbian operating system)
	- SD Card 
    - USB Sound microphone
    - HDMI Cable
	- Ethernet Cable
	
	![GitHub Logo](/images/logo.png)
Format: ![Alt Text](C:\Users\Filiz\Desktop\Gömülü Sistemler\resimler)

## Steps to be taken

    - Open raspberry pi terminal (in Rasbian)
	- Type "cd/opt" command
    - Type "sudo apt-get install git"
    - Clone clusters with this extension "sudo git clone https://github.com/filizdalip/Alexa-Voice-Service"
	- Enter the information of the product you created on the terminal via https://developer.amazon.com/
	- We are installing the "sudo ./AlexaPi/src/scripts/setup.sh" file
	- Finally, we make the necessary settings from the sudo raspi-config screen and reboot the raspberry pi.