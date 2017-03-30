# meetup
Notes for the DAUG meetup

Hue REST api documentation: https://www.developers.meethue.com/documentation/getting-started

Bridge ip adress:

    10.42.39.194

User for bridge:

    vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2

API Debug Tool: http://10.42.39.194/debug/clip.html

Full config: http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2

All the lights: http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights

## Update the state of a lamp:
    curl --request PUT \
      --url http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights/1/state \
      --header 'cache-control: no-cache' \
      --header 'postman-token: 99bdc85e-6d68-623c-4b22-77c90d103cd1' \
      --data '{\n	"on": true,\n	"sat": 254, \n	"bri": 254,\n	"hue": 65000\n}'
      
## Make a light blink:
    curl --request PUT \
      --url http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights/4/state \
      --data '{"alert": "select"}'

## Lampen indeling bij Q42:
    -----           -----
    | 3 |           | 7 |
    |   |           |   |
    | 2 |           | 6 |
    |   |           |   |
    | 1 |           | 5 |
    -----           -----

    ---------------------
    | 11   10    9    8 |
    ---------------------
