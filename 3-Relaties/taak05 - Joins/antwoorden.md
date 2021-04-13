# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM game LEFT JOIN platform ON game.platform_id = platform.id
2. Copy paste je gemaakte SQL query hieronder
   SELECT * FROM game JOIN platform ON platform.id = game.platform_id WHERE game.id < 11
3. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform FROM game JOIN platform ON platform.id = game.platform_id WHERE game.name = "Call of Duty: Advanced Warfare";
4. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform FROM game JOIN platform ON platform.id = game.platform_id LIKE game.name = 'Fifa%'
5. Copy paste je gemaakte SQL query hieronder
