Hola, gràcies a tots els que ens heu escrit errors i dubtes sobre la nostra API, ens ha ajudat a millorar i aprendre moltes coses. Us invitam a veure el projecte que hem creat per el nostre mòdul al següent enllaç:

http://www.dawidpelc.com/

Recomanable obrir des d'un ordinador ja que no és massa responsive.

Ajuda --> http://www.dawidpelc.com/api/laravel_projecte_baleart-dawidmateujulia/public/api

Per fer feina és necessari fer un login:
http://www.dawidpelc.com/api/laravel_projecte_baleart-dawidmateujulia/public/api/login --> Mètode POST

Usuari registrat:
email=random@paucasesnovescifp.cat
password=secret

Per fer el login heu d'enviar una solicitud a la URL abans mencionada amb el mètode POST, indicant al body, en format x-www-form-urlencoded els dos paràmetres de email i password amb els valors corresponents.

Una vegada registrats podreu emprar el token obtingut per fer altres consultes, com per exemple, crear un usuari propi per no emprar tots el mateix:
http://www.dawidpelc.com/api/laravel_projecte_baleart-dawidmateujulia/public/api/usuaris -> POST (podeu consultar els paràmetres en la pàgina d'ajuda)
Per fer qualsevol petició sempre haureu de posar el token al camp "Authorzation" del tipus "Bearer Token"
