# AI_Engineering_Projects_GenAI
My AI Engineering Master's Projects - Generative AI

# CyberEye Solutions - Data Augmentation per la Sicurezza delle Centrali Elettriche

Il progetto **Data Augmentation per la Sicurezza delle Centrali Elettriche** affronta una sfida critica nel campo della sicurezza cibernetica per infrastrutture critiche: la **limitazione dei dataset di addestramento** per i sistemi di riconoscimento di immagini.

Attualmente, i modelli di sorveglianza di CyberEye Solutions faticano a riconoscere con precisione e tempestività oggetti e comportamenti potenzialmente pericolosi all'interno delle centrali elettriche a causa di un dataset di addestramento insufficiente e poco diversificato. Il progetto supera questa limitazione, **arricchendo il dataset esistente** attraverso tecniche innovative di **Data Augmentation** per migliorare l'efficacia e l'affidabilità del sistema.

---

### Benefici della Soluzione

Questa iniziativa strategica porta a diversi vantaggi chiave per CyberEye Solutions:

* **Miglioramento della Sicurezza:** Un modello addestrato su un dataset più ampio e variegato rileva con maggiore precisione e tempestività minacce e anomalie, aumentando la sicurezza delle infrastrutture critiche e riducendo il rischio di incidenti.
* **Efficienza Operativa:** L'automazione della generazione di dati riduce il tempo e le risorse necessarie per l'addestramento dei modelli, consentendo al team di CyberEye Solutions di concentrarsi su attività di analisi e mitigazione delle minacce più complesse.
* **Innovazione Tecnologica:** L'adozione di tecniche avanzate di deep learning e generazione di dati posiziona CyberEye Solutions come un pioniere nel settore della sicurezza cibernetica per infrastrutture critiche.

---

### Dettagli Tecnici del Progetto

Il progetto si articola in quattro fasi principali:

1.  **Acquisizione e Preparazione del Dataset:** Si utilizza il dataset OxfordIIITPet da PyTorch come punto di partenza. Questo dataset, seppur non specifico per centrali elettriche, fornisce una base solida per sperimentare le tecniche di Data Augmentation che vengono poi adattate a contesti più specifici.

2.  **Generazione di Dati Sintetici:** Questo è il cuore del progetto. Si applica un processo a più stadi:
    * **Image Captioning:** Generazione di descrizioni testuali iniziali per le immagini del dataset base.
    * **Generazione di Testo:** Utilizzo di un modello generativo di testo (come un Large Language Model) per creare varianti e descrizioni alternative a partire dalle caption iniziali.
    * **Generazione di Immagini:** Impiego di un modello generativo di immagini (come un Generative Adversarial Network o un diffusion model) per produrre nuove immagini sintetiche a partire dalle caption originali e da quelle generate.

3.  **Addestramento del Modello:** Un modello di riconoscimento di immagini viene addestrato sul dataset ampliato, che include sia le immagini originali che quelle sintetiche generate.

4.  **Valutazione delle Performance:** Le performance del modello addestrato vengono accuratamente valutate utilizzando metriche standard come **accuracy**, **precision** e **recall**. Un'analisi comparativa tra il modello addestrato sul dataset originale e quello addestrato sul dataset aumentato dimostra l'efficacia della nostra soluzione.

---

### Conclusioni

Questo progetto rappresenta un passo fondamentale nell'impegno di CyberEye Solutions per garantire la massima sicurezza delle infrastrutture critiche. Sfruttando l'innovazione tecnologica e le tecniche di Data Augmentation, si crea un sistema di sorveglianza più robusto e intelligente, definendo nuovi standard nel settore della sicurezza cibernetica.
