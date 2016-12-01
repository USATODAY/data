#Fatal Police Chases Data

The data file [fatal_pursuits_2013-2014.csv](fatal_pursuits_2013-2014.csv) contains a listing of every fatal police pursuit in the United States in 2013 and 2014. USA TODAY assembled the list using crash data reported to the National Highway Traffic Safety Administration as well as police reports, court documents and news accounts.

The records show that black people die in police chases at a rate far higher than do people of other races, and that deadly chases of black drivers were more likely to begin with officers observing seemingly minor offenses that posed little danger to the public. You can read USA TODAY’s investigation at [http://policechases.usatoday.com](http://policechases.usatoday.com).

##The Data Fields

- ST: The state in which the crash occurred (postal abbreviation)
- City: The city in which the crash occurred
- County: The county in which the crash occurred
- Mo: Month of the crash
- Date: Day of the crash
- Year: Year of the crash
- Time: Time of the crash, on a 24-hour clock. The colon is implied. So 207 is 2:07 a.m.
- Light: Light conditions at the time of the crash. 1 = daylight, 2 = dark, not lighted; 3 = dark, lighted; 4 = dawn, 5 = dusk, 6 = dark, unknown lighting, 9 = unknown light conditions
- Deaths: Number of people killed
- Latitude/Longitude: The coordinates of the crash
- Fleeing driver: The name of the driver who was being pursued
- FD race: The race of the fleeing driver
- FD age: The age of the fleeing driver
- FD sex: The sex of the fleeing driver
- FD dead: Indicates whether the fleeing driver was killed in the crash.
- Pursuing agency: The name of the law enforcement agency responsible for the pursuit.
- Trigger: The reason the police gave for initiating the stop that led to a chase.
- Source: Principal source of information for this chase
- Killed1/2/3/4: Name of the person or people killed in the crash, if not the fleeing driver
- Type1/2/3/4: Type of person. (BYS = bystander, FP = passenger in the fleeing vehicle, LEO = law enforcement officer)
- Race1/2/3/4: Race of the person or people killed in the crash
