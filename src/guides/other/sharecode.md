{
  "name": "say",
  "description": "Bot powtarza wiadomość wpisaną przez użytkownika.",
  "type": 1,
  "options": [
    {
      "name": "message",
      "description": "Wiadomość, którą ma wysłać bot",
      "type": 3,
      "required": true
    }
  ],
  "actions": [
    {
      "type": "send-message",
      "channel": "channel",
      "message": "{{message}}",
      "tts": false,
      "embed": false
    }
  ]
}
