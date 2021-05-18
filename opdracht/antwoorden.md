# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM races JOIN circuits WHERE races.year = '2018'
2. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM races JOIN constructor_standing WHERE races.year = '2017'
3. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM pitstops LEFT JOIN drivers ON drivers.surname = surname WHERE duration < 25
4. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM constructors LEFT JOIN races ON races.date = date WHERE constructors.name = 'Mclaren' AND races.year = '2010'
5. Copy paste je gemaakte SQL query hieronder
   SELECT races.name, year, circuits.name, circuits.country, drivers.surname FROM races LEFT JOIN circuits ON races.circuitId = circuits.circuitId LEFT JOIN driver_standing ON races.raceId = driver_standing.raceId LEFT JOIN drivers ON driver_standing.driverId = drivers.driverId WHERE year = 1950 AND drivers.surname LIKE "f%"+
