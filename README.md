# vigilancia-virologica
Repositori de seguiment epidemiològic de virus respiratoris: circulació, clades, mutacions i variants. Informes periòdics basats en dades de vigilància genòmica i epidemiològica.

## Grip A

Per a la vigilància epidemiològica de la grip A es proposen una sèrie de gràfics que aporten, cadascun d'ells, una perspectiva diferent i complementària de les dades. 
A continuació es presenten els resultats obtinguts a partir de les seqüències de grip humana publicades per l'Hospital Universitari Vall d'Hebron a la plataforma GISAID. Aquestes dades comprenen les temporades epidemiològiques des de la setmana 40 de l'any 2020 fins al 20 de maig de 2026.

* **Informe de distribució de subtipus i clades per temporada epidemiològica** **[(Accés al gràfic)](https://htmlpreview.github.io/?https://github.com/ValldHebron-Bioinformatics/vigilancia-virologica/blob/main/GRIP/CladeGraphicReport.html)**:

    Aquest apartat mostra, mitjançant diagrames de sectors interactius, quina ha estat la **proporció dels diferents subtipus** del virus de la grip A humana en circulació. A més, aprofundeix en la **distribució específica per clades** dins de cadascun dels subtipus detectats, que actualment corresponen a l'H1N1pdm09 i l'H3N2.

    Els gràfics interactius inclouen un **menú desplegable** dissenyat per **filtrar** i visualitzar la informació d'una **temporada epidemiològica** concreta. Així mateix, en passar el cursor per sobre de qualsevol porció del gràfic, es desplega una **finestra emergent** amb les xifres detallades d'aquell segment. Aquesta interactivitat resulta especialment útil per explorar les agrupacions genètiques, ja que ofereix un **desglossament intern** (`Clade breakdown`) per a aquells llinatges designats amb el sufix `-like`. 

    De la mateixa manera, aquesta mateixa finestra emergent permet consultar quines variants exactes componen la categoria **`Others`**, una etiqueta que agrupa tots els clades minoritaris amb una presència inferior al **2%** en el conjunt de les mostres de cada temporada.



* **Dinàmica temporal de la circulació de subtipus i clades** **[(Accés al gràfic)](https://htmlpreview.github.io/?https://github.com/ValldHebron-Bioinformatics/vigilancia-virologica/blob/main/GRIP/CladeEvolutionReport.html)**:

   Aquest gràfic interactiu permet analitzar la distribució de subtipus de la grip A i dels seus clades associats a **escala setmanal**. 
   
   La visualització s'inicia de manera general mostrant l'històric complet de dades sota l'etiqueta **`All Time`**. L'ús del **menú desplegable** superior facilita la **selecció d'una temporada epidemiològica** específica, fet que **reajusta** automàticament el **focus de l'eix cronològic** cap a les barres acumulades d'aquell període concret.

   L'estructura de barres acumulades representa de forma visual la **proporció i dominància** de cada variant al llarg del temps. En passar el cursor per sobre de qualsevol dels segments de la barra, es desplega una **finestra emergent** que detalla el nom del **subtipus o clade**, la **setmana epidemiològica** exacta, el nombre absolut d'**ocurrències registrades** en aquell interval i el **percentatge** que representen respecte al total de mostres d'aquella setmana. 
   
   Es tracta d'un recurs dissenyat per detectar de manera **ràpida i intuïtiva** les **tendències** i els **canvis en el patró de circulació** del virus.


* **Informe de circulació de subtipus i clades a nivell geogràfic** **[(Accés al gràfic)](https://htmlpreview.github.io/?https://github.com/ValldHebron-Bioinformatics/vigilancia-virologica/blob/main/GRIP/GeographicReport.html)**:

    Aquest **mapa interactiu** permet representar la **dispersió espacial** i l'**evolució temporal** dels subtipus del virus de la grip A i dels seus clades associats a tot el territori de **Catalunya**. Oferint una **traçabilitat geogràfica** intuïtiva.

    Per optimitzar l'exploració de les dades, la interfície disposa de **tres menús desplegables** independents que en modifiquen el comportament visual de manera dinàmica. El primer filtre **`(SEASONS)`** permet **seleccionar una temporada epidemiològica** concreta, iniciant-se per defecte en la vista històrica completa `All Seasons`. El segon desplegable **`(GEOGRAPHIC LEVEL)`** serveix per **alternar la resolució territorial** de l'anàlisi, oferint l'opció d'agrupar les mostres a escala regional per **província `(Province)`** o bé descendint a un detall més local per **municipi `(City/Town)`**. Finalment, el tercer selector **`(CLASSIFICATION)`** permet canviar la **visualització taxonòmica** entre la distribució general dels **subtipus** o el detall dels **clades** específics que els componen. 

    El mapa manté la **interactivitat** de la resta d'informes, oferint **finestres emergents** amb el **desglossament de clades** en passar el cursor sobre els punts del territori.
    
* **Informe de les mutacions trobades en el conjunt de dades**: **[(Accés al gràfic)](https://htmlpreview.github.io/?https://github.com/ValldHebron-Bioinformatics/vigilancia-virologica/blob/main/GRIP/MutationsReport.html)**:







    




## Next steps
- VRS
- ...
