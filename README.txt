1. Importer tous les projets dans Rodin
2. Faire un TheoryPath pour que ClientServer connaisse Seq
3. Pour l'automatisation de certaines preuves grave à des règles d'inférence dans Seq (Merci Peter Rivière) 
Preferences->Event-B->Sequent Prover-> Auto/Post Tactic puis dans l'onglet Profile a gauche il y a le bouton import pour le fichier "TacticProfile", et après pour que cela remplace le robot, il faut revenir l'onglet Auto/Post Tactics, et dans l'encadré Auto-Tactics choisir la tactic "Default Auto Tactic with SMT with Theory PR"

