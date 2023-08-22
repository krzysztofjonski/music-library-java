# music-library

In this project, your task will be to create a console application to manage a music library. The application should include the following features:

Add Songs: Allow the user to add songs to the library. The user should be prompted to enter the name of the song, the artist, and the duration of the song in seconds.

View Library: Allow the user to view the current library of songs. The list should be displayed in alphabetical order by artist name.

Search Songs: Allow the user to search for songs by artist name. The user should be prompted to enter the name of the artist, and the application should display a list of all songs by that artist.

Remove Song: Allow the user to remove a song from the library. The user should be prompted to enter the name of the song to remove.

Clear Library: Allow the user to clear the entire library of songs.

A list with 30 random songs have been provided for you in the starter code, in a private static final field called songs in the Application class. You can use these to initialize your library.

You can choose what type of collection you wish to use to manage the songs in the library.

Please keep in mind the architectural principles you've acquired in the Basic Architecture section of this chapter. Your application should:

satisfy the Single Responsibility Principle,
use the Interface Segregation Principle,
use Dependency Injection,
include logging of the operations,
follow Clean Code Principles.

1.Create a Logger component
Create a flexible logger component that can target various outputs. Implement at least a console logger.


2.Create the Library component
Create the Library component and implement its features according to the requirements above.


3.Finish the UI component
Finish the implementation of the UI component that facilitates the communication between the user and the application.


4.Main program
Implement the main method in the Application to work with your newly created components and kick off the program flow.