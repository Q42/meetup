# meetup
Notes for the DAUG meetup

Hue REST api documentation: https://www.developers.meethue.com/documentation/getting-started

Bridge ip adress:  `10.42.39.194`

API Debug Tool: http://10.42.39.194/debug/clip.html

Volledige config: http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2
Aangesloten lampen op de bridge: http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights

Lamp laten knipperen: 
```
curl --request PUT \
  --url http://10.42.39.194/api/vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2/lights/4/state \
  --header 'cache-control: no-cache' \
  --header 'postman-token: 951fa20e-43ae-3def-3a00-c3ecaf19dff1' \
  --data '{"alert": "select"}'
```

User for Hue Bridge:
`vJB9Z1Q-SnW2Lunvzohsn2O17yVq8kqfhsHnNNa2`
