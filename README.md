# Home Assistant Omnik Solar sensor component
Home Assistant Omnik Solar sensor component.

### Example entry for configuration.yaml
```
sensor:
  - platform: omni
    datasource: inverter_and_portal
    inverter_host: <ip address inverter>
    inverter_port: <port inverter>
    inverter_serial: <serial number inverter> (example 1234567603)
    portal_host: www.omnikportal.com
    portal_port: 10000
    portal_username: <username omnik portal>
    portal_password: <password omnik portal>
    scan_interval: 60
    sensors:
      actualpower: [energytotal, energytoday, invertersn]
      energytoday:
      energytotal:
      hourstotal:
      invertersn:
      temperature:
      dcinputvoltage:
      dcinputcurrent:
      acoutputvoltage:
      acoutputcurrent:
      acoutputfrequency:
      acoutputpower:
      incometoday:
      incometotal:
```
