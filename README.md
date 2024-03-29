### sky-script: a non-instrusive solution for playing instruments in the game "Sky: Children of the Light"
fully functional with Google Pixel 2XL and QtScrcpy-win-x64-v1.6.0 and Java 16 on Windows 10.

### Repo structure
|-Json2Vbs.jar: for converting notes (in JSON) to VB scripts

|-sky.json:key map used by QtScrcpy

|-notes/: notes

|-vbs/: generated VB scripts

### How to play
1. enable developer mode on the phone, and enable debugging
2. connect the phone to your computer
3. put "sky.json" under the ./keymap of QtScrcpy
4. run QtScrcpy, let it recoginize the phone, and load the key map
5. run "java -jar Json2Vbs.jar <note_file>", you will get a VB script called "<note_file>.vbs"
6. run your generated "<note_file>.vbs" and enjoy it
