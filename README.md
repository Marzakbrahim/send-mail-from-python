# send-mail-from-python :
Using this code you can send mails from Python.
if they ever show you an error message like "SMTPAuthenticationError: (534, b'5.7.9 Application-specific password required. Learn more at\n5.7.9 
https://support.google.com/mail/?p=InvalidSecondFactorf24-20020a05600c491800b003df245cd853sm2763302wmp.44 - gsmtp')"
--> To resolve this error, follow these steps:

1-Go to the "Security" section of your Google Account.

2-Scroll down to the "Signing in to Google" section.

3-Click on the "App Passwords" link.

4-Follow the instructions to generate an application-specific password for the app that you're using (e.g. Python script).

5-Use the application-specific password in your Python script instead of your regular Gmail password.
