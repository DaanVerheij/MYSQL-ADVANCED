# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE game.name LIKE "b%"
   
2. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE game.year LIKE "2013%"

3. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE genre.genre LIKE "Puzzle%"

4. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, game.year, genre.genre, game.jp_sales FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE game.name LIKE "Mario%"

5. Copy paste je gemaakte SQL query hieronder
   SELECT game.name, platform.platform, genre.genre, game.year FROM game LEFT JOIN platform ON game.platform_id = platform.id LEFT JOIN genre ON game.genre_id = genre.id WHERE platform LIKE "Pc%"

