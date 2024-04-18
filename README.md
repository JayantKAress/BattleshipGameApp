# BattleshipGameApp
 
# Added Documentation with .PDF file for the code at location ....\BattleShipStateTracker\Documentation\
# Added Postman Collection with .json file for the api at location ....\BattleShipStateTracker\Documentation
 
# Function app end point:
# Create board - https://jayantkbattleshipcodingtest.azurewebsites.net/api/CreateBoard
# Add Ships - https://jayantkbattleshipcodingtest.azurewebsites.net /api/AddShip
# Need to Pass TotalShips from Json body
# Ex. {"TotalShips":1}
# Show Board - https://jayantkbattleshipcodingtest.azurewebsites.net /api/ShowBoard
# Fire Ship - https://jayantkbattleshipcodingtest.azurewebsites.net /api/FireShip
# Need to Pass board coordinates from Json body
# Ex.
# {
# "Xcordinate":4,
# "Ycordinate":7
# }
# Restart Game - https://jayantkbattleshipcodingtest.azurewebsites.net /api/RestartGame
 
# Steps to test:
# Step 1 – Call Create board end point from postman.
# EX: https://jayantkbattleshipcodingtest.azurewebsites.net/api/CreateBoard
# Add Ships - Call Add Ships end point from postman
# EX: https://jayantkbattleshipcodingtest.azurewebsites.net /api/AddShip
# Show Board – Call Show Board end point to view position which you want to hit
# Fire Ship – Call Attack Ship end point from postman and pass the Position as displayed on board
# EX: https://jayantkbattleshipcodingtest.azurewebsites.net /api/FireShip
# Need to Pass board coordinates from Json body
# {
# "Xcordinate":4,
# "Ycordinate":7
# }
# Restart Game – If you won the game you need to call this API to restart the game and follow the steps again
 
