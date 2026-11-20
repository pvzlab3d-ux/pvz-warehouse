# Ufficio virtuale PVZ 3D – istruzioni degli agenti

Copia di riferimento delle istruzioni che gli agenti leggono dal database
(Supabase, tabella `public.ufficio_docs`, collezione `istruzioni`).
Versione 2, ricostruita il 20 novembre 2026 dopo l'errore Acquamarina
(email sull'acquaristica a un negozio di rivestimenti, settore dedotto dal nome).

Novità principali:
- regola "niente prova, niente messaggio": ogni azienda va verificata leggendo
  una pagina e copiando una frase testuale che dice cosa fa (campo `verifica` nel CRM);
- obiettivi numerici solo come massimo, mai come minimo;
- messaggi scritti da zero dalla prova, non da modelli per categoria;
- controllo finale in 5 domande prima di ogni bozza;
- registro `bozze` con la prova di ogni messaggio, controllato da Nathan ogni sera;
- Nathan non modifica più le istruzioni da solo: propone, Filippo approva.

Se modifichi un file qui, aggiorna anche il documento nel database (e viceversa).
