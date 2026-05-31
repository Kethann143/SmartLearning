# SmartLearning
{
  "name": "Achievement",
  "type": "object",
  "properties": {
    "title": {
      "type": "string"
    },
    "description": {
      "type": "string"
    },
    "icon": {
      "type": "string"
    },
    "unlocked": {
      "type": "boolean"
    },
    "unlocked_date": {
      "type": "string",
      "format": "date-time"
    }
  },
  "required": [
    "title"
  ]
}
