# Java Media Player

Java Media Player is a simple multimedia player application developed in Java, utilizing the Java Media Framework (JMF) library. It allows users to play media files stored locally or fetched from a database.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Database Configuration](#database-configuration)
- [Contributing](#contributing)


## Prerequisites

Make sure you have the following software installed on your machine:

- **Java Development Kit (JDK)**
- **MySQL** (for database functionality)

## Getting Started

1.Set up your MySQL database:

- **Create a database named MediaPlayerDB5.**
- **Configure the database connection details in the:**
  + **initMediaPlayerFromDatabase method of the MediaPlayer class.**

2.Compile the Java code:
```

javac -cp .:path/to/jmf.jar JavaApplication3/proj/MediaPlayer.java

```
3.Run the application:
```

java -cp .:path/to/jmf.jar JavaApplication3.prog.MediaPlayer

```

## Usage

- **Click the "Play," "Pause," and "Stop" buttons to control media playback.**
- **Select a media file from the provided list to play it.**
- **The media files and their paths are stored in the MediaFiles table in the database.**

## Database Configuration

The database connection details are located in the initMediaPlayerFromDatabase method of the MediaPlayer class. Update the following lines with your MySQL database information:
```

String dbUrl = "jdbc:mysql://localhost/MediaPlayerDB5";
String dbUser = "Your Username";
String dbPassword = "Your Password";

```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



