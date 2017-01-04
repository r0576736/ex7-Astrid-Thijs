# ex7-Astrid-Thijs
Samengewerkt met Jelle Van Loock, Kevin Aerts en Genzo Vandervelden.


DroneTable.css:
  Hierin vind je de kleurcode terug voor de achtergrond van de webpagina. 
  Ik heb voor de kleur heb ik inspiratie opgedaan bij de huisstijl van Thomas More.

drones.html:
  Hierin vind je de code terug om de tabel te maken en in te vullen.
  Via de link kan je naar de stylesheet ./DroneTable.css verwijzen. 
  Script:
    Je geeft url mee waar je data wil gaan uithalen, GET Methode, Datatype JSON en ook de authorization code.
    Allereerst gaan we settings meegeven, basis url, function(Drone1).
      Via deze id gaan we verder de drone details ophalen, function(Drone2).
        Via de file id gaan we de nog diepere details ophalen, function(Drone3).
    zo krijgen we de uiteindelijke data:
        drone1.name       
        drone1.mac_address
        drone3.id
        drone3.date_first_record
        drone3.date_last_record
   
   Hierna de tabel definiëren.




Astrid Thijs.
