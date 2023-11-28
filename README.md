# API-Integraatiot


Työtunnit:
9.11. 30 min






Logi:
9.11. Lisäsin Blob-containeriin xml-muotoisen tiedoston ja arkistoin sen. Seuraavassa kohdassa sen tieto pitäisi muuttaa canonical-muotoon. 
Se tehdään mahdollisesti logic apin kautta jonkin muunto ohjelman kautta?


23.11.

Lisäsimme for-looppiin postgresql-tietokanta osion.
Poistimme tietokannasta yhden ylimääräisen rivin komennoilla :

ALTER TABLE persons ALTER COLUMN created_on DROP NOT NULL;
ALTER TABLE persons ALTER COLUMN created_on SET DEFAULT now();



