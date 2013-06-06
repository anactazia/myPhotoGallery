myPhotoGallery
==============

<p>myPhotoGallery är ett fint galleri som du kan använda för att visa upp dina
bilder på din hemsida. 

<hr />

<h3>Installation</h2>

<p>För att ladda hem myPhotoGallery så kan du trycka på länken nedan: </p>
<a href="http://www.github.com/anactazia/myPhotoGallery/archive/master.zip">Ladda ner myPhotoGallery</a>

<p>När du hämtat myPhotoGallery så läggs en komprimerad mapp på din dator (oftast i mappen hämtade filer) 
som heter <b>myPhotoGallery-master</b>.</p>

<p>Extrahera mappen på din server </p>


<p><b>EXEMPEL:</b><br />
Om du har WampServer så extraherar du mappen under c:/wamp/www/</p>


<p>Gå till den extraherade mappen och byt namn på den så att den bara heter <b>myPhotoGallery</b>.</p>

<hr />

<p>För lägga till bilder i myPhotoGallery så behöver du ladda upp dem på din server och sedan med hjälp av
en texteditor ändra i filen myPhotoGallery/index.html<br />
(Exempel på texteditor är NotePad eller <a href="http://www.jedit.org/">jEdit</a>)</p>

<p>I filen <b>index.html</b> som ligger under mappen <b>myPhotoGallery</b> finner du koden för kategorierna från
rad 33 och nedåt:<p>

<p><b>EXEMPEL:</b><br />
&lt;a class="sortLink" data-keyword="winter" href="#">Winter&lt;/a></p>

<p>För att lägga till en kategori så kopierar du koden och lägger in den på en rad bland de andra kategorierna.
Sedan så ändrar du på ställena där det i koden ovan står winter och Winter till namnet på kategorin du vill lägga
till. För att ta bort en kategori så tar du helt enkelt bort koden på raden där kategorin står.</p>

<p>Koden för att ändra, lägga till och ta bort fotografier och bilder hittar du från rad 48 och nedåt:

<p><b>EXEMPEL:</b><br />
  &lt;a class="thumbnail" title="Forreststream"
	    href="photos/forreststream.jpg" data-keywords="water forrest">
	    &lt;img src="photos/thumb_forreststream.jpg" />&lt;/a>
	    
<p>För att ändra koden för fotografierna så gäller följande: <br />
title="HÄR SKRIVER DU BILDTEXTEN"	    <br />
href="HÄR SKRIVER DU SÖKVÄGEN TILL BILDEN"	    <br />
data-keywords="HÄR SKRIVER DU VILKA KATEGORIER BILDEN TILLHÖR (med mellanslag mellan varje kategori)"	    <br />
title="HÄR SKRIVER DU BILDTEXTEN"	    <br />
src="HÄR SKRIVER DU SÖKVÄGEN TILL BILDENS 'thumbnail'"	    </p>
<p>För att lägga till en bild: kopiera koden för alla raderna som gäller en bild (från &lt;a till &lt;/a>)
Om du vill ta bort en bild så tar du helt enkelt bort hela koden för bilden som enligt ovan.</p>
<hr />

<p>Efter detta öppnar du din browser (myPhotoGallery är utvecklat i <b>Firefox</b>, så den browsern är att föredra. 
<a href="http://www.mozilla.org/en-US/">Firefox kan hämtas här</a>)</p>

<p>I adressfältet skriver du in sökvägen till filen index.html som ligger under mappen myPhotoGallery <br />

<p><b>EXEMPEL:</b><br />
<code>www.student.bth.se/javascript/myPhotoGallery/index.html</code></p>

<p>Nu kan du se ditt galleri.</p>

<p><i<b>Mycket nöje med myPhotoGallery!</b></p>
