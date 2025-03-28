### Descrizione della sfida 🪐

**Benvenuti** nel **Ciclo Cosmico 789**, dove l'umanità ha superato non solo i confini del proprio sistema solare, ma anche quelli delle dimensioni conosciute. In questo vasto intreccio di realtà e culture, la gastronomia si è evoluta in un'arte che trascende spazio e tempo. 

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F6840884%2Fd4cd3a9d619dec67942e5344dcacf9e4%2F9gw32h.gif?generation=1737047022355670&alt=media)

Ristoranti di ogni tipo arricchiscono il tessuto stesso del multiverso: dai sushi bar di **Pandora** che servono prelibati sashimi di **Magikarp** e ravioli al **Vaporeon**, alle taverne di **Tatooine** dove l’**Erba Pipa** viene utilizzata per insaporire piatti prelibati, fino ai moderni locali dove lo **Slurm** compone salse dai sapori contrastanti - l'universo gastronomico è vasto e pieno di sorprese.

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F6840884%2F888315aac2d2bdd249e8df8fc79f8043%2Fimage.png?generation=1737046855158236&alt=media)

L'espansione galattica ha portato con sé nuove responsabilità. La **Federazione Galattica** monitora attentamente ogni ingrediente, tecnica di preparazione e certificazione necessaria per garantire che il cibo servito sia sicuro per tutte le specie senzienti. Gli **chef** devono destreggiarsi tra regolamenti complessi, gestire ingredienti esotici che esistono simultaneamente in più stati quantici e rispettare le restrizioni alimentari di centinaia di specie provenienti da ogni angolo del **multiverso**.

Nel cuore pulsante di questo arcipelago cosmico di sapori, si erge un elemento di proporzioni titaniche, un'entità che trascende la mera materialità culinaria: la **Pizza Cosmica**. Si narra che la sua mozzarella sia stata ricavata dalla **Via Lattea** stessa e che, per cuocerla, sia stato necessario il calore di tre soli. Nessuno conosce le sue origini e culti religiosi hanno fondato la loro fede attorno al suo mistero.

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F6840884%2F0c07b3e6f34ac48b9bb627387ce71531%2FTesto%20del%20paragrafo%20(1).png?generation=1737047186767633&alt=media)

### Specifiche tecniche 💻

La vostra missione è proporre una soluzione per un assistente AI che aiuti i viaggiatori intergalattici a navigare in questo ricco panorama culinario.

Il sistema dovrà essere in grado di suggerire agli utenti piatti appropriati sulla base delle loro richieste:

- Interpretando domande in linguaggio naturale
- Gestendo query complesse che coinvolgono preferenze e restrizioni alimentari
- Elaborando informazioni provenienti da diverse fonti (menu, blog post, leggi galattiche e manuali di cucina)
- Verificando la conformità dei piatti con le normative vigenti

Inoltre, il vostro sistema dovrà:

- Utilizzare tecniche di **Generative AI** (**RAG**, **Agenti AI**) per processare e comprendere i documenti forniti
- Essere in grado di:
    - Ricevere in input una richiesta utente relativa a possibili piatti che corrispondono a criteri espressi in linguaggio naturale
    - Fornire in output una lista di piatti che rispettano tali criteri sulla base della documentazione fornita

***Che la forza sia con voi.***

### Descrizione Dataset 📋

Avrete accesso a un ricco set di documenti appartenenti a questo ecosistema gastronomico galattico:

- `planets_distance_matrix.csv`
    
    Un csv che contiene la matrice delle distanze in anni luce tra i pianeti su cui si trovano i diversi ristoranti
    
- `Codice Galattico.pdf`
    
    Un documento legislativo contenente:
    
    - Limiti quantitativi applicati all’utilizzo di alcuni ingredienti nella preparazione dei piatti
    - Vincoli relativi alle certificazioni che gli chef hanno bisogno di acquisire per poter utilizzare specifiche tecniche di preparazione dei piatti
- `Manuale di Cucina.pdf`
    
    Manuale di cucina che include:
    
    - L’elenco e la descrizione delle certificazione che uno chef può acquisire
    - L’elenco degli ordini professionali gastronomici a cui uno chef può aderire
    - L’elenco e la descrizione delle tecniche culinarie di preparazione esistenti
- `Menu (30 ristoranti)`
    
    Documenti in pdf contenenti i menù di 30 ristoranti differenti
    
- `Blog post`
    
    Pagine HTML che contengono informazioni supplementari su alcuni ristoranti
    
- `dish_mapping.json`
    
    Mappatura dei piatti in id numerici progressivi, necessario per dare l’output finale

- `domande.csv`
    File contenente la lista di domande con cui verrà valutata la soluzione implementata
