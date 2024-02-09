Login Registrieren
Diese Dateien begleiten das Tutorial: Login- und Registrierungssystem mit PHP

E-Mails lokal versenden
Für alle, die lokal mit E-Mails zu kämpfen haben, empfehle ich dringend, https://mailtrap.io dies ist ein großartiger Dienst, um E-Mails abzufangen, wenn sie lokal arbeiten.

Um es einzurichten, öffnen Sie classes/phpmailer/mail.php und geben Sie die SMTP-Details ein:

Stellen Sie sicher, dass Sie den Benutzernamen und das Passwort eingeben, die Sie von mailtrap erhalten haben.

public $Host = 'smtp.mailtrap.io';
public $Mailer = 'smtp';
public $SMTPAuth = true;
public $Username = '';
public $Password = '';
//public $SMTPSecure = 'tls';

Sie benötigen Xampp zum öffnen und hosten der datei.
