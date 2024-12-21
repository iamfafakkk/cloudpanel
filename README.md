v2.5.0 - [2024-11-26]
New

PHP 8.4 Support
MariaDB 11.4 Support
Translations: Hungarian, Slovak, Thai
Bug Fixes

#471 username error
#476 Shebang incorrect in /usr/bin/clpctl
#484 Unexpected brackets at the beginning of files
#500 Custom cron commands are not working
#505 Web based File Manager does not upload files
#511 .well-known directory deleted after certificate renew
#527 Unable to login with site user via ssh key when ftp user is created (Thanks to ccMatrix)
#530 File permissions revert to 0770 after file modification
#535 "Additional Configuration Directives" doesn't allow for spaces in value
#540 S3 backup - Region - Middle East (UAE) me-central-1 missing
Translation Fixes
Enhancements:

New AWS regions for S3 remote backup
Security:

Privilege Escalation from clpctlWrapper command (Yell Phone Naing) (HIGH)
Privilege Escalation: Site User Access Allows Linux Password Changes (HIGH) (Yell Phone Naing)
Server IP disclosure despite using Cloudflare (Yell Phone Naing)
