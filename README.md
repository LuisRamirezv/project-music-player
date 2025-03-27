## Project-music-player

This is a project to make a music player like Winamp

Preparing the project directory.
* First, we have to have the node folder with the electron nodes in our project directory, but at the same time, outside of this repository.(to avoid upload or clone 230mb all the time)

![image](https://github.com/user-attachments/assets/67e39fc8-b468-411c-b0e5-966497d6b0c4)

* Second, modify the package.json, adding a new script to rnu in the command prompt.

```json
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "electron ." 
  },
```
