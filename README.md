# Baseball Team Updater
### This is a program that allows baseball player information to be updated and then saved back to file.

To Run:

Load the project in visual studio, choose BaseballTeamUpdater.sln as the startup item.

The program will prompt user to enter in the initials for a given MLB team and then will generate a list of players from that team that the user can choose from.

The user then enters the specific player's name, this is case sensitive, and then will be given the player's Name, Team, Position, Weight, Height, and Age.

The user will them be prompted to update the player's team and weight.

The player's updated profile will then be displayed, and then the user can save it back to mlb_players.csv.

The program files included are Program.CS, UIClass.cs, ListMaker.CS, and ListMaker.CS. The .csv file is mlb_players.csv.

The program utilizes the CsvHelper library.