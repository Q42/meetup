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

Make a light blink:

    curl --request PUT \
      --url http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights/4/state \
      --data '{"alert": "select"}'

Lampen indeling bij Q42:

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
