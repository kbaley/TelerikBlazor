To diagnose an issue with binding values to a TelerikTextBox in an EditForm in a Blazor server project.

### To reproduce

- Launch the application
- Go to the Auth Required page
- Enter an email address and password and submit

An error will appear that an email address is required. If you remove the `[Required]` attribute, it will submit but the email address you enter won't propagate to the Input model.
