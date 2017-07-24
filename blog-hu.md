# Hétfő

Az első nap négy előadót ismertem meg. Háromszor is hallottam Li Denget, annak a
[Speech Recognition, a Deep Learning Perspective](http://www.springer.com/gp/book/9781447157786) (vagy fordítva) című könyvnek
a szerzőjét, ami boldogult speeches korunkban olvastunk. Először keynote-ként
beszélt egy olyan módszerről, amit a felügyelt és a felügyeletlen tanulás közé
esik [arXiv](https://arxiv.org/abs/1702.07817): van az adat, meg vannak címkék is, csak nincs párosítva. A beharangozóban
azt írta, hogy ezt a módszert a kriptográfia ihlette, de ezt a részt az
előadásban nem mondta, vagy legalábbis én lemaradtam róla. A háromrészes
előadássorozatának, pontosabban annak az első két résznek, ami ma volt, azt a
címet adnám, hogy _A personal history of recent advances in deep learning for
speech recognition_. Az előadás során nem értettem meg semmilyen módszert, amit
azelőtt nem ismertem, és attól tartok, hogy mások sem, mégis volt benne valami
érdekes, ahogy ezt a robbanásszerű történetet mesélte,
[2012](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=GQWTo4MAAAAJ&citation_for_view=GQWTo4MAAAAJ:wGzT3bKASkAC)-re mint régi
időkre utalva.

Az első idősávban  Dechter és társának a grafikus (mármint gráfos
valószínűségi)
modellektől szóló előadására ültem be. Jó előadók, jól strukturálták is az
előadást, de valahogy nem keltette föl az érdeklődésemet, illetve a viszonylag
lassú tempó ellenére nem volt mindenütt érthető.

A szünetekben nem volt enni-innivaló, pontosabban egy nagyon túlterhelt büfében
lehetett vásárolni, amin annyira berágtam (persze csak a szó átvitt
értelmében), hogy ebédidőben meg se néztem, hogy van-e ebéd, hanem elmentem az
óvárosba, ami Bilbao talán legszebb része, mégis itt van a legolcsóbb
hagyományos ebéd, ital--előétel--főétel--desszert 12 euróért. Finomat ettem,
jól laktam, és a nagyon intenzív hőségben visszamenve beültem
[Wu](http://www.stat.ucla.edu/~ywu/research.html)nak a
képgenerálásról szóló előadására, és ott egy jót sziesztáztam. Amikor ébren
voltam, úgy tűnt, hogy színvonalas előadás, úgyhogy holnap délelőtt újra hozzá
fogok menni. A délutáni középső előadásban Ranzatót hallgattam, aki eleinte
ugyancsak gépi látásról beszélt (neki ez már a második előadása volt,
mindenkinek három van), utána pedig nyelvről. LSA-val kezdte, majd
nagyon érdekesen tért át az embeddingekre: a bigramgyakoriságot ábrázoló
mátrix (szószor szó) dimenziócsökkentéssel simított alakját fogalmazta át
hálóvá. Őt is tovább hallgatom holnap.

# Kedd

A ma reggeli keynote [Richard Socher](http://www.socher.org/) volt, aki ugyan megfázás miatt csak
Skype-on szerencséltetett minket, mégis elég érdekes dolgokról számolt be. Úgy tűnik
van élet az NLP-ben deep learning cunami idején is. Most csak ideírom a
kulcsszavakat, aztán majd
utánaolvasok: 
[dynamic memory model](http://metamind.io/research/state-of-the-art-deep-learning-model-for-question-answering), 
[quasi-recurrent neural network](https://einstein.ai/research/new-neural-network-building-block-allows-faster-and-more-accurate-text-understanding) 
(az RNN és a CNN bizonyos tulajdonságait egyesítő modell szövegre), 
[A  Deep  Reinforced  Model for Abstractive Summarization](https://einstein.ai/research/your-tldr-by-an-ai-a-deep-reinforced-model-for-abstractive-summarization), és 
[many-task learning](https://einstein.ai/research/multiple-different-natural-language-processing-tasks-in-a-single-deep-model).

Wunak a másik két előadására is bementem. Nem mondom, hogy mostantól mindent
tudok a generatív modellekről, de voltak érdekes dolgok, főleg a mai elsőben: a
lineáris látens változós modell különféle interpretációi, a nehéz farok és a
látens változók függetlenségének kapcsolata, ritka kódolás. Az utolsó előadás
végén sorolt egy csomó kapcsolódó, részben új modellt: Helmholtz-gép, GAN,
introspektív generatív modell, önregresszív modellek (pixel-RNN), a
függetlenkomponens-elemzés általánosítása, real NVP (nem tudom mi az),
aktiváció-maximalizálás, plug and play generatív modell, diffusion modell.

Ranzato ma már nem tett rám olyan nagy benyomást, de azért neki is volt pár
gondolata, aminek szeretnék utánaolvasni: az egyik a [bag of embeddings](https://learning.mpi-sws.org/mlss2016/slides/Arthur_Szlam_MLSS-2016.pdf), ami egy
olyan reprezentáció, amiből a mondat a szavak sorrendjétől eltekintve
visszakapható (valamiért azt sejtem, hogy ez valami kvantálás féleség, de
könnyen előfordulhat, hogy tévedek). A [FastText](https://github.com/facebookresearch/fastText)et is szóba hozta, amit mint sok
nyelvre rendelkezésre álló embeddinget mi is használunk, de a modellt magát nem
ismerem. Utólag találtam még tőle [egy fontosnak tűnő
cikket](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=NbXF7T8AAAAJ&citation_for_view=NbXF7T8AAAAJ:tHtfpZlB6tUC) rnn4nlp témában

Deng előadásának harmadik, nyelvi része (ami a ppt 158. oldalán kezdődik) az
utolsó öt percre maradt. A szlájdjait bevallása szerint két éve írta és azóta
nem frissítette, ezért érdekesen tudta kommentálni a végén levő jóslatokat,
hogy mennyire váltak be. Visszautalt Socher reggeli előadására, hogy az talán
megvalósít valamit az őáltala jósolt fejlődésből.

[George Cybenko](http://www.dartmouth.edu/~gvc/) a viselkedésről beszélt általában, amit nem annyira szakmai
szempontból, hanem ilyen furcsa önismereti tréningként volt érdekes hallgatnom.
Szabados Levente kollégája, Florian dicsérte Baldinak a más
természettudományokban való alkalmazásról szóló előadását.  A következő
napokban csúnya ütközések lesznek a szempontomból: az egyik sorozatban az
embeddingekről szóló előadással egyszerre lesz egy emós (a fő téma a chatbotok, az előadó 
[Soo-Young Lee](https://scholar.google.com/citations?user=QXGini0AAAAJ&hl=en)) és 
egy agyas (Maximilian Riesenhuber, [kutatócsoport](http://riesenhuberlab.neuro.georgetown.edu/index.html)), 
utolsó két nap pedig az NLP-nek dedikált előadással egyszerre egy _exploiting
domain bias_ ([Michael C. Mozer](http://www.cs.colorado.edu/~mozer/index.php)), (és 
egy seq2seq, [Alessandro Sperduti](https://scholar.google.com/citations?user=JsExaWMAAAAJ&hl=en)).

# Szerdától péntekig

Szerdától már nem írtam esténként ilyen félszakmai beszámolót, úgyhogy most
egybe írom le az egészet.
[Yih](https://www.microsoft.com/en-us/research/people/scottyih/#)hel kezdem, aki egy halk szavú előadó, de eléggé
otthon van a témájában, a tudásbázis-embeddingben (most egy kicsit bánom, hogy
nem szoktam magyarítva, beágyazásnak mondani az embeddinget, mert akkor itt
adná magát a tudásbázis-beágyazás). Az szlájdjai átfedtek Gaoéival, mindketten
az ideghálók történetével kezdték, Yih korai
mesterségesintelligencia-rendszereket is említett egy-egy szlájd erejéig.
Tetszett, ahogy a hivatkozásokat rövidítette (Chang+ EMNL 14), meg hogy minden
kétváltozós függvénynek (amiből kérdésmegválaszolás (question answering, QA),
esetén ugye van egy pár) alanynak hívta az első argumentumát, és tárgynak a
másodikat. A szemantikai típusokat használó QA-nak a mi 4lang-os elképzeléseink szempontjából fontos jelensége
az áthidalás (bridging, Berant+ EMNL 13): abban a kérdésben, hogy _Which
college did Obama go to?_, könnyen felismerjük az college és az Obama
kulcsszavakat, de a _go to_ igei szerkezet felismerése a gyakorlatban túl nehéz
lenne, ezért máshogy kell kitalálni, hogy vajon mi a kérdés ezzel a személlyel
és ezzel az intézménytípussal kapcsolatban. Egy csomó hivatkozást kiírtam a
szlájdjairól azzal, hogy el szeretném olvasni.

A tavalyi konferenciákon (LREC majd ACL) kezdett föltűnni, hogy milyen okos
ember lehet ez a Gao, milyen sok jó cikk szerzői között bukkan fel. Aztán
lassan rájöttem, hogy több Gao nevű nyelvtechnológus is van, most pedig, hogy a
nyári egyetemről hazatérve utánanéztem, a több közül kettőnek a munkája is
relevánsnak tűnik embedding témában. Mindenesetre most nem [Bin
Gaó](https://scholar.google.hu/citations?user=O45XKiQAAAAJ&hl=en&oi=sra)ról
fogok írni, aki a Xu+ 14 és a Tian+ 14 szerzői között szerepel, hanem [Jianfeng
Gaó](https://www.microsoft.com/en-us/research/people/jfgao/#)ról. Az előadást a Hintonéhoz hasonló flegmatikus személyisége fűszerezte
(what is _more interesting, or less boring,..._). Ahogy már írtam, már a
,,kibernetika" történetéről szóló bevezetőjével levett a lábamról, Az első
nagyobb témája a mély szemantikus hasonlósági modellek voltak: a gépi fordítás
és a webkeresés problémáját is úgy fogalmazta meg, hogy az outputnak (fordítás
illetve találat) hasonlónak kell lennie az inputhoz (eredeti mondat illetve
keresőszó). 

George Cybenko előadásának sajnos kihagytam a számomra talán pont legérdekesebb
részét, amikor a közönség nagy megelégedésére elmondta a
[Myhill--Nerode-tételt](https://en.wikipedia.org/wiki/Myhill–Nerode_theorem).
Beszélt a rejtett Markov-modellek (hidden Markov models, HMMs) tanulására
vonatkozó
[Baum--Welch-algoritmusról](https://en.wikipedia.org/wiki/Baum–Welch_algorithm),
és nemnegatív mátrix-felbontásáról (az n-gram gyakoriságokat tartalmazó
mátrixéról és ennek a HMM-ekkel való kapcsolatáról). Az sorozat később
részében bevezette a megerősítéses tanulás formalizmusát, és megosztotta a
tapasztalatait pénzügyi folyamatokkal kapcsolatban (tőzsdei megbízások deanonimizálása).

Az utolsó sorozatban [Richard Zemel](www.cs.toronto.edu/~zemel) óráit választottam, aki visionről beszélt eleinte
kicsit talán ismeretterjesztő módon, de -- valószínűleg az okos kérdések hatására --
később jobban belement a technikai részletekbe. Pár hónapos eredményeket,
folyamatban levő projekteket is megosztott. Egyik témája a few-shot learning
volt, ahol néhány kép (gyümölcsök vagy az Omniglotról való egzotikus
karakterek) alapján egy új példányról kell megmondani, hogy az eddigiek közül
melyik osztályba tartozik, pl. tehén hieroglifa vagy alma.
