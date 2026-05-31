{
  "name": "Course",
  "type": "object",
  "properties": {
    "title": {
      "type": "string"
    },
    "category": {
      "type": "string"
    },
    "description": {
      "type": "string"
    },
    "image_url": {
      "type": "string"
    },
    "difficulty": {
      "type": "string",
      "enum": [
        "Beginner",
        "Intermediate",
        "Advanced"
      ]
    },
    "duration_hours": {
      "type": "number"
    },
    "rating": {
      "type": "number"
    },
    "skills": {
      "type": "array",
      "items": {
        "type": "string"
      }
    },
    "topics": {
      "type": "array",
      "items": {
        "type": "string"
      }
    },
    "trending": {
      "type": "boolean"
    },
    "enrolled_count": {
      "type": "number"
    }
  },
  "required": [
    "title",
    "category"
  ],
  "rls": {
    "create": {
      "user_condition": {
        "role": "admin"
      }
    },
    "read": {},
    "update": {
      "user_condition": {
        "role": "admin"
      }
    },
    "delete": {
      "user_condition": {
        "role": "admin"
      }
    },
    "write": {
      "user_condition": {
        "role": "admin"
      }
    }
  }
}
