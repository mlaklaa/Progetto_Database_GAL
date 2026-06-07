# Progetto Basi di Dati: Gestione Esami GAL

Repository contenente la documentazione e l'implementazione del progetto per l'insegnamento di Basi di Dati.

## Obiettivo del Progetto
Il progetto consiste nella progettazione concettuale, logica e nell'implementazione fisica (tramite istruzioni DDL e DML) di un database relazionale dedicato alla gestione degli appelli universitari. Come dominio applicativo e caso di studio è stato analizzato l'esame di Geometria e Algebra Lineare (GAL). 

Il sistema è strutturato per modellare due macro-aree:
* **Logistica:** gestione delle aule, assegnazione dei turni per fascia alfabetica, controllo della capienza massima, idoneità delle aule per studenti con certificazione DSA e assegnazione del personale strutturato e non strutturato per la sorveglianza e le correzioni.
* **Valutazione:** tracciamento delle singole prove (parziali o totali), calcolo delle valutazioni tecniche, gestione degli esiti finali comprensivi di eventuali integrazioni orali, verifica dello stato di verbalizzazione e controllo dei vincoli di sbarramento (es. OFA pendenti).

## Tecnologie Utilizzate
* **DBMS:** PostgreSQL. La scelta è ricaduta su questo sistema per la sua stretta aderenza agli standard SQL (ANSI) e per l'efficiente gestione dei vincoli di integrità di dominio e referenziale.
* **Progettazione:** Modello Entità-Relazione (E-R) per lo schema concettuale; Modello Relazionale per lo schema logico.
* **Documentazione:** HTML e CSS. È stata sviluppata un'interfaccia di consultazione statica per permettere la navigazione agevole tra gli schemi, le scelte architetturali e i risultati delle query SQL.

## Consultazione del Progetto
L'intera documentazione tecnica, gli schemi ad alta risoluzione e l'output delle interrogazioni SQL (Query e Viste) sono consultabili tramite la seguente pagina web interattiva:

https://mlaklaa.github.io/Progetto_Database_GAL/

## Gruppo di Lavoro
Progetto realizzato per la sessione di Giugno 2026 da:
* Laklaa Marwa (Matricola: 1099064)
* Frimane Karima (Matricola: 1100141)
* Derouich Sukaina (Matricola: 1099300)
