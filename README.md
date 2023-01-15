Andrés Pantoja - DIW 2023

# R01. 
**Hi ha un report de Lighthouse (en format HTML) per cada pàgina (al començament de l'auditoria d'accessibilitat)**

Puedes encontrar el reporte de Lighthouse en el archivo llamado **reportelighthouse1.html**, lo podras encontrar en el repositorio.

Una vez escaneada la pagina, lighthouse nos ha encontrado los siguientes problemas:
- Los elementos del form, no tienen un label asociado.
- Los <iframe> no tienen un titulo
- Los links no tienen un nombre descriptible.
- Las listas no continen solo <li> (Facilita tabular)
- Heading elements no estan en orden. Esto significa que no he utilizado bien los: h1,h2,h3...

# R02. 
**Hi ha un report de Lighthouse (en format HTML) per cada pàgina (al final de l'auditoria d'accessibilitat)**
Puedes encontrar el reporte de Lightouse en el archivo llamado **reportelighthouse2.html**, lo podras encontrar en el repositorio

Una vez hemos arreglado los errores detectados automaticamente por lighthouse, vamos a poceder a comprobar manualmente.

# R03. 
**En el README s'indica quins problemes d'accessibilitat s'han comprovat manualment**

He comprobado los siguientes errores manualmente:
- La pagina tiene un orden de tabulacion logico &#x2611;
- Los controles iteractivos son "focuseable" por teclado &#x2611;
- Los elementos interactivos indican su proposito y estado &#x2611;
- El usuario hace focus directamente el nuevo contenido añadido a la pagina. (No aplica)
- El focus no se queda atrapado en alguna region de la pagina &#x2611;
- Los controles personalizados tiene labels asociados (Tales como arial-label)  &#x2611;
- Los controles personalizados tienen roles ARIA (Screen reader)
- El orden visual de la pagina sigue el orden DOM &#x2611;
- El contenido de fuera de la pagina esta oculto &#x2611;
- elementos Landmark son utilizados (nav), (main), (footer) &#x2611;
# R04.
**En el README s'indica quins dels problemes detectats manualment s'han solucionat**
he solucionado los elementos landmark, ya que no poseia ningun <main>
# R05. 
**En el README s'indica quins dels problemes detectats manualment no s'han solucionat**
He podido solucionar el unico problema manual que he tenido, comentado en el punto anterior
# R06.
**En el README es justifica perquè no s'ha solucionat qualque problema d'accessibilitat detectat (fals positiu o no aplica)**
El unico que no aplica es que el usuario hace focus directamente el nuevo contenido añadido a la pagina.  Ya que en mi pagina web estatico, no se añade contenido nuevo
# R07.
**La pàgina té una puntuació de 100 en la categoria de Accessibility de Lighthouse**
En el **reportelighthouse2.html**, puedes comprobar que ha dado la puntuacion de 100.

# R08. 
**La pàgina és usable només amb teclat**
La web es perfectamente usable con teclado, (Flechas de direccion, tabulador)
# R09. 
**La pàgina és semàntica (usable amb tecnologies asistives com lectors de pantalla)**
  Si. añadido arial label a partes importantes del codigo
# R10. 
**La pàgina és usable en qualsevol dispositiu i resolució (responsive)**
La pagina es usable en navegador de escritorio y en navegador de movil. Tambien es responsive.
