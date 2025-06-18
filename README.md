[![Deploy static content to Pages](https://github.com/rbuj-UOC/M4.252-PAC1/actions/workflows/static.yml/badge.svg)](https://github.com/rbuj-UOC/M4.252-PAC1/actions/workflows/static.yml)

# PAC1

## Descripció de l'activitat

L'activitat consisteix en un exercici pràctic de construcció d'un lloc web format per tres pàgines que estaran vinculades entre elles mitjançant un menú de
navegació.

El lloc web constarà de 3 arxius HTML ( index.html , estadistiques.html i xarxes.html ), un únic arxiu CSS ( estils.css ) que haurà d'estar situat en una
carpeta de nom css i una carpeta ( img ) que contindrà els arxius d'imatge necessaris.

Cada pàgina del lloc haurà de tenir un títol únic, que descrigui de forma adient el seu contingut.

Per crear els documents, han d'utilitzar-se les millors tècniques de marcat explicades en el material docent de l'assignatura.

Així, han d'emprar-se correctament les marques apropiades per a textos, llistes, enllaços, imatges, contenidors genèrics i estructurals (span, div, header, main, nav, etc.), així mateix han d'utilitzar-se els diversos tipus de selectors CSS que correspongui i aplicar classes i ids de la manera més
semàntica possible.

Ha de treballar-se utilitzant el tipus de document HTML5.

Dins de l'arxiu comprimit MaterialsP1.zip s'inclouen els arxius que us caldran per a la realització de les activitats:
- Per copiar i enganxar els textos còmodament us lliurem l'arxiu TextosCopiaEnganxa-CondicionsFormat.rtf.
- Els enllaços externs que han de preparar-se es troben també a l'arxiu TextosCopiaEnganxa-CondicionsFormat.rtf
- En aquest document trobareu, també, algunes instruccions relacionades amb el format dels arxius (pàg. 10).
- Els arxius d'imatge 01-index.png , 02-estadistiques.png i 03-xarxes.png mostren l'aspecte final que ha de tenir cadascun dels arxius; el resultat que obtingueu ha de ser el més semblant possible a aquests models.
- Les imatges necessàries per a la composició de les pàgines es troben dins de la carpeta img.

## Descripció dels arxius

### Primer

Nom de l'arxiu: index.html

Heu de marcar correctament el text de l'article.

Heu de preparar els enllaços externs dins de l'article. Trobareu aquests enllaços en l'arxiu TextosCopiaEnganxa-CondicionsFormat.rtf
L'aspecte de l'article resultant ha de semblar-se al model ( 01-index.png ); reviseu bé aquesta imatge, hi trobareu alguns textos que es mostren entre
cometes i d'altres que es mostren en cursiva, amb un altre tipus de lletra...; són textos amb un valor semàntic especial que exigiran l'ús d'etiquetes HTML
específiques.

### Segon

Nom de l'arxiu: estadistiques.html

Utilitzant la tècnica de llistes imbricades, heu de crear la pàgina en què es llisten algunes dades estadístiques sobre l'ús de les xarxes socials. Els noms de les xarxes socials esmentades en el llistat han de portar a la pàgina xarxes.html , situant el navegant en la posició on aparegui la descripció de la xarxa.

Heu de preparar els enllaços externs dins de l'article. Trobareu aquests enllaços en l'arxiu TextosCopiaEnganxa-CondicionsFormat.rtf.
Observeu bé l'aspecte de l'article i pareu especial atenció als pics de les llistes que heu de modificar mitjançant els selectors i propietats CSS adients; un
d'aquests pics s'ha d'aconseguir mitjançant la utilització de la imatge users.svg que ha de mostrar-se a la llista mitjançant CSS (no amb img ). L'aspecte
de l'article resultant ha de semblar-se al model ( 02-estadistiques.png ).

### Tercer

Nom de l'arxiu: xarxes.html

Utilitzant una llista de descripció, heu de crear la pàgina en la qual es fa una breu descripció de quatre xarxes socials; aquesta descripció inclou una
imatge dels seus creadors i diversos enllaços externs que trobeu indicats a l'arxiu TextosCopiaEnganxa-CondicionsFormat.rtf
L'aspecte de l'article resultant ha de semblar-se al model ( 03-xarxes.png ).

###  Condicions de maquetació dels documents
- Tipus de fonts: en cada part del text ha de respectar-se la tipografia bàsica utilitzada que es mostra en la imatge model (sense serif — Verdana,
Tahoma, sans-serif— o amb serif — Georgia, 'Times New Roman', serif ).
- Mida de la lletra: cal fer els canvis de mida dels textos de cada part del document, tot imitant les proporcions del model.
- S'han de respectar els alineaments de cada part del text.
- Elements semàntics: marqueu convenientment les citacions (de línia, de bloc, d'obres de creació), abreviatures, paraules en idioma diferent del del
document, etc.
- Enllaços: considereu quines regles CSS heu d'aplicar perquè els enllaços tinguin l'aspecte que s'indica en la pàgina 10 de l'arxiu TextosCopiaEnganxa-
CondicionsFormat.rtf.
- Imatges: considereu la forma en què presentareu les imatges per tal que la seva posició sigui la mateixa que en els models.
- Composició: no cal que l'amplada del text en pantalla tingui exactament la mateixa mida que la dels models, si bé s'ha d'aconseguir que sigui llegible i
que els continguts apareguin centrats en la finestra del navegador . Tingueu en compte que la capçalera i el peu de cada pàgina han d'ocupar el 100%
de la finestra del navegador; el contingut principal de cada pàgina ha de tenir una amplada menor . Per realitzar aquesta composició us suggerim que
els elements que han d'estar acotats a una amplada inferior al 100% estiguin continguts dins d'un element amb la classe .container i que la regla CSS
que l'afecti sigui, per exemple, aquesta: .container{width: 95%; max-width: 850px; margin-left: auto; margin-right: auto;}

### Altres activitats a realitzar

Tal com es veu en les imatges model que s'adjunten, totes les pàgines hauran de tenir una capçalera amb el nom del lloc ( Xarxes ).

Cada pàgina ha de tenir un peu de pàgina on s'inclourà el nom de l'estudiant i l'assignatura.

Creació d'un menú de navegació: les tres pàgines del lloc han d'estar enllaçades per un menú de navegació que haurà d'estar situat en la part superior de
cada pàgina, per sota de la capçalera. S'ha de construir amb una llista no ordenada convenientment modificada amb CSS per tal que no es mostrin els
pics per defecte. L'element del menú corresponent a la pàgina en què ens trobem, ha de mostrar-se amb un color diferent de la resta.

### Explicació de les entitats HTML i CSS utilitzades

En el lliurament, a més del lloc web construït, haureu d'incloure un document de text (odt, .docx o .pdf) que amb l'explicació de les decisions de marcatge
que heu pres per construir el lloc web:

1. Sobre les entitats HTML: ha d'explicar-se l'ús de les etiquetes escollides.
2. Sobre el CSS: ha d'explicar-se el CSS utilitzat, incloent-hi quan s'ha utilitzat i per què i per a què s'apliquen els selectors i propietats definides.
3. Si realitzéssiu qualsevol canvi significatiu respecte dels models als quals heu d'aproximar el resultat, heu d'explicar els motius pels quals els heu
realitzat.

### Validació i accessibilitat de les pàgines

Totes les pàgines lliurades, i el full d'estil associat, hauran de validar correctament. Cal assegurar-se que les pàgines acompleixen amb els criteris
d'accessibilitat.