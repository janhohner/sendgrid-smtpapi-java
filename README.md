SendGrid SMTP API for Java
==========================
Java port of SendGrid's PHP SmtpApiHeader library

Copyright and License
---------------------
Copyright (c) 2012, Jan Hohner.  This project is provided under
a triple license that allows you to select the license that is best for your 
needs. You may choose from:

- [The GNU GPL v2.0](http://www.gnu.org/licenses/gpl-2.0.html)
- [The GNU GPL v3.0](http://www.gnu.org/licenses/gpl-3.0.html)
- [The MIT License](http://www.opensource.org/licenses/MIT)

Requirements
------------
This library needs the Jackson JSON processor. You can get it 
[here](http://jackson.codehaus.org/).

Using this library
------------------
1. Create a SmtpApiHeader object
2. Create your message as you are used to
3. Add any information you want to the SmtpApiHeader object
4. Call asJSON() to get the JSON representation of all information you put into 
   the object
5. Add this JSON string to a SMTP header called X-SMTPAPI
6. Send the mail.

Contributors
------------
- [SendGrid](http://www.sendgrid.com) - initial PHP version of this library
- [Jan Hohner](http://www.janhohner.de) - this version

How to contribute
-----------------
1. Clone this repository
2. Improve it (add yourself to this file)
3. Submit a pull request

Bugs
----
If you find any bugs, please report them to the issue tracker at 
[GitHub](https://github.com/janhohner/sendgrid-smtpapi-java/issues)