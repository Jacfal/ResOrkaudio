This repository is fork of the [OREKA GPL](http://oreka.sourceforge.net/) project.

Changes in compare with original OREKA GPL project:

* new bunch of info messages which are sent to orktrack (i have my own implementation of orktrack which know how to work with this messages)
    * "callsetupstart" command is sent when INVITE message of certain call is caught on orkaudio
    * "callsetupcomplete" command is sent when 3-way-handshake end with ACK message
    * "callcancel" command is sent when 3-way-handshake end with CANCEL message
    * "callend" command is sent when BYE message of certain call is caught on orkaudio
