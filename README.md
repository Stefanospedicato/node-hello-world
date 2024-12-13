Node Hello World
===
esercizio di oggi: **node-hello-world**
repo:`node-hello-world
**Esercizio**
1. Creiamo la prima applicazione con NodeJs e inizializziamola con `npm init`
2. Scriviamo un file `index.js` che dovrà stampare nel terminale “Hello World”. Proviamo ad eseguirlo dal terminale stesso usando i comandi di node base.
3. Impostiamo ora uno script “start” in `package.json` e facciamo in modo di lanciare il nostro script con `npm run start`
4. Impostiamo un nuovo script “watch” in `package.json` che possa essere lanciato con `npm run dev` e che aggiorni in tempo reale le modifiche ai nostri file. Lanciamolo e proviamo a cambiare il nostro codice in modo che stampi nel terminale “Hello Boolean”. Dovremmo vedere il terminale senza fermare e rilanciare il server.
5. Proviamo a passare da terminale una parola come argomento. da mostrare dopo “Hello”. Dovremo quindi stampare “Hello *parola_passata”*
## SVOLGIMENTO
- Ho creato innanzitutto il mio file js.
- Ho poi utilizzato il terminale per inizializzare il mio file e creare il file json.
- Nel json ho creato i due nuovi script richiesti da consegna. e li ho utilizzati nel terminale per controllare il loro funzionamento.
- Ho successivamente creato una const in js per la mia parola da mostrare nel console log dopo la scritta HELLO, utilizzando il process.argv con indice 2.
- Ho infine testato il mio console.log richiamando con il template literal la mia parola per controllare se si fosse associata nel modo corretto a ciò che ho scritto nel mio terminal.
  