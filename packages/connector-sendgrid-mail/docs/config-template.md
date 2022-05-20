```json
{
  "apiKey": "<api-key>",
  "fromEmail": "noreply@logto.test.io",
  "templates": [
    {
      "usageType": "SignIn",
      "type": "text/plain",
      "subject": "Logto SignIn Template",
      "content": "This is for sign-in purposes only. Your passcode is {{code}}.",
    },
    {
      "usageType": "Register",
      "type": "text/plain",
      "subject": "Logto Register Template",
      "content": "This is for registering purposes only. Your passcode is {{code}}.",
    },
    {
      "usageType": "Test",
      "type": "text/plain",
      "subject": "Logto Test Template",
      "content": "This is for testing purposes only. Your passcode is {{code}}.",
    }
  ]
}
```