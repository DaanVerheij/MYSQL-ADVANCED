# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT races.year, circuits.name, races.name
   FROM races 
   LEFT JOIN circuits ON circuits.circuitId = races.circuitId 
   WHERE races.year = "2018"

2. Copy paste je gemaakte SQL query hieronder
   SELECT races.name, races.year, driver_standing.points, drivers.surname
   FROM races
   LEFT JOIN driver_standing ON races.raceId = driver_standing.raceId
   LEFT JOIN drivers ON driver_standing.driverId = drivers.driverId
   WHERE races.year = 2017 AND driver_standing.points = 10'

3. Copy paste je gemaakte SQL query hieronder
   SELECT drivers.forename, drivers.surname, pitstops.duration
   FROM drivers
   LEFT JOIN pitstops ON drivers.driverId = pitstops.driverId
   WHERE pitstops.duration < 25

4. Copy paste je gemaakte SQL query hieronder
   SELECT constructors.name, races.year, races.name
   FROM races
   LEFT JOIN constructor_standing ON races.raceId = constructor_standing.raceId
   LEFT JOIN constructors ON constructor_standing.constructorId = constructors.constructorId
   WHERE constructors.name = 'Mclaren' AND races.year = 2010
   
5. Copy paste je gemaakte SQL query hieronder
   SELECT races.name, year, circuits.name, circuits.country, drivers.surname FROM races LEFT JOIN circuits ON races.circuitId = circuits.circuitId LEFT JOIN driver_standing ON races.raceId = driver_standing.raceId LEFT JOIN drivers ON driver_standing.driverId = drivers.driverId WHERE year = 1950 AND drivers.surname LIKE "f%"+
