# python-email-sender

This is an automatic e-mail sender using Python. 

## Dependencies

* Python 3.7+
* smtplib
* email

## Installation

To get started, download and put "email_sender.py" under the folder that contains your project files that send emails.

## Usage

An example usage inside a project is given below.

```
from email_sender import EmailSender

receiver_email = "jane.doe@example.com"
subject = "The first e-mail"
message_body = "This is a body of the message."
attachments = ["image.png", "output.pdf"]

email_sender = EmailSender("john.doe@example.com", "Pswrd!0001")
email_sender.send_email(receiver_email, subject, message_body, attachments)

```
## References

* https://towardsdatascience.com/automate-email-with-python-1e755d9c6276
* https://medium.com/@bakiiii/automatic-e-mail-sending-with-python-eb41855119e1
* https://realpython.com/python-send-email/

## License

This work is published under [MIT](https://github.com/sefaburakokcu/python-email-sender/blob/master/LICENSE) License.



