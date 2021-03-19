This is a an extension for Drive Badger. It provides `exclude.list` file, containing a list of exclusions compatible with popular `rsync` program.

The purpose of these exclusions is to decrease the amount of data to be exfiltrated by Drive Badger, and thus to speed up the attack,
by eliminating files and directories, that are not valuable in any way to the attacker:

- additional browsers: Google Chrome, Opera
- communication software: Slack, WebEx, GoToMeeting
- remote work software: TeamViewer
- multimedia software: Corel, Gimp, IrfanView, Paint.NET, Windows Live, movie codecs
- movie streaming/editing software: MAGIX, OBS Studio
- productivity software: Evernote, Notepad++

### Installing

Clone this repository as `/opt/drives/config/exclude-software` directory on your Drive Badger persistent partition.

### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
