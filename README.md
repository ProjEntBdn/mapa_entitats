# Índex

-   [Introducció](#introducció)
-   [Contacte](#contacte)
-   [Com utilitzar el mapa](#com-utilitzar-el-mapa)
-   [Evolució del projecte](#evolució-del-projecte)
-   [Fonts d'informació](#fonts-dinformació)
-   [Criteris per afegir entitats](#criteris-per-afegir-entitats)
-   [Fitxa de les entitats](#fitxa-de-les-entitats)
-   [Fiabilitat de la informació](#fiabilitat-de-la-informació)

# Introducció

El [mapa d'entitats a Badalona](https://umap.openstreetmap.fr/ca/map/entitats-actives-de-badalona_1027376#14/41.4554/2.2576) forma part d'un [projecte ciutadà](https://github.com/ProjEntBdn/repositori_central) sense ànim de lucre per millorar la informació disponible de les entitats actives a Badalona amb l'objectiu de promoure la col·laboració.

Va començar com un projecte personal i actualment som dues persones. No estem vinculats a cap entitat, ni organisme oficial, ni forma part d'un treball acadèmic, ni té com a objectiu rebre una subvenció.

# Contacte

Ens podeu contactar a https://x.com/ProjEntBdn o per email a projecteentitatsbadalona@gmail.com.

En cas de voler afegir la vostra entitat, modificar les dades o eliminar-la del mapa, si us plau utilitzeu un compte oficial de l'entitat perquè puguem verificar que realment ens contacteu des d'aquesta entitat.

Si heu vist algun error, voleu col·laborar, fer alguna crítica o simplement donar la vostra opinió, també estem interessats.

# Com utilitzar el mapa

![Imatge general del mapa d'entitats](img/mapa_entitats.jpg)

Es pot utilitzar el cursor per veure el nom de l'entitat sense haver de fer clic i, una vegada s'hagi trobat la que es vol veure, es pot fer clic per veure la seva fitxa.

## Capes

En el mapa, a l'esquerra, hi ha una icona que permet filtrar el llistat d'entitats per nom i per tipus, a més d'ocultar o mostrar capes per facilitar la cerca.

![Mostra la icona del botó per treballar amb la informació de les capes](img/botons_mapa_capes.jpg)

En fer clic sobre aquesta icona, es pot fer clic sobre el filtre per buscar una entitat pel seu nom o filtrar per les que es troben actualment visibles.

![Mostra la icona per filtrar per nom i per entitats visibles actualment](img/filtres.jpg)

També es poden ocultar/mostrar capes (tipus d'entitats) fent clic sobre la icona que sembla un ull (resaltada amb vermell) a l'esquerra del tipus d'entitat, o veure el llistat d'entitats a cada capa tenint en compte el filtre, si n'hi ha algun, fent clic sobre la fletxa (resaltada amb blau).

![Mostra la imatge de diferents capes i la possibilitat d'ocultar o mostrar, a més de llistar les entitats de cada capa](img/ocultar_capes_i_desplegar_llistat.jpg)

## Informació

A sota del botó anterior, podem trobar la icona d'informació.

![Imatge general del mapa d'entitats](img/botons_mapa_info.jpg)

En fer clic, s'obre un panell i, a sota de tot, es pot fer clic sobre els crèdits per consultar-los.

## Idioma

El servei [uMap](https://umap.openstreetmap.fr/ca/) utilitzat per fer el mapa es troba disponible en diversos [idiomes](https://wiki.openstreetmap.org/wiki/UMap). Es pot escollir l'idioma de la interfície canviant la URL del mapa, per exemple, [ca](https://umap.openstreetmap.fr/ca/map/entitats-actives-de-badalona_1027376#14/41.4554/2.2576) pel català, [es](https://umap.openstreetmap.fr/es/map/entitats-actives-de-badalona_1027376#14/41.4554/2.2576) pel castellà o [en](https://umap.openstreetmap.fr/en/map/entitats-actives-de-badalona_1027376#14/41.4554/2.2576) per l'anglès.

El que no es pot escollir és l'idioma de les fitxes de les entitats. Com que la major part de la informació s'ha obtingut de fonts oficials i es troba en català, de moment, la informació només es troba disponible en català.

# Evolució del projecte

Per entendre la metodologia de treball, és important comprendre com va començar i ha anat evolucionant el projecte.

## Selecció del conjunt de dades

Originalment, es buscaven dades obertes reals per Internet per fer un petit projecte personal. En aquell moment es va trobar el portal de dades obertes de l'Ajuntament de Badalona, es van descarregar les dades i es va mirar què es podia fer amb elles. A mesura que s'utilitzaven les dades, van aparèixer dubtes i es van trobar problemes potencials. Així que es va intentar contactar amb els responsables per veure si es podien resoldre, però no es va aconseguir.

Un temps després es va tornar a examinar el conjunt de dades per veure si es podia fer alguna cosa interessant i es van seleccionar les dades del registre municipal d'entitats. Examinant aquest conjunt de dades es va veure que hi havia informació desactualitzada i no es podia saber quines entitats seguien actives. D'aquesta manera es va establir el primer objectiu del projecte: veure quines entitats seguien actives.

## Inicis del projecte

Per simplificar la tasca de trobar entitats actives, es va començar filtrant per aquelles que tenien una pàgina web. D'aquestes, hi havia un nombre significatiu on la web no funcionava, ja no els pertanyia o no s'actualitzava des de feia anys. Així que també es va recórrer a fer cerques per Internet per veure si tenien una altra web o xarxes socials actives. Finalitzat aquest primer filtre, també es va recórrer a altres fonts d'informació com la cerca de notícies sobre entitats als diaris de Badalona.

Més o menys per aquella data es va fer el [Calendari d'advent solidari de Badalona](https://www.instagram.com/calendariadventsolidari/) i, mirant entre les entitats participants, el que feia [Llefia@net](https://llefia.org/) es semblava al que volia fer i se'ls hi va demanar assessorament. Parlant amb ells, em van informar de recursos interessants com: [uMap](https://umap.openstreetmap.fr/ca), el [mapa d'entitats i serveis de La Salut i Llefià](https://www.badalona.cat/ca/serveis-ajuntament/civisme-convivencia-i-mediacio/servei-de-mediacio/barris-i-comunitats-1/mapaentitatsiserveis_salutllefia-vfinal.pdf) i el [registre d'entitats jurídiques de la Generalitat de Catalunya](https://justicia.gencat.cat/ca/serveis/guia_d_entitats/).

## Creació del mapa

Amb aquests nous recursos, i altres que es van anar buscant, es va decidir que es crearia un mapa amb la informació del registre d'entitats municipals i el registre d'entitats jurídiques, afegint les entitats d'aquests registres que s'haguessin pogut verificar que es trobaven actives. A més, s'actualitzaria i verificaria la seva informació.

Abans de continuar, es va buscar assessorament sobre si podria haver problemes al utilitzar aquestes dades per fer el mapa. Després de veure que no hi hauria d'haver problemes, es va continuar recopilant informació fins que es va veure que es feia difícil continuar sense contactar amb les entitats. Així que es va decidir publicar la primera versió del mapa i crear el compte https://x.com/ProjEntBdn per explicar els objectius del projecte i el que s'estava fent, a més de poder accedir a la informació de les entitats i contactar-les a través d'aquesta xarxa social.

## Contacte amb entitats

Arribat el moment de contactar amb les entitats, es va decidir utilitzar diversos mitjans disponibles com: mostres d'entitats, correu electrònic, la xarxa social X, telèfon i visites a les pròpies entitats. Cadascun d'aquests té els seus avantatges i inconvenients.

Normalment, la manera de contacte preferida és l'email, ja que permet investigar per adelantat la informació de les entitats, explicar en detall el que s'està fent, donar el temps necessari per respondre i la informació queda escrita, així que hi ha una menor probabilitat d'introduir errors. Tot i això, en general sembla que hi ha desconfiança, sobretot, a l'inici del projecte i el percentatge de respostes ha sigut baix, més o menys un 30%.

Les mostres d'entitats també han estat tingudes en compte, ja que permeten contactar ràpidament a diverses entitats i hi ha menys desconfiança al veure presencialment a qui demana la informació, però no estan exemptes d'inconvenients. Normalment, no es publica la llista de participants (encara que si es demana, a vegades la proporcionen), així que no es pot buscar la informació per adelantat per confirmar-la. A més, l'ambient sol ser festiu, el que implica que hi ha soroll i costa comunicar-se.

## Adaptació

A mesura que el projecte ha anat avançant, s'han anat fent canvis. Un dels més importants va ser disminuir la informació disponible. Es desconeixia que moltes entitats no sabien que part de la informació que proporcionaven a registres oficials era pública i lliure. Per donar més tranquil·litat a les entitats, es va ometre informació o es va canviar la localització (es dona més detalls sobre això a l'apartat sobre la [fitxa](#fitxa-de-les-entitats)).

En l'àmbit d'aquest projecte, s'entenia per entitat de Badalona, el pertànyer al registre municipal d'entitats o al registre d'entitats jurídiques de la Generalitat. Al anar consultant diferents fonts d'informació i, sobretot, al anar a mostres d'entitats, es va veure que hi havia altres entitats que també jugaven un paper important. A més, es van anar trobant més [registres](https://github.com/ProjEntBdn/registres_reconeixements_entitats) alternatius al d'entitats jurídiques.

Per últim, destacar que aquest projecte no només consisteix en el mapa d'entitats. Al [repositori central](https://github.com/ProjEntBdn/repositori_central) es poden consultar altres continguts relacionats amb les entitats, la informació i la col·laboració. Per exemple, hi ha una [còpia de les dades obertes](https://github.com/ProjEntBdn/dades_obertes_ajuntament) que va publicar l'Ajuntament i que va ser el punt de partida d'aquest projecte. També hi ha una llista de [registres i reconeixements](https://github.com/ProjEntBdn/registres_reconeixements_entitats) que s'han anat consultant i poden ser interessants per les entitats. A més, aprofitant el treball que s'ha anat fent amb els [mapes](https://github.com/ProjEntBdn/mapes), es va crear una llista amb una recopilació de mapes i eines per treballar amb ells.

# Fonts d'informació

Les principals fonts d'informació són les dades del registre d'entitats de l'Ajuntament de Badalona, el registre d'entitats jurídiques de la Generalitat de Catalunya i el registre d'entitats esportives de la Generalitat de Catalunya.

Les altres fonts d'informació s'utilitzen per complementar, actualitzar o corregir aquestes dades. Entre aquestes fonts d'informació es troben: altres [registres](https://github.com/ProjEntBdn/registres_reconeixements_entitats), pàgines web i xarxes socials de les entitats, diaris, contacte directe amb les entitats (telèfon, correu electrònic, visitant l'entitat, mostres d'entitats, etc.), Google Maps, guies d'entitats ([La Salut i Llefià](https://www.badalona.cat/ca/serveis-ajuntament/civisme-convivencia-i-mediacio/servei-de-mediacio/barris-i-comunitats-1), [Des del sud de Badalona](https://sudbadalona.wordpress.com/)), iniciatives com el [Calendari d'advent solidari de Badalona](https://www.instagram.com/calendariadventsolidari/), etc.

## Ajuntament de Badalona

Registre d'entitats publicat el 02/10/2023 al portal de dades obertes (no disponible en aquest moment). Es van descarregar els conjunts d'aquest portal i es troben disponibles en [aquest repositori](https://github.com/ProjEntBdn/dades_obertes_ajuntament).

## Generalitat de Catalunya. Departament de Justícia, Drets i Memòria

[Registre d'entitats jurídiques](https://analisi.transparenciacatalunya.cat/Legislaci-just-cia/Entitats-jur-diques-del-Registre-d-entitats-de-Cat/y6fz-g3ff/about_data) publicat el 09/06/2024.

## Generalitat de Catalunya. Departament de Presidència

[Registre d'Entitats Esportives](https://analisi.transparenciacatalunya.cat/Esport/Registre-d-Entitats-Esportives/qrgc-u7pk/about_data) de la Generalitat de Catalunya publicat el 15/03/2024.

## Generalitat de Catalunya. Departament de Justícia, Drets i Memòria:

[Associacions declarades d'utilitat pública](https://justicia.gencat.cat/ca/ambits/dret_i_entitats_juridiques/associacions/associacions_utilitat_publica/) consultat el 29/05/2024.

# Criteris per afegir entitats

Fins fa relativament poc, el mapa només contenia entitats registrades oficialment a la Generalitat o a l'Ajuntament de Badalona. El motiu era obtenir la informació més fàcilment i només haver de confirmar-la o actualitzar-la.

A partir de juny d'aquest any (2024), també s'inclouran les entitats no registrades oficialment, ja que aquestes també tenen un rol important, participen en les mostres d'entitats i apareixen en les guies d'entitats. Tot i això, encara quedaran algunes entitats que de moment no es tindran en compte.

També s'ha d'aclarir que la intenció no és només incloure les entitats amb seu a Badalona, sinó aquelles entitats actives a Badalona. Si una entitat té la seva seu a Badalona però no té activitat a Badalona, en principi no se la inclourà. D'altra banda, aquelles entitats amb seu fora de Badalona que tinguin activitat a Badalona o atenguin a les persones de Badalona, també se les inclourà.

# Fitxa de les entitats

La fitxa de les entitats no conté la mateixa informació per totes les entitats.

-   **Nom**: normalment s'utilitza el nom oficial de les entitats, encara que hi ha vegades que s'utilitza el nom que mostren la seva web o xarxes socials. Si són part d'una altra entitat, per exemple una secció, s'intenta posar el nom de l'entitat a Badalona encara que la resta de la informació, com els registres oficials, poden ser de l'entitat principal o una delegació més àmplia.
-   **Categoria**: per simplificar la classificació de les entitats, de moment només s'utilitza una única categoria, que gairebé sempre és la mateixa que la capa on es troba al mapa. Normalment, aquesta categoria es decideix en funció de l'activitat de l'entitat, la seva classificació als registres oficials (no sempre coincideix entre els diferents registres) i preguntant quan hi ha dubtes.
-   **Id. Ajuntament**: quan s'ha pogut trobar l'entitat a la còpia del registre d'entitats municipals amb la qual treballem, s'afegeix l'identificador i un enllaç a una web simple que s'ha fet amb informació mínima. En aquesta còpia del registre hi ha entitats que no hi surten, però no es coneix el motiu. A més, es troba desactualitzada i de moment no s'ha pogut accedir a una versió recent.
-   **Generalitat esportiva**: identificadors de l'entitat al registre d'entitats esportives de la Generalitat i un enllaç a la seva pàgina única. A vegades aquesta informació no s'afegeix.
-   **Esports**: camp _modalitat_ del registre d'entitats esportives de la Generalitat.
-   **Generalitat jurídica**: identificadors de l'entitat al registre d'entitats jurídiques de la Generalitat i un enllaç a la seva pàgina única. A vegades aquesta informació no s'afegeix.
-   **Declarada d'utilitat pública**: enllaç al document del Diari Oficial de la Generalitat de Catalunya (DOGC) on se les declara com a tals.
-   **Adreça**: adreça sense el número de pis. A vegades aquesta informació no correspon a l'adreça real de l'entitat perquè no tenen local on fer la seva activitat i s'afegeix l'adreça que ens indiquin o s'afegeix una advertència "Per millorar la protecció de dades, la ubicació d'aquesta entitat no és real." En el cas de les entitats amb seu fora de Badalona, s'intenta posar una adreça de Badalona en el cas que en tinguin alguna.
-   **Telèfon**: opcional.
-   **Correu electrònic**: opcional.
-   **Pàgina web**: de moment només s'afegeix un enllaç per entitat, ja sigui una web o xarxa social.
-   **Finalitats**: concatenació dels camps sobre _finalitats_ del registre d'entitats jurídiques de la Generalitat.
-   **Descripció**: alternativa al camp _finalitats_ per les entitats no registrades o que no disposen d'aquesta informació.

# Fiabilitat de la informació

S'ha tractat de fer un esforç raonable per assegurar la veracitat i actualització de la informació, però no s'ofereix cap garantia de les dades ni de les entitats mencionades.

S'intenta estar atent a canvis en els registres oficials, així com a notícies sobre canvis en les entitats, però no es pot assegurar que la informació estigui actualitzada.

També existeix la possibilitat d'introduir errors en el tractament de les dades.

Si detecteu errors, us podeu posar en [contacte](#contacte) amb nosaltres.
