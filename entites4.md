{
  "name": "UserProgress",
  "type": "object",
  "properties": {
    "course_id": {
      "type": "string"
    },
    "progress_percent": {
      "type": "number"
    },
    "completed_topics": {
      "type": "array",
      "items": {
        "type": "string"
      }
    },
    "streak_days": {
      "type": "number"
    },
    "total_study_minutes": {
      "type": "number"
    },
    "last_studied": {
      "type": "string",
      "format": "date-time"
    },
    "notes": {
      "type": "string"
    }
  },
  "required": [
    "course_id"
  ]
}
