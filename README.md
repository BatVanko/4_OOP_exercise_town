# 4_OOP_exercise_town
Create a class Town. The __init__ method should receive the name of the town (string). Each town has a latitude - "0°N" upon initialization and a longitude - "0°E" upon initialization. It should also have 3 more methods:
•	set_latitude(latitude) - sets an latitude
•	set_longitude(longitude) - sets an longitude
•	__repr__ - returns a representation of the object in the following string format:
"Town: {name} | Latitude: {latitude} | Longitude: {longitude}"

Test Code
town = Town("Sofia")
town.set_latitude("42° 41\' 51.04\" N")
town.set_longitude("23° 19\' 26.94\" E")
print(town)

Output
Town: Sofia | Latitude: 42° 41' 51.04" N | Longitude: 23° 19' 26.94" E
