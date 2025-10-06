## info
just playing around out building a webapp ^^

## file structure
backend:
	database/
		models.py 	| Klassen für Datenbanktabellen
		db.py		| access functions for db
	routers/  		| REST-API-Endpunkte
	auth/	  		| Login, Tokenüberprüfung, Rollen

	main.py	  		| main entrypoint.
	
frontend:
	routes/	  | the different pages
	lib/ 	  | reusable components

## dev
for developing I recommend doing npm install inside /frontend and downloading every module via pip in the requirements.txt
