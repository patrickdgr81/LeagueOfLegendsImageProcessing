# LeagueOfLegendsImageProcessing
This project will take a screenshot of League of Legends and find out where the enemy champions are located. Uses opencv pattern matching.

Compile with 
g++ LeaguePatternMatch.cpp -lopencv_core -lopencv_highgui -lopencv_imgproc

To run with GPIO, compile with
 g++ -O2 -Wall LeaguePatternMatch.cpp -lopencv_core -lopencv_highgui -lopencv_imgproc SimpleGPIO.cpp -o LeaguePatternMatch

