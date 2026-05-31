{
  "name": "StudySession",
  "type": "object",
  "properties": {
    "course_id": {
      "type": "string"
    },
    "topic": {
      "type": "string"
    },
    "minutes": {
      "type": "number"
    },
    "date": {
      "type": "string",
      "format": "date"
    }
  },
  "required": [
    "course_id",
    "minutes",
    "date"
  ]
}
