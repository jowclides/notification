** Email Notification Library using phpMailer. **

This library has the function of sending e-mail using the phpmailer library. Doing this in an uncomplicated way is essential for any system.

**  To install the library, run the following command: ** 

```

composer require jowclides/notification

```

To make use of the library, simply require the autoload of the composer, invoke the class and make the method call:

```
<? php

require __DIR__ . '/vendor/autoload.php';

USE Notification\Email;

$mail = new Email (2, "mail.host.com", "your@email.com", "your-pass", "smtp secure (tls / ssl)", "port (587)", "from@email.com", "From Name");

$email-> sendEmail ("Subject", "Content", "reply@email.com", "Replay Name", "address@email.com", "Address Name");

```



Note that the entire configuration of sending the email is using the magic method builder! Once you've invoked the constructor method within your application, your system will be able to fire the shots.

** Studants **

Emerson P. Silva - CEO and Founder Coupled Tecnologia from https://www.coupled.com.br

João Loriato - CEO and Founder Coupled Tecnologia from https://www.coupled.com.br

Hudson P. Silva - CEO and Founder Coupled Tecnologia from https://www.coupled.com.br

** Developers **

Gustavo Web - Developer of this library and tutor of the course Composer in the Practice!

Robson V. Leite - CEO and Founder UpInside Treinamentos

UpInside Treinamentos - Official site of your digital marketing and programming school

phpMailer - Lib to send Email

License

MIT

** Plus One UpInside Training Courses, Make Good Use! **