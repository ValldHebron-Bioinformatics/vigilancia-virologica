<div style="text-align: justify;">

<h1>Vigilància virològica del virus de la grip A</h1>

<p>Per a la vigilància epidemiològica de la grip A es proposa un conjunt d'<b>eines visuals i gràfics interactius</b> dissenyats per oferir <b>perspectives complementàries</b> que faciliten la <b>interpretació de la dinàmica evolutiva del virus</b>.</p>

<p>A continuació es presenten els resultats obtinguts a partir de les seqüències de grip humana publicades per l'Hospital Universitari Vall d'Hebron a la plataforma GISAID. Aquestes dades comprenen les temporades epidemiològiques des de la setmana 40 de l'any 2020 fins al 20 de maig de 2026.</p>

<ul>
    <li>
        <p><b>Informe de distribució de subtipus i clades per temporada epidemiològica</b> <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/CladeGraphicReport.html">(Accés al gràfic)</a></b>:</p>
        <p>Aquest apartat mostra, mitjançant diagrames de sectors interactius, quina ha estat la <b>proporció dels diferents subtipus</b> del virus de la grip A humana en circulació. A més, aprofundeix en la <b>distribució específica per clades</b> dins de cadascun dels subtipus detectats, que actualment corresponen a l'H1N1pdm09 i l'H3N2.</p>
        <p>Els gràfics interactius inclouen un <b>menú desplegable</b> dissenyat per <b>filtrar</b> i visualitzar la informació d'una <b>temporada epidemiològica</b> concreta. Així mateix, en passar el cursor per sobre de qualsevol porció del gràfic, es desplega una <b>finestra emergent</b> amb les xifres detallades d'aquell segment. Aquesta interactivitat resulta especialment útil per explorar les agrupacions genètiques, ja que ofereix un <b>desglossament intern</b> (<code>Clade breakdown</code>) per a aquells llinatges designats amb el sufix <code>-like</code>.</p>
        <p>De la mateixa manera, aquesta mateixa finestra emergent permet consultar quines variants exactes componen la categoria <b><code>Others</code></b>, una etiqueta que agrupa tots els clades minoritaris amb una presència inferior al <b>1%</b> en el conjunt de les mostres de cada temporada.</p>
    </li>
    <br>
    <li>
        <p><b>Dinàmica temporal de la circulació de subtipus i clades</b> <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/CladeEvolutionReport.html">(Accés al gràfic)</a></b>:</p>
        <p>Aquest gràfic interactiu permet analitzar la distribució de subtipus de la grip A i dels seus clades associats a <b>escala setmanal</b>.</p>
        <p>La visualització s'inicia de manera general mostrant l'històric complet de dades sota l'etiqueta <b><code>All Time</code></b>. L'ús del <b>menú desplegable</b> superior facilita la <b>selecció d'una temporada epidemiològica</b> específica, fet que <b>reajusta</b> automàticament el <b>focus de l'eix cronològic</b> cap a les barres acumulades d'aquell període concret.</p>
        <p>L'estructura de barres acumulades representa de forma visual la <b>proporció i dominància</b> de cada variant al llarg del temps. En passar el cursor per sobre de qualsevol dels segments de la barra, es desplega una <b>finestra emergent</b> que detalla el nom del <b>subtipus o clade</b>, la <b>setmana epidemiològica</b> exacta, el nombre absolut d'<b>ocurrències registrades</b> en aquell interval i el <b>percentatge</b> que representen respecte al total de mostres d'aquella setmana.</p>
        <p>Es tracta d'un recurs dissenyat per detectar de manera <b>ràpida i intuïtiva</b> les <b>tendències</b> i els <b>canvis en el patró de circulació</b> del virus.</p>
    </li>
    <br>
    <li>
        <p><b>Informe de circulació de subtipus i clades a nivell geogràfic</b> <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/GeographicReport.html">(Accés al gràfic)</a></b>:</p>
        <p>Aquest <b>mapa interactiu</b> permet representar la <b>dispersió espacial</b> i l'<b>evolució temporal</b> dels subtipus del virus de la grip A i dels seus clades associats a tot el territori de <b>Catalunya</b>. Oferint una <b>traçabilitat geogràfica</b> intuïtiva.</p>
        <p>Per optimitzar l'exploració de les dades, la interfície disposa de <b>tres menús desplegables</b> independents que en modifiquen el comportament visual de manera dinàmica. El primer filtre <b><code>(SEASONS)</code></b> permet <b>seleccionar una temporada epidemiològica</b> concreta, iniciant-se per defecte en la vista de la temporada epidemiològica més recent <code>Season 2025-2026</code>. El segon desplegable <b><code>(GEOGRAPHIC LEVEL)</code></b> serveix per <b>alternar la resolució territorial</b> de l'anàlisi, oferint l'opció d'agrupar les mostres a escala regional per <b>província (<code>Province</code>)</b> o bé descendint a un detall més local per <b>municipi (<code>City/Town</code>)</b>. Finalment, el tercer selector <b><code>(CLASSIFICATION)</code></b> permet canviar la <b>visualització taxonòmica</b> entre la distribució general dels <b>subtipus</b> o el detall dels <b>clades</b> específics que els componen.</p>
        <p>El mapa manté la <b>interactivitat</b> de la resta d'informes, oferint <b>finestres emergents</b> amb el <b>desglossament de clades</b> en passar el cursor sobre els punts del territori.</p>
    </li>
    <br>
    <li>
        <p><b>Informe de les mutacions trobades en el conjunt de dades</b>: <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/MutationsReport.html">(Accés al gràfic)</a></b>:</p>
        <p>Aquest conjunt de <b>gràfics interactius</b> permet explorar les mutacions en els segments genòmics de la Grip A, ordenats de manera biològica. Mitjançant un <b>menú desplegable</b>, l'usuari pot filtrar la informació per <b>temporades epidemiològiques</b>, mantenint una separació estricta entre els subtipus <b>H1N1 i H3N2</b> per evitar confusions visuals. Els <b>marcadors moleculars amb funció coneguda</b> (actualment a NA i PA) es ressalten en <b>taronja</b>, mentre que a la proteïna <b>HA1</b> s'identifiquen els <b>epítops antigènics principals</b>, els quals també es veuen representats mitjançant <b>barres verticals de colors</b> al fons del gràfic.</p>
        <p>L'<b>eix horitzontal (X)</b> indica la <b>posició lineal dels aminoàcids</b>, facilitant la localització exacta dels canvis dins de la proteïna i els seus epítops. L'<b>eix vertical (Y)</b> mostra la <b>freqüència de la mutació (%)</b>, calculada de manera dinàmica segons el <b>nombre total de mostres</b> d'aquell subtipus en la temporada seleccionada. Per evitar la saturació visual de dades aïllades, s'inclou un <b>botó lliscant interactiu</b> que regula el <b>llindar mínim de freqüència</b>. Aquest filtre s'inicia automàticament en un <b>tall del 25%</b>, de manera que d'entrada només es visualitzen les mutacions presents en una quarta part o més de les seqüències, tot i que l'usuari pot modificar aquest límit lliurement.</p>
        <p>El gràfic manté una alta interactivitat que permet fer <b>zoom de precisió</b> en seleccionar àrees concretes de la pantalla. A més, en passar el cursor sobre qualsevol punt, es desplega una <b>finestra emergent amb informació específica</b> que detalla la posició en la proteïna, els efectes biològics estimats i les referències associades.</p>
    </li>
    <br>
    <li>
        <p><b>Informe de l'evolució de la freqüència dels marcadors específics</b> (Accés als gràfics: <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_HA1_H1N1.html">HA1_H1N1</a></b>, <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_HA1_H3N2.html">HA1_H3N2</a></b>, <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_NA_H1N1.html">NA_H1N1</a></b>, <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_NA_H3N2.html">NA_H3N2</a></b>, <b><a href="https://valldhebron-bioinformatics.github.io/vigilancia-virologica/GRIP/evolution_PA_H3N2.html">PA_H3N2</a></b>):</p>
        <p>Aquest mòdul interactiu permet avaluar de manera <b>setmanal</b> com apareixen i progressen determinades mutacions al llarg del temps. Visualment l'eina consta de <b>dos gràfics superposats</b>: el <b>gràfic superior</b> mostra la <b>freqüència setmanal</b>, que representa el percentatge de mostres d'aquella setmana concreta on s'ha detectat la variant, mentre que el <b>gràfic inferior</b> reflecteix la <b>freqüència acumulada</b>, indicant el nombre total de vegades que s'ha anat observant el marcador fins a arribar a una data determinada.</p>
        <p>A través del <b>menú desplegable</b>, es pot filtrar la informació per <b>temporada epidemiològica</b>, mostrant per defecte la vista històrica global <b><code>All time</code></b>. El gran avantatge d'aquest filtre és que, en triar una temporada concreta, l'aplicació no només realitza un zoom automàtic en el període de temps seleccionat, sinó que <b>recalcula i actualitza la freqüència relativa acumulada</b> d'aquells mesos, la qual cosa permet analitzar immediatament quines variants han tingut un paper més dominant a cada campanya.</p>
        <p>Per evitar la saturació i el solapament de línies a la pantalla, el panell incorpora una <b>llegenda interactiva</b> a la dreta amb els marcadors ordenats numèricament. Aquesta llegenda s'adapta de forma dinàmica i <b>només mostra les mutacions actives</b> de la temporada que s'estigui avaluant. A més, l'usuari pot fer <b>doble clic</b> sobre un marcador concret per aïllar la seva corba i analitzar-la en solitari, o fer <b>clics simples addicionals</b> sobre altres elements per anar sumant variants a la comparativa visual de manera personalitzada.</p>
        <p>La combinació d'aquestes funcions garanteix un <b>seguiment epidemiològic d'alta precisió</b>, fent que l'estudi de la trajectòria de les mutacions clau sigui un procés net, intuïtiu i molt visual.</p>
    </li>
</ul>

<h2>Properes passes</h2>

<p>La metodologia desenvolupada per a la vigilància genòmica de la grip A ha estat dissenyada amb una <b>arquitectura modular i escalable</b> que permet la seva adaptació a <b>altres virus respiratoris de rellevància epidemiològica</b>.</p>

<p>La línia de treball actual es dirigeix a l'escalabilitat d'aquesta plataforma per incloure el <b>Virus Respiratori Sincitial (VRS)</b> i el <b>SARS-CoV-2</b>. L'objectiu d'aquesta ampliació és aplicar els mateixos estàndards d'anàlisi, des de la caracterització de llinatges fins a la localització geogràfica, per tal de generar un <b>marc d'anàlisi unificat</b>.</p>

</div>