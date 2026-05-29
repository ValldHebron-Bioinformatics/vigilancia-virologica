# Vigilància virològica del virus de la grip A

Per a la vigilància epidemiològica de la grip A es proposa un conjunt d'**eines visuals i gràfics interactius** dissenyats per oferir **perspectives complementàries** que faciliten la **interpretació de la dinàmica evolutiva del virus**.

A continuació es presenten els resultats obtinguts a partir de les seqüències de grip humana publicades per l'Hospital Universitari Vall d'Hebron a la plataforma GISAID. Aquestes dades comprenen les temporades epidemiològiques des de la setmana 40 de l'any 2020 fins a la setmana 20 del 2026.

* **Informe de distribució de subtipus i clades per temporada epidemiològica** **[(Accés al gràfic)](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/CladeGraphicReport.html)**:

    Aquest apartat mostra, mitjançant diagrames de sectors interactius, quina ha estat la **proporció dels diferents subtipus** del virus de la grip A humana en circulació. A més, aprofundeix en la **distribució específica per clades** dins de cadascun dels subtipus detectats, que actualment corresponen a l'A(H1N1pdm09) i l'A(H3N2).

    Els gràfics interactius inclouen un **menú desplegable** dissenyat per **filtrar** i visualitzar la informació d'una **temporada epidemiològica** concreta. Així mateix, en passar el cursor per sobre de qualsevol porció del gràfic, es desplega una **finestra emergent** amb les xifres detallades d'aquell segment. Aquesta interactivitat resulta especialment útil per explorar les agrupacions genètiques designades amb el sufix `-like`. 

    De la mateixa manera, aquesta mateixa finestra emergent permet consultar quines variants exactes componen la categoria **`Others`**, una etiqueta que agrupa tots els clades minoritaris amb una presència inferior al **1%** en el conjunt de les mostres de cada temporada.



* **Dinàmica temporal de la circulació de subtipus i clades** **[(Accés al gràfic)](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/CladeEvolutionReport.html)**:

   Aquest gràfic interactiu permet analitzar la distribució de subtipus de la grip A i dels seus clades associats a **escala setmanal**. 
   
   La visualització presenta per defecte les dades corresponents a la **temporada epidemiològica més recent** `Season 2025-2026`. Mitjançant el **menú desplegable superior**, és possible seleccionar una temporada específica per a l'anàlisi. Addicionalment, l'opció **`All Time`** permet visualitzar l'històric complet de dades, fet que comporta un reajustament automàtic de l'eix cronològic.

   L'estructura de barres acumulades representa de forma visual la **proporció i dominància** de cada variant al llarg del temps. En passar el cursor per sobre de qualsevol dels segments de la barra, es desplega una **finestra emergent** que detalla el nom del **subtipus o clade**, la **setmana epidemiològica** exacta, el nombre absolut d'**ocurrències registrades** en aquell interval i el **percentatge** que representen respecte al total de mostres d'aquella setmana. 
   
   Es tracta d'un recurs dissenyat per detectar de manera **ràpida i intuïtiva** les **tendències** i els **canvis en el patró de circulació** del virus.


* **Informe de circulació de subtipus i clades a nivell geogràfic** **[(Accés al gràfic)](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/GeographicReport.html)**:

    Aquest **mapa interactiu** permet representar la **dispersió espacial** i l'**evolució temporal** dels subtipus del virus de la grip A i dels seus clades associats a tot el territori de **Catalunya**. Oferint una **traçabilitat geogràfica** intuïtiva.

    Per optimitzar l'exploració de les dades, la interfície disposa de **tres menús desplegables** independents que en modifiquen el comportament visual de manera dinàmica. El primer filtre **`(SEASONS)`** permet **seleccionar una temporada epidemiològica** concreta, iniciant-se per defecte en la vista de la temporada epidemiològica més recent `Season 2025-2026`. El segon desplegable **`(GEOGRAPHIC LEVEL)`** serveix per **alternar la resolució territorial** de l'anàlisi, oferint l'opció d'agrupar les mostres a escala regional per **província `(Province)`** o bé descendint a un detall més local per **municipi `(City/Town)`**. Finalment, el tercer selector **`(CLASSIFICATION)`** permet canviar la **visualització taxonòmica** entre la distribució general dels **subtipus** o el detall dels **clades** específics que els componen. 

    El mapa manté la **interactivitat** de la resta d'informes, oferint **finestres emergents** amb el **desglossament de clades** en passar el cursor sobre els punts del territori.
    
* **Informe de les mutacions trobades en el conjunt de dades** **[(Accés al gràfic)](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/MutationsReport.html)**:


    Aquest conjunt de **gràfics interactius** permet explorar les mutacions en els segments genòmics de la Grip A, ordenats de manera biològica. Mitjançant un **menú desplegable**, l'usuari pot filtrar la informació per **temporades epidemiològiques**, mantenint una separació estricta entre els subtipus **A(H1N1)pdm09 i A(H3N2)** per evitar confusions visuals. Els **marcadors moleculars caracteritzats fenotípicament, i que suposen un canvi de susceptibilitat als antivirals** (actualment a NA i PA) es ressalten en **taronja**, mentre que a la proteïna **HA1** s'identifiquen els **epítops antigènics principals**, els quals també es veuen representats mitjançant **barres verticals de colors** al fons del gràfic.
    
    L'**eix horitzontal (X)** indica la **posició lineal dels aminoàcids**, facilitant la localització exacta dels canvis dins de la proteïna i els seus epítops. L'**eix vertical (Y)** mostra la **freqüència de la mutació (%)**, calculada de manera dinàmica segons el **nombre total de mostres** d'aquell subtipus en la temporada seleccionada.
    Per evitar la saturació visual de dades aïllades, s'inclou un **botó lliscant interactiu** que regula el **llindar mínim de freqüència**. Aquest filtre s'inicia automàticament en un **tall del 25%**, de manera que d'entrada només es visualitzen les mutacions presents en una quarta part o més de les seqüències, tot i que l'usuari pot modificar aquest límit lliurement.
    
    El gràfic manté una alta interactivitat que permet fer **zoom de precisió** en seleccionar àrees concretes de la pantalla. A més, en passar el cursor sobre qualsevol punt, es desplega una **finestra emergent amb informació específica** que detalla la posició en la proteïna, els efectes biològics estimats i les referències associades.

* **Informe de l'evolució de la freqüència dels marcadors específics** (Accés als gràfics: **[HA1_H1N1](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_HA1_A(H1N1)pdm09.html)**,  **[HA1_H3N2](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_HA1_A(H3N2).html)**, **[NA_H1N1](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_NA_A(H1N1)pdm09.html)**, **[NA_H3N2](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_NA_A(H3N2).html)**, **[PA_H3N2](https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_PA_A(H3N2).html)**):


    Aquest mòdul interactiu permet avaluar de manera **setmanal** com apareixen i progressen determinades mutacions al llarg del temps. Visualment l'eina consta de **dos gràfics superposats**: el **gràfic superior** mostra la **freqüència setmanal**, que representa el percentatge de mostres d'aquella setmana concreta on s'ha detectat la variant, mentre que el **gràfic inferior** reflecteix la **freqüència acumulada**, indicant el nombre total de vegades que s'ha anat observant el marcador fins a arribar a una data determinada.
    
    A través del **menú desplegable**, es pot filtrar la informació per **temporada epidemiològica**, mostrant per defecte la vista de la temporada més recent `Season 2025-2026`, també presenta l'opció de veure la vista global de totes les temporades `All Time`. El gran avantatge d'aquest filtre és que, en triar una temporada concreta, l'aplicació no només realitza un zoom automàtic en el període de temps seleccionat, sinó que **recalcula i actualitza la freqüència relativa acumulada** d'aquells mesos, la qual cosa permet analitzar immediatament quines variants han tingut un paper més dominant a cada campanya.
    
    Per evitar la saturació i el solapament de línies a la pantalla, el panell incorpora una **llegenda interactiva** a la dreta amb els marcadors ordenats numèricament. Aquesta llegenda s'adapta de forma dinàmica i **només mostra les mutacions actives** de la temporada que s'estigui avaluant. A més, l'usuari pot fer **doble clic** sobre un marcador concret per aïllar la seva corba i analitzar-la en solitari, o fer **clics simples addicionals** sobre altres elements per anar sumant variants a la comparativa visual de manera personalitzada.
    
    La combinació d'aquestes funcions garanteix un **seguiment epidemiològic d'alta precisió**, fent que l'estudi de la trajectòria de les mutacions clau sigui un procés net, intuïtiu i molt visual.


## Properes passes
La metodologia desenvolupada per a la vigilància genòmica de la grip A ha estat dissenyada amb una **arquitectura modular i escalable** que permet la seva adaptació a **altres virus respiratoris de rellevància epidemiològica**. 

La línia de treball actual es dirigeix a l'escalabilitat d'aquesta plataforma per incloure el **Virus de la Grip B**, **Virus Respiratori Sincitial (VRS)** i el **SARS-CoV-2**. L'objectiu d'aquesta ampliació és aplicar els mateixos estàndards d'anàlisi, des de la caracterització de llinatges fins a la localització geogràfica, per tal de generar un **marc d'anàlisi unificat**.
