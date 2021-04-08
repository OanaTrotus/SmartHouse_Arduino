#  <p align="center"> **Proiect SMP 2021** <br>  *Smart House - Arduino* <br/>

## Proiect realizat de studentii:
- :link: [*Trotus Oana*](https://github.com/OanaTrotus)
- :link: [*Tudor Costin-Cristian*](https://github.com/TudorCostinCristian)

## Descriere
In cadrul cursului de *Actionari* din anul II de facultate, am implementat cu ajutorul unei placi de dezvoltare ***Arduino UNO*** si a unui ***motor DC***, o usa glisanta de garaj. Ne propunem ca in cadrul acestui proiect sa dezvoltam o aplicatie mobila care sa permita controlul mai multor parametrii corespunzatori unor noi functionalitati aduse proiectului.

## Cuprins:
 - :bulb: [Functionalitati](#F)
 - :bulb: [Componente](#C)
 - :bulb: [Surse](#S)
 - :bulb: [Implementare usa garaj](#DC)

 ## Functionalitati <a name="D"></a>
 - :clipboard: Aplicatie mobila de control
   - :clipboard: Deschiderea usii 
   - :clipboard: Aprinderea/stingerea LED-urilor
   - :clipboard: Verificarea temperaturii dintr-o incapere si reglarea acesteia
   - :clipboard: Afisarea distantei masurate de senzor
 - :clipboard: Masurarea distantei dintre vehicul si usa garajului cu ajutorul unui senzor 

 ## Componente <a name="C"></a>
   :pushpin: Plăcuță Arduino UNO R3 <br/>
   :pushpin: Breadboard <br/>
   :pushpin: Fire de legătură <br/>
   :pushpin: Modul Driver Motor <br/>
   :pushpin: Motor DC  <br/>
   :pushpin: Ventilator <br/>
   :pushpin: Rezistențe <br/>
   :pushpin: LED-uri <br/>
   :pushpin: Senzor de temperatură <br/>
   :pushpin: Modul Bluetooth <br/>

 ## Surse <a name="S"></a>
 Pe masura ce vom dezvolta proiectul, vom adauga sursele folosite in aceasta sectiune. 
 - :link: [*Link 1*](https://www.youtube.com/watch?v=HG-W3-bLvpo) : aceasta a fost ideea de la care a pornit proiectul
 
 ## Implementare usa garaj <a name="DC"></a>
Pentru construirea usii de garaj am montat doua canale in forma de ”U”, lungi de aproximativ 16 cm, pe care culiseaza usa propriu-zisa. Aceasta este realizata din betisoare de lemn lungi de aproximativ 14 cm. Barele sunt legate elastic intre ele, astfel incat sa permita infasurarea lor in partea superioara a usii pe doua role cilindrice, care sunt montate la randul lor pe un ax metalic. Axul pe care se infasoara usa este sustinut de doua suporturi fixate pe un perete frontal. La capatul axului, este montat un capac de sticla pe al carui diametru este creat un canal care va face legatura cu ansamblul motorului. Ansamblul motorului este compus din motorul propriu-zis si reductorul de turatie, care are un raport de reductie de 5:1 rotatii. Perpendicular pe axul de iesire din reductorul de turatie este montata o tija metalica, care va intra in canalul de pe capac de la capatul axului portii, realizand astfel cuplajul dintre motor si sistemul mecanic de ridicare/coborare.