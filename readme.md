# WEB APP DI RIPRODUZIONE LAYOUT DI SPOTIFY

---

## Caratteristiche richieste:
**1   Web App (100 ViewPort Height)**
**2   Responsività per device** 
    **- desktop**
    **- tablet**
    **- mobile**
    **- mobile XS**
**3   Effetti hover (*bonus*)**

---

*Nell'esercizio, si sono riprodotti i mockup richiesti, a seconda dei device.*
*Sono stati utilizzati, strutture **flexbox** annidate, pseudo selettori (`::before`), posizionamenti `fixed`, `relative`, `absolute`.*

*Nello specifico:*
    1   a seconda dei device utilizzati, la barra laterale presenta due tipologie di layout:
        -   full layout, con coppie *icona - testo* e playlist (con presenza di scrollbar al bisogno).
        -   reduced layout, con sole icone, menu ridotto ed assenza delle playlist.
    2   bottom bar (equivalente al footer) che presenta i controlli del player e la locandina del brano in            esecuzione, i cui elementi si riposizionano e, all'occorenza spariscono, a seconda del device in uso.
    3   sezione principale, contenente le cards, disposte in fila per 6 (desktop), 4 (tablet), 2 o 1 (mobile) elementi per riga.

In tutto l'esercizio, sono presenti effetti hover, quali cambi di colore sulle voci dei menu, opacita' su cards e icone, transizioni sulla "*call to action*".

### Media query:

Le media query presenti nell'esercizio sono le seguenti:

1   **`max-width: 768px:`** versione *tablet* --> con modificazioni nella bottom bar e nella sezione principale
2   **`max-width: 425px:`** versione *smartphone medium* --> come sopra
3   **`max-width: 375px:`** versione *smartphone small* --> con modificazioni nella bottom bar, nella side bar e nel main
4   **`max-width: 320px:`** versione *smartphone extra-small* --> come sopra, con variante *1 card per riga* (**EXTRA**)
5   **`max-height: 350px:`** versione *altezza small* --> con modificazioni sulla side bar e relativi menu (**EXTRA**)
6   **`max-height: 320px:`** versione *altezza extra-small* --> come sopra (**EXTRA**)
