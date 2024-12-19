### Traccia: Creazione e Gestione di un Grafo Personalizzato

#### **Descrizione del Task:**

Lo scopo dell'esercizio è lavorare con la classe `Grafo` per creare, manipolare e analizzare un grafo. Lo studente deve ideare un grafo personalizzato e implementarlo direttamente nel codice, insieme alle operazioni richieste.

---

### **Ideazione e Creazione del Grafo**

1. **Ideazione del Grafo**:
   - Ogni studente deve progettare un grafo personale, specificando:
     - Il tipo di grafo (**orientato/non orientato** e **pesato/non pesato**).
     - I nodi del grafo (es. città, nomi, numeri, ecc.).
     - Gli archi tra i nodi, con eventuali pesi (se il grafo è pesato).
   - Il grafo deve avere almeno:
     - 5 nodi.
     - 6 archi.
   - Lo studente deve caricare il disegno (realizzato in qualsiasi modo) del grafo realizzato. Se questo file non sará presente nella repository, lo studente non sará esonerato.

2. **Inserimento nel Codice**:
   - Lo studente deve implementare il grafo direttamente nel main, utilizzando i metodi della classe `Grafo`.
   - Inserire i nodi e gli archi ideati seguendo la struttura del proprio grafo.

---

### **Visualizzazione del Grafo**

1. **Visualizzazione dei nodi**:
   - Stampare tutti i nodi presenti nel grafo.
2. **Visualizzazione degli archi**:
   - Stampare tutti gli archi del grafo, specificando la sorgente, la destinazione e il peso (se presente).

---

### **Ricerca e Manipolazione**

1. **Ricerca**:
   - Verificare se un nodo esiste nel grafo.
   - Stampare i nodi adiacenti a un nodo specificato.
   - Verificare se un arco esiste tra due nodi.
2. **Manipolazione**:
   - Rimuovere un nodo e tutti i suoi archi associati.
   - Rimuovere un arco specifico (specificando sorgente e destinazione).

---

### **Calcolo e Confronto**

1. **Grado del Nodo**:
   - Stampare il grado entrante e uscente di un nodo specificato (per grafi orientati).
   - Stampare il grado totale per i grafi non orientati.
2. **Connettività**:
   - Verificare se due nodi specificati sono connessi.

---

### **Modifica del Grafo**

1. **Aggiunta di nuovi nodi**:
   - Aggiungere un nuovo nodo al grafo.
2. **Aggiunta di nuovi archi**:
   - Aggiungere un nuovo arco, specificando sorgente, destinazione e peso (se applicabile).

---

### **Operazioni Aggiuntive per chi ha voto da 20 in su**

  **Connettività**:
   - Implementare nella classe Grafo un metodo che dati due nodi in input verifica se sono connessi. Richimarlo poi nel main.

### **Operazioni Aggiuntive per chi vuole aumentare il voto da 22 in su**

  **Percorso Minimo**:
   - Implementare una funzione esterna al main per calcolare il percorso minimo tra due nodi utilizzando l'algoritmo di Dijkstra (per grafi pesati).

---

### **Esempio di Grafo Ideato**

Un grafo che rappresenta una rete di città:
- Nodi: `Milano`, `Roma`, `Napoli`, `Torino`, `Firenze`.
- Archi:
  - `Milano → Torino` (100 km)
  - `Torino → Firenze` (200 km)
  - `Firenze → Roma` (150 km)
  - `Roma → Napoli` (120 km)
  - `Napoli → Milano` (500 km)
```
