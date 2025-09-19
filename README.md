Rapido riassunto di cosa c'è nei vari file

CARTELLE:
- Composition: classi e metodi per la composizione
- Plot_and_utils: funzioni che ho usato per i plot, metriche e le funzioni che generano i tree e i 2-community graph
- Saved Models: pkl dei modelli che ho allenato -> tutti 30 epochs 500 gibbs-steps, l'ultimo su 30IEEE ho provato 50 epochs 200 Gibbs steps
- data: 3 cartelle con i pkl rispettivamente di oggetto "GraphDataset", lista di np.array e lista di nx.Graph per ogni dataset
- deep ebm: uguale al fork originale
- graphs_out: uguale al fork originale
- result: uguale al fork originale
- src: uguale al fork originale

FILE:
- 2community, 30IEEE, tree | _eval.ipynb: dove calcolo mmd, genero grafi e valuto connessioni
- dataset_creator.ipynb : notebook dove semplicemente creo i dataset e salvo i .pkl
- embedding_study : valutazione energy landscape
- ensembler.py: uguale al fork originale
- exec_ebm.py: uguale al fork originale
- model_trainin.ipynb: dove faccio il training e salvo i .pkl dei modelli
