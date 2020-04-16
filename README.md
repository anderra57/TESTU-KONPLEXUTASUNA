# 📝 *TESTU KONPLEXUTASUNA NEURTZEKO WEB APPa* ⛓️

>Proiektu honen helburua PHP eta Python-en garatutako aplikazio baten instalazio eta mantenimendua egitea erraztuko duen script interaktibo bat gauzatzea da, zeinaren azken helburua testu konplexutasuna neurtuko duen web aplikazio bat instalatzea izango den.

Script-ak Ubuntu 18.04 LTS sistema eragilea duen edozein konputagailutan funtzionatu beharko du, zeina ingelesez, gazteleraz edo euskaraz lokalizaturik egongo den. Script honek eskainiko dituen zerbitzuak ondoko hauek izango dira:

- Python-en ingurune birtual bat sortuko du zeinean Python3-az eginiko programak egikarituko diren.

- Apache web zerbitzaria instalatuko du.

- Apache zerbitzarian host birtuala (Virtual Host) sortuko du, zerbitzari batean domeinu anitzak ahalbidetzeko.

- Web aplikazioarentzat PHP modulua instalatuko du.

- Testu baten konplexutasuna neurtuko duen web aplikazioa instalatuko du.
- ---

Proiektu hau garatzeko bash komando interpretatzaileko lengoaiaz idatzitako script-ak erabiliko dira. Proiektu hau aprobatzeko ondoko funtzionalitateak inplementatzea obligaziozkoa izango da, zeintzuak script-ak eskainiko duen menuan bilduko diren modu honetan enumeratuta:

- 0 aukera: Apache eta PHP desinstalatu, baita proiektu honekin erlazionaturiko datu eta bestelako moduluak ere, honela script-a behin eta berriz egikaritzea ahalbidetzea erraztuko da.

- 1 aukera: Apache web zerbitzaria instalatu.

- 2 aukera: Apache web zerbitzaria gaitu eta testatu.

- 3 aukera: Apache web zerbitzarian host birtual (virtual host) bat sortu 8080 portuan eta */var/www/html/erraztest* karpetan.

- 4 aukera: Host birtuala testatu, hau da, apache-k 8080 portutik weborri eskaera bat jasotzen duenean */var/www/html/erraztest* karpetan dagoen *index.html* erakusten duela.

- 5 aukera: PHP modulua instalatu.

- 6 aukera: PHP modulua testatu.

- 7 aukera: Python3-rako ingurune birtual bat sortu */var/www/html/erraztest* karpetan eta *python3envmetrix* izena duena.

- 8 aukera: Testu Konplexutasuna web aplikazioa instalatu.

- 9 aukera: Bistaratu Testu Konplexutasuna web aplikazioa.

- 10 aukera: Apache-k izandako erroreak idazten dituen lorratz fitxategietako (log-etako) azken lerroak bistaratu.

- 11 aukera: Segurtasun gisara, web zerbitzarira egin diren SSH konexio irekitze saiakerak bistaratu.

- 12 aukera: Irten script-etik.
