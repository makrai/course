#initialization, Karpathy course

makrai
>Sziasztok! Professzor Ng annak idején azt tanította, hogy a véletlen
inicializálás szórását a ki?-fok függvényében érdemes választani, de a mi nem
beszéltünk erről. Tudtok erről valamit? Ez kiment a divatból? (Rákeresve
stackoverflow-n csak egy válaszra adott harmadik kommentben találtam.)
http://stackoverflow.com/questions/23194818/normalise-weights-to-produce-midrange-function-signal 
stackoverflow.com

daniel
>10:50 AM Nem tudom, hogy mit mondott Ng, de egy másik kétbetűs, He módszerét
szokták mostanában szeretni. És ki tudják kalkulálni az analitikusan legjobb
szórást, viszont személyes preferencia, hogy milyen eloszláscsaládból vétetnek
azzal a szórással. Itt elég jól le van írva, és hivatkozva van Glorot és He:
10:50
http://datascience.stackexchange.com/questions/13061/when-to-use-he-or-glorot-normal-initialization-over-uniform-init-and-what-are  
datascience.stackexchange.com
When to use (He or Glorot) normal initialization over uniform init? And what
are its effects with Batch Normalization?
I knew that Residual Network (ResNet) made He normal initialization popular.
In ResNet, He normal initialization is used , while the first layer uses He
uniform initialization.I've looked through
10:51 Ahogy itt is írja, ez azért sokkal kevésbé fontos mostanában, mint régen
(amikor perdöntő volt),
10:51 mert a Batch Normalization magától beállítja a megfelelő szórást,
úgyhogy nem tud elfajulni. (edited)
10:52 Karpathy Stanfordi kurzusa fent van youtube-on, ott van ez
szuperérthetően elmondva, grafikonokkal illusztrálva.

>ndavid
10:54 AM tudsz még ilyeneket? :slightly_smiling_face:
10:54 ezek már megint DeepMindos csávók, ugye?
daniel
10:55 AM nem, He még Microsoft Asia.
ndavid
10:55 AM de a Batch Normalization
daniel
10:55 AM Batch norm az érdekes eset, mert ő az egyik legrégebbi haverom, a
Christian Szegedy.
10:56 Google, nem Brain, nem Mind.

10:56 Karpathy OpenAI
10:57 Előkerestem a Karpathy kurzus releváns részét, nagyon érthető:
10:57 https://youtu.be/mzkOF4tULj8?t=37m7s  
