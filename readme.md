Esercizio di oggi: Vue To Do List

nome repo: vue-todolist


Descrizione: Rifare l'esercizio della to do list. Questa volta però ogni todo sarà un oggetto, formato da due proprietà:
text, una stringa che indica il testo del todo
done, un booleano (true/false) che indica se il todo è stato fatto oppure no
MILESTONE 1 Stampare all'interno di una lista HTML un item per ogni todo. Se la proprietà done è uguale a true, visualizzare il testo del todo sbarrato.
MILESTONE 2 Visualizzare a fianco ad ogni item ha una "x": cliccando su di essa, il todo viene rimosso dalla lista.
MILESTONE 3 Predisporre un campo di input testuale e un pulsante "aggiungi": cliccando sul pulsante, il testo digitato viene letto e utilizzato per creare un nuovo todo, che quindi viene aggiunto alla lista dei todo esistenti.

<!-- LOGICA -->

1- debug per verificare il funzionamento dei link 
2- impostazione statica del layout

3- struttura base vue 
4- creazione  array di oggetti

5-milestone 1 stampiamo all'interno dell'html i nostri list item recuperati dall'array di oggetti
6 - barriamo gli item che hanno valore booleano corrispondente a true 
6.1 - creo una classe che crea la linea di sbarramento eseguo il bind della classe nell'html
7-operatore ternario che cambia l'icona del bottone in base alla condizione
8- definire il metodo per rimuovere un item
9- definire il metodo per aggiungere un nuovo item
 9.1 definire una stringa vuota
 9.2 controllo se il campo new item non e vuoto
 9.3 pusho il nuovo item nell'array
 9.4 resetto il campo item dopo l'aggiunta

