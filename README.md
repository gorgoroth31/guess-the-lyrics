- app, bei der zunächst eine Spotify-Playlist eingegeben wird
- Dann wird ein zufälliger Song ausgewählt
- Dann wird über die Musixmatch - API der Text gezogen (Wenn die Lyrics nicht vorhanden sind, dann wird ein anderes Lied ausgewählt)
- Dann wird eine Song-Zeile extrahiert
- Der Nutzer muss Songname und Interpret erraten -> Fehlertoleranz mit lowercase oder so
- Nach 3 falschen Guesses wird der Anfangsbuchstabe des Interpreten verraten
- Nach 5 falschen Guesses wird der Interpret Name verraten
- Der Nutzer kann immer abbrechen, bekommt aber keine Punkte
