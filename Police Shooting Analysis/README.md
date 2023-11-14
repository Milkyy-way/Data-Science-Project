# ABOUT
This is a punchline report. The shootings in the USA have increased almost exponentially in recent years. The data that I collected has information about the shooting from the year 2015 until the latest week in all counties of the USA. The data collected from the dataset are geographical locations of shootings, armed status of the victim, flee status, weapon carried by the victim, name, place (county, state, city), date, race, etc. From the above-mentioned information.

# About the data
The file fatal-police-shootings-data.csv contains data about each fatal shooting in CSV format.

##### id: a unique identifier for each victim
##### name: the name of the victim
##### date: the date of the fatal shooting in YYYY-MM-DD format
##### manner_of_death: shot shot and Tasered
##### armed: indicates that the victim was armed with some sort of implement that a police officer believed could inflict harm
##### undetermined: it is not known whether or not the victim had a weapon
unknown: the victim was armed, but it is not known what the object was
unarmed: the victim was not armed
##### age: the age of the victim
##### gender: the gender of the victim. The Post identifies victims by the gender they identify with if reports indicate that it differs from their biological sex.
M: Male
F: Female
None: unknown
##### race:
W: White, non-Hispanic
B: Black, non-Hispanic
A: Asian
N: Native American
H: Hispanic
O: Other
None: unknown
##### city: the municipality where the fatal shooting took place. Note that in some cases this field may contain a county name if a more specific municipality is unavailable or unknown.
##### state: two-letter postal code abbreviation
##### signs of mental illness: News reports have indicated the victim had a history of mental health issues, expressed suicidal intentions or was experiencing mental distress at the time of the shooting.
##### flee: News reports have indicated the victim was moving away from officers
Foot
Car
Not fleeing
The threat column and the fleeing column are not necessarily related. For example, there is an incident in which the suspect is fleeing and at the same time turns to fire at gun at the officer. Also, attacks represent a status immediately before fatal shots by police while fleeing could begin slightly earlier and involve a chase.
##### body_camera: News reports have indicated an officer was wearing a body camera and it may have recorded some portion of the incident.
##### latitude and longitude: the location of the shooting expressed as WGS84 coordinates, geocoded from addresses. The coordinates are rounded to 3 decimal places, meaning they have a precision of about 80-100 meters within the contiguous U.S.
##### is_geocoding_exact: reflects the accuracy of the coordinates. true means that the coordinates are for the location of the shooting (within approximately 100 meters), while false means that coordinates are for the centroid of a larger region, such as the city or county where the shooting happened.
