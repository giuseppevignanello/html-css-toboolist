# Appunti sull'esercizio di ieri

Quella al centro è un "Card", la si può dividere in card top e card buttom
Non mettere il colore nel container, ma in un div interno "Card". Di base il container si lascia pulito. 
"Card header" è molto utilizzato nei framework (anche in Bootstrap che è quello che useremo)
"Button" solitamente viene abbreviato in "btn"  ù
Nel CSS non usare "general", ma "common" 
*importante* Selezionare con un quadrato su Penpot per scoprire esattamente quanti pixel ci sono
Creare le utility prima, ogni volta che se ne presenta la necessità 
Ctrl D serve a segnare tutte le altre occasioni delle parole 

# Margin collapse
Il margine collassa quando due margin entrano in contatto. Vale solo in verticale e domina il margine maggiore. *Eccezione*: Se i margini sono di segno opposto effettivamente si sommano

# Cercare 

Search Replace 

# Assets
Una cartella Assets si usa per metterci dentro img e css

# Regola di reset 

con * si resetta tutto quanto dando 0 a margin e padding e border-box al box-sizing

# Refactoring 

La pulizia del codice

# Pseudo Selector  

:root {
    --tb--white: ...
    ecc
    ecc
}

body {
    bg-color: var(--tb-white)
}

# Per commentare il CSS

#region nome_della_regione 

#endregion nome_della_regione

# Modi per selezionare il CSS
 L'ordine degli attributi per <a> è quello indicato nelle'slide [hover, active, ecc.] Non può essere un altro. 