## Aufgabe A:

![alt text](<Screenshot 2025-01-15 180926.png>) <br>

**Warum es besser ist einen PAAS, SAAS zu nutzen:** <br>
Die Nutzung von PaaS / SaaS-Services spart Zeit und Aufwand. Die Anbieter kümmern sich um Installation, Wartung und Skalierung. 

## Aufgabe B:

Zuerst habe ich eine geignette Plattform für meine App ausgewählt, in diesem fall Node.js. <br>
![alt text](<Screenshot 2025-01-15 181618.png>) <br>
Daraufhin habe ein Key-Pair für meine PaaS instanz gewählt. <br>
![alt text](<Screenshot 2025-01-15 181800.png>) <br>
Im Anschluss habe ich das Auto-Scaling konfiguriert, ich habe die min / max instanzen gewählt, und den Scaling-Trigger definiert. <br>
In meinem Fall "Scaled" die Applikation sobald die CPU-Last über 80% ist. <br>
![alt text](<Screenshot 2025-01-15 182624.png>)
![alt text](<Screenshot 2025-01-15 182659.png>)
Dann habe ich meine Loadbalancer konfiguriert, das Montioring "Enabled", den "Patch-Timeframe" definiert und meine E-Mail hinterlegt um wichtige Nachrichte bezgl. VM zu kriegen. <br>
![alt text](<Screenshot 2025-01-15 182712.png>) <br>
![alt text](<Screenshot 2025-01-15 184112.png>) <br>
![alt text](<Screenshot 2025-01-15 184119.png>) <br>
![alt text](<Screenshot 2025-01-15 184124.png>) <br>
![alt text](<Screenshot 2025-01-15 190157.png>) <br>


## Aufgabe C:

KN07-Sec. Group
![alt text](image.png)
KN07-Auto-Scaling
![alt text](image-1.png)
![alt text](image-2.png)
KN07-Load-Balancer:
![alt text](image-4.png)
KN07-Target group: 
![alt text](image-3.png)

**Was ist CloudFormation:**
CloudFormation ist ein AWS-Dienst, mit dem Infrastruktur als Code definiert und automatisch bereitgestellt wird. Im Unterschied dazu wird Cloud-Init direkt auf virtuellen Maschinen ausgeführt, um sie während des Startvorgangs zu konfigurieren.
![alt text](image-5.png)


