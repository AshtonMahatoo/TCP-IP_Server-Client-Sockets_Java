## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

How to run this program!!! 

1. Open 3 different command line windows.
2. Navagate to the file were this program is located in each command line window.
3. Compile each Java files in its own command line window.  
    javac Router.java
    javac Server.java 
    javac Client.java.

4. Start the Server, Router, and Client, in this order in there respective window!!: 
    java Server.java
    java Router.java 
    java Router.java

Process for the txt.file!!!
The client will send the specified file (file_to_send.txt) to the server via the router. 
The server will receive the file, (received_file.txt), and send a response back. 

Process for the Sound Wave File!!!
The server will send the specified sound file (sound_file.wav) to the client via the router. 
The client will receive the sound file and save it as (received_sound.wav.)