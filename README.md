# Neural-Networks-research---my-BSc-thesis-project

## Publication about the first part of my research:
"Applying the Standard Non-linearity of Cellular Neural Networks in Convolutional Networks"
https://ieeexplore.ieee.org/document/8470498


english below

## Kivonat

Az elmúlt években számos területen áttörést hozott a gépi tanulás, azon belül a neurális hálózatok alkalmazása. Ezen programozási módszer lényege, hogy tanítómintákat adunk a rendszernek és valamilyen feladatra tanítjuk. E módszer akkor működik jól, ha nagy számú tanítóminta áll rendelkezésre. Kis mintaszám esetén a pontosság nagymértékben lecsökken. Ezt dolgozatomban kísérletileg is megmutatom. Az emberi tanulás azonban azon esetekben is képes absztrakt jellemzők és tulajdonságok szintetizálására, mikor csupán néhány minta áll rendelkezésre egy lehetséges halmazból.

A természetben az emberi tudást messze túlszárnyaló effektivitású rendszerek találhatók. Talán a legjobban az agy képességei ejtik ámulatba az embert. Nem csoda, hogy a gépi tanulás is az e szerv működéséből inspirálódik, nagy részben ennek köszönheti fejlődését. Kutatásom során mélyen tanulmányoztam az emberi agy és a mesterséges neurális hálózatok összefüggéseit, ezt dolgozatomban be is mutatom.

Gyakorlati kutatásom célkitűzése olyan módszer kutatása volt, mely javítja a neurális hálózat pontosságát alacsony mintaszám esetén. Ezt két módon is elértem. Az egyik az volt, hogy a mesterséges neuronok általánosan használt ReLU aktivációs függvénye helyett egy új függvényt konstruáltam. Ezzel 5,11%-kal sikerült a háló pontosságát növelnem a referencia ReLU aktivációs függvényt használó futtatáshoz képest.

Kutatásom másik részeként a Matching Network hálózatarchitektúrával foglalkoztam. Kimutattam, hogy a neurális háló kimenete nagy mértékben függ a support halmaz választásától. Ebből következik, hogy a support halmaz elemeinek véletlenszerű választása helyett található egy olyan optimális support halmaz, mellyel a klasszifikáció lényegesen jobb lesz a véletlenszerűen generáltnál. A pontosság javulásának mértéke átlagosan 20% körüli.


## Abstract

In recent years adoption of neural networks for machine learning succeeded in many area of science. This programming method is efficient, in cases when have lots of training samples; however, if the number of the samples decreases, the accuracy will fall down significantly. I am showing empirical evidence tho this phenomenon in the thesis. In contrast to this, however, human learning can solve such tasks easily, so people do not need thouands of samples to synthetize abstrakt features from a set.

There are a lot of processes in nature, which have so high efficiency, that humans can not even approximate in practice. Maybe the most amazing is the capabality of the human brain.  Not surpisingly, that machine learning draw inspiratin from this organ too. This art of science developed mostly due to the brain research. During my work I studied deeply the correspondence of the human brain and the artificial neural networks. I also demonstrate this in my thesis.

During my practical research my aim was to find methods, that improve the accuracy of neural networks in case of low number of traning samples. I achieved this by two ways. Firstly I adopted a new type of activation function instead of the widly used ReLU function. This way tha accuracy increased by 5% compared to the referency running with the ReLU function.

The second part of my research refered to the Matching Network architetcure. I demonsrtated, that the output of this neural network highly deoendent from the chosen support set. From this statement comes that instead of choosing the support set elements randomly, we can find an optimal set. By using this set the classification will be significantly better than by using the randomly generated. I did prove it. The difference in accuracy is around 20%.
