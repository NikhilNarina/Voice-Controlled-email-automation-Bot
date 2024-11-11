Voice-Controlled Email Automation Bot (Python)

This project leverages Python’s speech recognition and email automation capabilities to create a voice-controlled email bot. By simply using voice commands, users can draft, send, and manage their emails hands-free. This bot integrates speech recognition to interpret voice commands and an SMTP (Simple Mail Transfer Protocol) client to send emails securely using starttls() for encryption.

Key Features:

Voice Command Support: Users can dictate email content, specify recipients, and control the email sending process through voice.
Speech Recognition: Built on Python’s speech_recognition library for converting spoken language into text.
Email Automation: Automates the process of sending emails using the smtplib library, with email subject, body, and recipient fields dynamically populated from voice input.
StartTLS for Secure Connection: Utilizes the starttls() method to upgrade the connection to a secure one using TLS (Transport Layer Security), ensuring encrypted communication with the SMTP server.
Custom Commands: Recognizes predefined voice commands such as "send email", "draft email", "list inbox", etc.
Error Handling: Includes checks for common errors like invalid email addresses or network issues during email transmission.


Technologies Used:

Python 3.x
SpeechRecognition library for speech-to-text conversion
smtplib for sending emails via SMTP
pyttsx3 (Text-to-Speech) for verbal feedback to the user
