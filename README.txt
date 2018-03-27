INSTALLATION
Run the following command to install dependencies:


   sudo yum install numpy scipy python-matplotlib ipython python-pandas sympy
   python-nose pyaudio


INSTRUCTIONS
To run the program, type into the command line python shazam.py


The menu you see is the average user menu. The options are listed below.


1. Match a song from file - Selecting this option will prompt you for a file path and it will match against it.
2. Match a song from microphone - Selecting this option will prompt you to record a sample, it will then match the recorded sample. 
If you press r after each match, you can see a list of related songs


If you press “a” at the main menu, this pulls up the admin panel, which is used for managing the library and testing the code. 
1. Cache a current library - Use the function to cache the current library for posterity. 
2. Import directory of songs to library - As described
3. Remove song from library - As described
4. Test match on a file or directory - This allows you to run a battery of tests on a directory of songs.
5. Force library save - This forces the library to save and quite. 


The library contents are located in library_list.txt.