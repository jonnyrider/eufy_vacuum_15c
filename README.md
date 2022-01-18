# Eufy Vacuum 15C Integration with Home Assistant

# Installation

Add the following to your configuration.yaml:
```
eufy_vacuum_15c:
  devices:
  - name: Robomop
    address: <ip address>
    access_token: <access token>
    id: <id>
    type: T2118    
   ``` 
 To get the access_token and id, download the Eufy app here: https://www.dropbox.com/s/bcwy6iqchydgexc/EufyHome_2.4.0_vevs.apk.zip?dl=0 and go to the vacuum settings where they are shown.
   
 Copy the contents of the eufy_robovac_15c folder to custom_components/eufy_vacuum_15c in your home assistant configuration directory. 
 
 Restart Home Assistant.
