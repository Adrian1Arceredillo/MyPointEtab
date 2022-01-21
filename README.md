# MyPointEtab
1.	Proiektuaren funtzionaltasuna:

Java proiektu honek, formei orientatuta dago; puntuekin eta aldagaiekin, forma desberdinak egin ditzakegu. Gainera, forma hauetako bakoitzak, bere datuak ditu (azalera, perimetroa, altuera…).
Lehenik eta behin, klase bakoitzak bere test fitxategia dauka:
•	MyCircle -> TestCirclePrueba
•	MyRectangle -> TestRectanglePrueba
•	MyPoint -> TestMyPointPrueba
•	MyTriangle -> TestTrianglePrueba
Test fitxategi bakoitzaren barruan, klase horretako método guztiak probatzen dira (asmaturiko proben bitartez). Proba horietan, pauso bakoitzak zer egiten duen komentatuta dago.
Horrez gain, “guztiaTesteatu” izeneko fitxategi bat dago; bertan, klase guztiekin lan egitea posiblea da. Hau da, MyCircle, MyRectangle, MyPoint eta MyTriangle klaseak testeatu ditzakegu. Horretarako, menú sinple bat sortu dut. Bertan, menuko aukera bakoitza, klase mota bati dagokio.
Menuaren aukera bat, konkretuki bostgarrena, aurrerago azalduko den interfaze grafikoa exekutatuko du.

2.	Klase diagrama osoa:

Nahiz eta Moodle-en dagoen klase diagramaren oso antzekoa izan, nik sortutako pare bat método agertzen dira (konkretuki MyTriangle eta MyRectangle klaseetan). Metodo hauek, probak egiteko sortu ziren, eta nire ustez, erabilgarriak izan daitezke, klasearen funtzionamendua ondo ulertzeko (klasearen fitxategian daude azalduta, javadoc-aren bitartez). 
Bi diagrama egin ditut. Lehenengoan, klase bakoitzak dituen método guztiak adierazten dira; eta bigarrenean, klaseen eta paketeen arteko erlazioak agertzen dira (bigarren honetan, ez nekien erlazioak nola adierazi behar ziren, eta Internet-en ez nuen tutorialik aurkitu; beraz, baliteke txarto egotea).
(Diagramak -> hurrengo orrialdeetan)







Diagrama 1 – Erlazio gabe
 









Diagrama 2 – Erlazioekin
Erlazioen diagrama egitean, ez nekien nola adierazi paketeen eta klaseen arteko erlazioak, beraz, jarraitu dudan logika honako hau izan da: main-a edo exekutagarria den fitxategian erabili ditudan klaseen metodoak jarri ditut. Gainera, fitxategiaren hasieran, beharrezkoak diren klase guztien import-ak jarri ditut.
a)	Model paketea
 

b)	Exekutagarriak paketea:
 


c)	Probak paketea:
 

3.	Javadoc-a:

Proiektuaren javadoc-a, klase bakoitzaren fitxategiaren barne dago; hau da, klase bakoitzak, bere javadoc-a dauka (eskuz idatzitako informazio guztia metodoen gainean agertzen da).
Gainera, Netbeans-ek ahalbidetzen duen “generate javadoc” aukeraren bitartez, html egindako javadoc-a sortu dut, bain nire ustez, fitxategietan dagoena, erosoagoa da.


4.	GUI / Interfaze grafikoa

GUI-ei orientaturiko saiakera batzuk egin ondoren, pare bat adibide sortu ditut, zeinetan gauza/kontzeptu desberdinak landu ditut. Adibide hauek honakoak dira:
•	Puntu9Lerro4
•	Partxisa 

Puntu9Lerro4: fitxategi honetan, oso ezaguna den jolasa bat saiatu naiz sortzen. Jolasaren kontzeptua honako hau da: 4 lerrorekin, saiatu behar zara 9 puntuak lotzen. Hori egiteko, mousePressed izeneko evento bat sortu dut. Honen bitartzez eta jarritako kodigoaren ondorioz, erabiltzaileak klik egiten duen tokian, puntu bat agertuko da. Eta noski, bi punturekin lerro bat sortuko da.

Partxisa: fitxategi honekin arazo bat zian dut. Hau da, etxean sorturiko lehenengo “bertsioa” ondo funtzionatzen du, baina klasean irekitzean, sorturiko formen neurriak aldatzen dira, eta ez dakit nola konpondu.
