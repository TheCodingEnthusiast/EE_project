## Back end - Application

##### End User- Parents/ Therepists

A) wifi
  1) wifi connection must be established between mobile application and the device. For this, parmanent wifi connection will be used
  2) The application must redirect to bluetooth connection page for the first pairing.
  3) For Bluetooth, appropriate error handeling must be  in case the device is not detected or paired.
  4) If the device gets disconnected while working, appropriate handling must be performed.
  5) If the application is connected to two devices, then only one device must be chosen. _(Edge case)_
  stop searching for new connections once connected.
  if application gets disconnected then the board must connect to same app and continue broadcasting
  for pairing with new device, restart device
  on restart it must clear pairing
  
B) Starting the Game
  1) The speed of the game must be set by the user. Speed will be in terms of colors per minute. It must range from 10 to 50 in steps of 2.
  2) Once the speed is set, it can be increased or decreased during the game in steps of 2. _(OPTIONAL)_
  3) The game duration must be set in minutes before the game starts and cannot be changed afterwards.
  4) game duration will be seen only in ui
  5) The score must be updated and shown to the user during the course of the game, updated every 5 seconds. _(OPTIONAL)_

C) Ending the game
  1) The game must end after the specified time is over.
  2) The final score must be displayed when the game is over.
  4) The progress must be shown in form of a graph done by application _(OPTIONAL)_



