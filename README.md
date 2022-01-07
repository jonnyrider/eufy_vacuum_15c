# eufy_vacuum_g10
Integration with Home Assistant for the Eufy RoboVac G10

Add the following to your configuration.yaml:

eufy_vacuum_g10:
  devices:
  - name: Robomop
    address: <ip address>
    access_token: <access token>
    id: <id>
    type: T2118    
    
 Copy the contents of the eufy_robovac_g10 folder to custom_components/eufy_vacuum_g10 in your home assistant configuration directory. 
 
 Restart Home Assistant.
