* sqlite3 db/chinook.db .tables
* .tables '%s'
* .schema albums
* .fullschema
* SELECT * FROM tracks
* SELECT albumID FROM albums LIMIT 10 ORDER BY artistID ASC
* SELECT nom FROM tracks LIMIT 10 ORDER BY albumID ASC
* SELECT nom FROM tracks LIMIT 10 WHERE albumID = 1
* SELECT nom FROM tracks LIMIT 10 WHERE albumID = 1 AND duree > 252980
* SELECT nom FROM tracks LIMIT 10 WHERE type IN (1,2)
* SELECT id, nom FROM artists LEFT JOIN albums ON artists.id = albums.id ORDER BY albumID ASC