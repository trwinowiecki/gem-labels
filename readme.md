# Gem Labels

HTML view for printing labels in json formatted data

## JSON

```json
[
  {
    "name": "Name of gem, i.e. 'Quartz'",
    "description": "Stone properties, i.e. 'Strength - Intuition ....'",
    "quantity": 0 // Number of labels to print of this type
  }
]
```

## HTML

Start a webserver on port 8080 to have access to the json file

```bash
python -m http.server 8080
```
