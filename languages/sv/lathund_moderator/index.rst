Lathund för moderatorer
=======================

En snabbgenomgång av funktionerna för att skapa ett möte.


Behöver du ett möte?
--------------------

Om du inte redan är moderator för ett möte så behöver ett skapas. Bara administratörer för VoteIT-servrar kan i nuläget skapa möten.
Är du administratör finns alternativet **lägg till** i vänsterkolumnen.

Observera att möten kan skapas utifrån gamla möten. På så sätt kan mycket arbete sparas in med inbjudningar och dylikt.


Publikt eller slutet möte
-------------------------

Som standard måste deltagarna ha inbjudan för att vara med i möte. Är du nöjd med det, hoppa till nästa sektion.

Om deltagarna ska kunna komma in i mötet själva:

* Gå till menyn **inställningar** > **accesspolicy**
* Välj **publik tillgång**
* Gå till menyn **inställningar** > **Inställningar för vald accesspolicy** om du inte redan hamnat på den sidan
* Välj vilka roller deltagarna ska kunna få

Alla med länken till mötet kan nu komma in i det och få de rättigheter du specificerat.


Redigera mötets förstasida och publika presentation
---------------------------------------------------

* Klicka på kugghjulet nära rubriken till höger på mötets förstasida. Välj redigera.

eller

* Menyn **inställningar** > **Mötespresentation**


Skapa dagordning
----------------

I vänstermeny finns knappen **Ändra dagordning**. Du kan nu använda en standarddagordning eller lägga till punkterna själv.
Utöver de vanliga årsmötespunkterna kan digitala årsmöten använda lite extra punkter. Det är ingen nackdel att ha saker som:

* Mötesordning
* Tidsplan
* Ordningsfrågor
* Fikarum - ett ställe att ha informella övriga diskussioner "off topic".


Använda standarddagordning
""""""""""""""""""""""""""

* Klicka på knappen **Ändra dagordning**
* Klicka på fliken **Standarddagordningar**
* Välj **Använd i möte** för den dagordning som passar

Lägga till ny dagordningspunkt
""""""""""""""""""""""""""""""

* Klicka på knappen **Ändra dagordning**
* Fliken **Lägg till dagordningspunkt** bör redan vara markerad - bara fyll i formuläret och spara

Ändra ordningen mellan dagordningspunkter
"""""""""""""""""""""""""""""""""""""""""

* Klicka på knappen **Ändra dagordning**
* Klicka på fliken **Sortera**
* Dra och släpp - spara

Observera att ordningen är inom varje sektion. En dagordningspunkt som är pågående kommer alltid ligga i sektionen pågående,
och ordningen i den sektionen avgörs av denna lista.

Ändra status på många dagordningspunkter
""""""""""""""""""""""""""""""""""""""""

För att deltagarna ska kunna se dagordningspunkterna så får de inte ha statusen **privat**. Du kan ändra enstaka
dagordningspunkter i kugghjulet i dagordningen till vänster, annars finns en funktion för att justera många direkt.

* Klicka på knappen **Ändra dagordning**
* Fliken **Hantera**
* I sektionen privat, markera de dagordningspunkter du vill göra till kommande genom att klicka i kryssrutan till vänster om dem.
* I listan under tabellen välj **Kommande**
* Klicka **Ändra tillstånd**

Bjud in deltagare
-----------------

Det finns flera sätt att ge deltagare tillåtelse att vara med i möten.

Skicka inbjudningbiljett via mail - slutna möten
""""""""""""""""""""""""""""""""""""""""""""""""

* Klicka på **Deltagare** > **Bjud in deltagare**
* Följ formulärets instruktioner och klicka **Lägg till**
* Deltagarna får nu ett epostmeddelande med en länk som kan användas för att komma in i mötet

.. warning::

    Observera att epostmeddelanden som skickas till många via VoteIT lätt hamnar i spamfoldern hos mottagarna. Du bör informera deltagarna om
    att en inbjudan är på väg, så de förväntar sig inbjudan och reagerar om den inte kommer.

Skicka länk - öppna möten
"""""""""""""""""""""""""

Skicka mötets länk via epost till deltagarna. Efter att de har registrerat sig kan de begära tillträde till mötet och få
de rättigheter du har ställt in via accesspolicyn.

.. tip::

    Länken till mötet är samma som förstasidan i mötet, sannolikt något i stil med: **https://mote.voteit.se/<Mötets-namn>**

Lägg till existerande användare
"""""""""""""""""""""""""""""""

Om du redan vet användarnamnet på någon kan du även lägga till den personen via menyn:

* **Deltagare** > **Lägg till användare**

Starta mötet
------------

Du har vid det här laget deltagare och dagordningspunkter, men för att mötet ska kunna ha pågående dagordningspunkter och omröstningar
behöver mötet startas.

* Gå till mötets förstasida, t.ex. genom att klicka på titeln på mötet eller på texten **Dagordning**
* Klicka i kugghjulet som ligger till vänster om rubriken för mötet
* Välj **pågående** under **Ändra tillstånd**

Du kan nu göra dagordningspunkter till pågående genom att klicka i respektive kugghjul i dagordningen i vänsterkolumnen.

Hantera diskussion och förslag
------------------------------

Som moderator kan du justera tillståndet på andras förslag och till och med radera eller dra tillbaka dem. Du bör som regel
undvika att göra det om mötet inte utsätts för regelrätt sabotage.

* För att hantera förslag, använd kugghjulsmenyn bredvid dem.
* För diskussionspunkter finns länkar direkt under dem.

.. tip::

    Om du inte redan kan funktionaliteten för hashtaggar och omnämnanden, läs in dig på det i deltagarmanualen.

Observera att förslag har arbetsflöde med följande tillstånd:

* **Publicerad** - förslagets grundtillstånd. Det kan bara väljas när du skapar en omröstning om det är publicerat.
  Användare kan dra tillbaka sina förslag så länge de är i detta tillstånd.
* **Låst för omröstning** - När förslaget deltar eller ska delta i en omrösting. Det kan inte längre dras tillbaka.
  Förslag får detta tillstånd när en omröstning blir kommande eller pågående om de deltar i den omröstningen.
* **Tillbakadragen** - Ska inte behandlas.
* **Bifallen** - Har hanterats och bifallits.
* **Avslagen** - Har hanterats och avslagits.
* **Ohanterad** - Förslaget behandlades aldrig av mötet.

.. tip::

    Många tillbakadragna förslag? Du kan välja att gömma dem som standard i menyn **Inställningar** > **Layout och widgets**

Observera att alla tillstånd inte är tillgängliga hela tiden. Ett tillbakadraget förslag måste t.ex. publiceras först innan det kan få ett annat tillstånd.

Omröstningar
------------

Klicka på knappen **Lägg till omröstning** precis vid förslag.

* I **omröstningsmetod** finns de metoder som är registrerade och aktiverade för mötet. Du kan ändra dessa via **Inställningar** > **Mötets omröstningsinställningar**
* I listan **förslag** finns *endast* förslag som har tillståndet **publicerad**.
* Tänk på att du oftast bör ha **avslå allt** som alternativ. Du kan skapa detta förslag om du glömt det via kryssrutan **Avslå förslag**.
* Tiderna för mötet är information till deltagarna. Ingenting automagiskt händer vid de klockslagen! Ett dygns omröstningstid är standard.
* När du sparat har vissa omröstningmetoder ett extra formulär med omröstningsinställningar. Du kan även gå tillbaka till detta via kugghjulet vid omröstningens titel.

Omröstningen har nu tillståndet **privat**. Bara du kan se den. Inga förslag har justerats till **Låst för omröstning** än.
För att redigera inställningar för omröstningen, använd kugghjulsmenyn till höger om omröstningens titel.

För att göra omröstningen till **kommande**, klicka i kugghjulsmenyn och välj kommande. Du kan fortfarande justera inställningar och lägga till / ta bort förslag,
men de förslag du har med bör vara låsta för omröstning nu.

Gör på samma sätt för att göra omröstningen **pågående**. Både mötet och dagordningspunkten måste vara pågående för att det ska gå. När omröstningen väl är pågående
kan du inte ändra den, annat än att avsluta eller avbryta den.

Avsluta omröstingen genom att välja **Avslutad** i kugghjulsmenyn. Resultatet beräknas nu. Beroende på vilken omröstningsmodell du använt så kan även förslag
ha justerats som avslagna eller bifallna. I annat fall kan du behöva göra detta manuellt, eller inte alls. (T.ex. om ni röstat om hur mycket debattid en punkt ska få på ett fysiskt möte)

När något går fel
"""""""""""""""""

Ibland kan omröstningar behöva tas bort, eller till och med raderas. Raderar du en omröstning så loggas detta i servern, men inga av förslagen som deltog i omröstningen försvinner.
Ett alternativ är också att välja **Avbruten** som tillstånd i kugghjulsmenyn. Då beräknas inget resultat. Om din omröstning inte är startad än så kan du fortfarande redigera och ändra den.

För att återställa och skapa en ny omröstning efter att du raderat eller avbrytit, klicka i förslagens kugghjulsmeny och gör dem publicerade igen.
Är de låsta för omröstning så kan de inte delta i en ny omröstning.

Avsluta en dagordningspunkt
---------------------------

I dagordningspunktens kugghjulsmeny (antagligen till höger om dess rubrik, eller i dagordningen i vänsterkolumnen) klicka på **Avslutad**.

Nu kan ingen lägga till fler förslag eller omröstningar, men diskussionen kan fortsätta.

Behöver punkten öppna igen, bara klicka i kugghjulsmenyn och välj pågående igen.

Avsluta mötet
-------------

På samma sätt som mötet startades - gå till mötets startsida och använd kugghjulsmenyn till höger om rubriken.
När mötet är avslutat kan inget längre ändras, så länge mötet inte startas igen.

Protokoll
---------

Under menyn **Möte** > **Protokoll** finns nu ett beslutsprotokoll. Ett tips kan vara att kopiera texten och använda som grund om du behöver mer än så.
