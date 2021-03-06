# CHANGELOG

- v0.1.0-alpha.8 2016-10-05
  * Added cli command "zone-mta" to create and run ZoneMTA applications
  * Added API endpoint to check message status in queue
  * Added new plugin option (`app.addStreamHook`) to process attachment streams without modifying the message. This can be used to store attachments to disk or calculcating hashes etc. on the fly

- v0.1.0-alpha.5 2016-09-25
  * Allow multiple SMTP interfaces (one for 465, one for 587 etc)

- v0.1.0-alpha.4 2016-09-21
  * Added option to log to syslog instead of stderr

- v0.1.0-alpha.3 2016-09-21
  * Added plugin system to be able to easily extend ZoneMTA
  * Added plugin to use Rspamd for message scanning
  * Added plugin to send bounce notifications either to an URL or email address or both
  * Converted built-in HTTP calls to optional plugins (authentication, sender config etc)
  * Allow total or partial message rewriting through the rewrite API

- v0.1.0-alpha.2 2016-09-06
  * Added option to forward messages of a Zone not to MX but to another predefined MTA

- v0.1.0-alpha.1 2016-09-06
  * Initial release
