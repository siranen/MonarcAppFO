MONARC Changelog
================


## 2.0.4 (2017-10-27)

### Fix

- fix a bug with salted passwords that prevented users to update their
  password. Users may have to use the password recovery functionality (zm-core)
  Reported by Nicolas SCHWARTZ, Cyber Security Team of PwC Luxembourg.
- set default deliveries in english (zm-client);
- block the probability in the threat assessment in 1.2 of the method (ng-anr);


## 2.0.3 (2017-10-13)

### Fix

- set default deliveries in english.
- Set NewCenturySchlbk-Roman Imagick font.


## 2.0.2 (2017-10-10)

### New

- MONARC is now available in Dutch.

### Enhancement

- updated German translations.
- updated the font used for the images in the generated reports.
- minor improvements in the configuration.

### Fix

- Lost operational risk when importing from MONARC Common DB (#32)
- PHP Notice: Use of undefined constant i (#33)


## 2.0.1 (2017-08-28)

### Enhancement

- Auto-complete function in the creation of a specific risk (#29)
- Remove the category for operational risk (#26)
- update of the database
- the database of MONARC is now backed up before an upgrade

### Fix

- Import bug : Format of duedate in recomandation (#30)
- Problem when a label of an impact contains a character such as '&' or '%' (#24)
- Lost operational risks of assets in library after a snapshot (#25)
- Problem setting a comment in new scale row (#24)
- hash of users' passwords were exposed through the API as reported by
  Thomas LARCHER, Cyber Security Team of PwC Luxembourg.


## 2.0.0 (2017-08-07)

### Other

- initial release of the version 2.0.0 of MONARC;
- project source code is now hosted at https://github.com/monarc-project
