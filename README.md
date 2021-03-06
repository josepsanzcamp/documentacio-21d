# Documentacio 21D

Aquest repositori conté la documentació relativa a les eleccions al Parlament de Catalunya.

## Llista de col·legis i meses electorals

Al directori csv, trobareu els arxius que contenen totes les escoles amb les taules per províncies. Si només desitgeu la llista de les escoles sense les taules per a cada província, heu de fer servir els arxius acabats en -petit.csv. Aquests arxius només contenen 3 columnes amb el municipi, nom de l'escola o espai i la direcció.

Els arxius PDF originals s'han descarregat de les següents fonts:
- Barcelona: https://bop.diba.cat/scripts/ftpisa.aspx?fnew?bop2017&11/062017000385.pdf
- Girona: https://ssl4.ddgi.cat/bopV1/pdf/2017/210/201721009239.pdf
- Lleida: https://bop.diputaciolleida.cat/faces/consultaF/servlets/donarEdicte/?id=2017_212_7635
- Tarragona: https://www.diputaciodetarragona.cat/ebop/index.php?op=dwn&tipus=i&data=20171103&anyp=2017&num=09182&v=i

Els updates s'han descarregat de les següents fonts:
- Barcelona: https://bop.diba.cat/scripts/ftpisa.aspx?fnew?bop2017&11/062017000444.pdf
- Girona: https://ssl4.ddgi.cat/bopV1/pdf/2017/223/201722309852.pdf


## Candidatures presentades

Al Directori csv, trobareu l'arxiu que conté les candidatures. En aquest cas, hi ha 1 arxiu amb totes les candidatures que es presenten per cada província.

Els arxius PDF originals s'han descarregat de les següents fonts:
- http://www.parlament2017.cat/ca/formacions-politiques/candidatures/candidatures-presentades/index.html

## Altres

- Normativa electoral: http://www.parlament2017.cat/ca/normativa-electoral/index.html
- Manual d’instruccions per als membres de les meses electorals: http://www.parlament2017.cat/web/resources/parlament_content/Documentacio/02_Administracio_electoral/EPC2017-MIMM-CAT-definitu.pdf

## Conversió entre formats

Per convertir els fitxers PDF a CSV, cal tenir instal·lats els programes pdftotext, php i executar la següent comanda:

```
source make.sh
```
