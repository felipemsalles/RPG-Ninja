## RPG Ninja - Mobile Devices Laboratory 2022.1

### Overview
RPG Ninja is a mobile application developed as part of the Mobile Devices Laboratory course (2022.1). The project is designed as a multiplayer Android game where players can compete in different arenas. The game uses OneSignal for player invitations and Firebase to manage and distribute players across various arenas.

### Features
Player Invitations with OneSignal: Use OneSignal to invite players to join the game.
Multiplayer Arenas with Firebase: Players are distributed across different arenas (or scenarios) via Firebase. Each arena can hold a maximum of 2, 3, or 4 players (configurable), with the option for players to switch arenas during the game.
Inactive Player Cleanup: The game automatically removes inactive players to ensure smooth gameplay.
User Data Management: Players can edit their personal data (email, nickname, etc.) through a user interface built with LibGDX.
Path Planning for Movement: Players can only walk along predefined paths using a path-planning algorithm.

### Deliverables

Executable App (.apk): A fully functional Android application.
Demonstration Video: A video demonstrating the gameplay on a real Android smartphone.
Project ZIP: A ZIP file containing the project (excluding the build folders).

### How to Play

Install the APK on your Android device.
Launch the app and register by providing an email and nickname.
Invite friends using OneSignal or join an existing arena.
Play in arenas with up to 4 players, switching arenas as needed.
Enjoy the game and strategize your movements along the designated paths.
