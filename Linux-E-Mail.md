# Linux-E-Mail

## MTA Servers 
* http://postfix.org/
* sendmail.org - https://www.proofpoint.com/us/products/email-protection/open-source-email-solution 
* https://www.exim.org/ 
* Qmail – http://cr.yp.to/qmail.html
* OpenSMTPD – https://www.opensmtpd.org/
* Haraka – https://github.com/haraka/Haraka - Haraka is a highly scalable node.js email server with a modular plugin architecture. Haraka can serve thousands of concurrent connections and deliver thousands of messages per second. Haraka and plugins are written in asynchronous JS and are very fast. 
* https://github.com/mistralmail/mistralmail MistralMail will be a production-ready, and easy to setup mail server. It consists of an SMTP server (both MSA and MTA) and an IMAP server all bundled in one executable (or just in one Docker image) with auto-generated TLS certificates.  *WIP: MistralMail is far from being production-ready* 
* Zone-MTA Outbound SMTP relay (MTA/MSA) built on Node.js and MongoDB (queue storage) https://github.com/zone-eu/zone-mta 
* Courier – https://sourceforge.net/projects/courier/
* https://github.com/albertito/chasquid - https://blitiri.com.ar/p/chasquid/monitoring/ "chasquid is an SMTP (email) server with a focus on simplicity, security, and ease of operation. It sends and receives email as a typical MTA (for example, can be used instead of Postfix or Exim), and it is designed mainly for individuals and small groups. It's written in Go"
* vSMTP "a next-gen mail transfer agent (MTA) written in Rust. Faster and Greener".  https://github.com/PMPetra/vSMTP https://viridit.com/providers-edition/ 
* notqmail "The collaborative Open Source successor to qmail and netqmail" https://github.com/notqmail/notqmail
* kumomta "The first Open-Source high-performance MTA developed from the ground-up for high-volume email sending environments" https://github.com/KumoCorp/kumomta
* emersion/go-smtp "An ESMTP client and server library written in Go"  https://github.com/emersion/go-smtp
* ZMailer (was great for mail gateways, outbounding/routing, but it's dead) https://www.zmailer.org/overview.html

See also: [Wikipedia: Comparison of mail servers](https://en.wikipedia.org/wiki/Comparison_of_mail_servers) 

## List of popular Linux nullmailers (locally behave as MTA, but not real ones)
 
* Nullmailer – http://untroubled.org/nullmailer/
* sSMTP – https://github.com/Raymonds84/ssmtp
* esmtp – http://esmtp.sourceforge.net/
* mSMTP – https://marlam.de/msmtp/
* mini_sendmail – https://acme.com/software/mini_sendmail/
* nbsmtp – https://nbsmtp.ferdyx.org/
* smtp-cli – https://github.com/mludvig/smtp-cli
* smtp-forwarder – https://github.com/agentzh/smtp-forwarder
* sendEmail – http://caspian.dotconf.net/menu/Software/SendEmail/
* sendEmail-SSL-wrapper – https://github.com/wildsau/sendEmail-ssl-wrapper
* calmh/smtpcat https://github.com/calmh/smtpcat

## Mail server emulators - for developers 
* MailHog is an email testing tool for developers https://github.com/mailhog/MailHog 
* MailCatcher runs a super simple SMTP server which catches any message sent to it to display in a web interface. Run mailcatcher, set your favourite app to deliver to smtp://127.0.0.1:1025 instead of your default SMTP server, then check out http://127.0.0.1:1080 to see the mail that's arrived so far. https://mailcatcher.me/
* Blackhole " is an MTA written on top of asyncio, utilising async and await statements that dumps all mail it receives to /dev/null" https://github.com/kura/blackhole


## Mail related distributions / add-ons

See also https://en.wikipedia.org/wiki/List_of_mail_server_software#Mail_server_packages 

* https://modoboa.org/en/ // https://github.com/modoboa/ (Debian based add-on - also Ubuntu, POP or Kali)
* https://www.iredmail.org/  (add on for  CentOS Stream, Rocky, Alma, Debian, Ubuntu, FreeBSD, OpenBSD)
* https://www.zimbra.com/
* Mail-in-a-Box helps individuals take back control of their email by defining a one-click, easy-to-deploy SMTP+everything else server: a mail server in a box. [github.com/mail-in-a-box/mailinabox](https://github.com/mail-in-a-box/mailinabox/) 
* [mailcow.email](https://mailcow.email/)
* Mailu is a simple yet full-featured mail server as a set of Docker images.  [https://mailu.io/2.0/](https://mailu.io/2.0/)
* Poste.is is dockerized full blown mail server based on Haraka, Dovecot and nginex [poste.io](https://poste.io/)

