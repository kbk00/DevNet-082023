# DevNet-082023

Part 1: GitHub
Logger ind i min GitHub og laver et public repo til opgaven.
Opretter mappestruktur lokalt på min VM
Kører de nødvendige git kommandoer for at konfigurere mit brugernavn og email til github.
Kører de nødvendige git kommandoer for at linke lokal mappe til repo, initalizer git i min GitHub_folder, og fortæller git at den skal medtage alt i GitHub_folder
Jeg oprettede med vilje ikke README da jeg oprettede mit repository, så derfor køres kommando til dette. Herefter "add *" til root folder og derefter commit ændringer og push til master branch.

Part 2: Ansible
Ansibe installeres med de nødvendige kommandoer.
Sørger for at jeg har ansible.cfg, hosts og servers.
Skriver en yaml fil som er min playbook, tester det og får output eksporteret til fil.

Part 3: Docker
Først installeres Flask som bruges til apache webserver. Docker er preinstalleret på VM.
Derefter laves python script til at importere methods fra Flask.
Tempdir oprettes og heri oprettes mapperne static og templates som webserveren skal bruge.
Bash script skrives til kopiering af mapper til mappestruktur, opprettelse af dockerfile, til at bygge docker container og til at starte containeren.
Index.html ændres sådan at jeg kan vise webserveren virker.

Part 4: Rest API and RESTCONF
Starter med at finde dokumentationen til RESTCONF api.
Først konfigureres min router til at kunne bruge YANG via RESTCONF protokollen, og åbner for HTTPS, og sikrer mig at YANG og nginx er running.
Derefter fjernes SSL-requirement i postman. 
Jeg tilpasser en GET-request i Postman for at kunne få de nødvendige oplysninger fra min router til mit script.
Python script skrives til PUT-request og for hyggens skyld laver jeg en GET-request også.

Part 5: Netmiko
Jeg finder den nødvendige dokumantation til Netmiko.
Skriver efterfølgende script som passer til opgaven.
Scriptet testes.

