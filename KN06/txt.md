## Aufgabe A:

Ein Reverse Proxy ist ein System, welches Anfragen von clients annimmt und sie an "interne" instanzen weiterleitet, ohne dass die clients etwas merken. Ein Reverse Proxy verbessert die Sicherheit, skalierbarkeit von Systemen. <br>

 
![alt text](<Screenshot 2025-01-14 160405.png>) <br>

![alt text](<Screenshot 2025-01-14 161630.png>) <br>

![alt text](<Screenshot 2025-01-14 161834.png>) <br>


**Schauen Sie sich das Cloud-Init genau an. Welche(r) Teil(e) macht/machen hier überhaupt keinen Sinn in einer produktiven Umgebung:**
Username und passwort sind hardcoded, dies ist NIE eine Gute Idee.

## Aufgabe B:

**Vorher:** <br>
![alt text](<Screenshot 2025-01-14 162722.png>)


Zuerst Erstelle ich ein Elastic-Block Storage Volume in der Grösse 20gb. Anschliesend "attache" ich das Volume an meiner EC-2 instanz.
![alt text](image.png)

Zuerst Stoppe ich die Instanz. Danach ändere ich den Instanz-Typ unter "Actions", "Instance-Settings", "Change-InstanceType" den Instanz-Typ auf T2-Medium.
![alt text](<Screenshot 2025-01-15 090049.png>)

## Aufgabe C: 

**Erklärung DNS:**
Der AWS Load Balancer bekommt einen eigenen DNS-Namen, über den er erreichbar ist, weil sich seine IP's ständig ändern. Damit man trotzdem einfach darauf zugreifen kann, verbindet man den DNS-Namen mit einer eigenen Domain.

Swagger via DNS:
![alt text](image-1.png)

## Aufgabe D: 

Nich fertig bekommen.