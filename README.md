NOTES
=====

- Import config
  To trigger an import on startup place a file called .vorta-init.json in the user’s home directory. 
  During the next startup, Vorta will import and then delete this file.
- Eventuell muss auf einem neuen Gerät einmalig ein Login per SSH erfolgen!
- Falls das Repository noch nicht besteht, muss es einmal über Vorta angelegt werden
- borg_pw wird zum Entschlüsseln des Repos verwendet und ist daher user-spezifisch!
- ssh-keys werden zum login des borg-backup users verwendet, sind global und werden im Home-Verzeichnis des Users gespeichert.

TO DO
=====

- add autostart