# rishivalley_student

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Reporting to Learning Record Store

Student application tracks user's experience over activities/tasks through specifications of Experience API (TinCanAPI/XAPI). A specific set of events/actions would be tracked and reported to LRS, detailed below.

### LRS Endpoint to post a statement
http://rishivalley.lrs.com/statements (actual endpoint will be replaced here)
Method: POST

### Statement Model:
```json
{
  "actor": {
    "id": "001",
    "type": "student/teacher",
    "name": "Student Name"
  },
  "verb": {
    "id": "http://adlnet.gov/expapi/verbs/attempted",
    "action": "attempted"
  },
  "object": {
    "milestone": "",
    "activity": "",
    "task": "",
    "objectType": "Activity"
  },
  "class": "Class1",
  "subject": "English"
}
```
"# rishi_valley_student" 
