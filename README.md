### **Objectifs du TP :**

 L’objectif général du TP est de **résoudre numériquement un problème de programmation linéaire** en utilisant Python et les solveurs intégrés
 de la bibliothèque **scipy.optimize.linprog** (HiGHS ou Simplex). Les étudiants développeront une compréhension approfondie des étapes
 nécessaires à la formulation et à la résolution de ce type de problème, tout en explorant l’analyse post-optimale et l’étude de sensibilité.

 *Objectifs spécifiques:*

 1. Introduire les étudiants aux solveurs de SciPy (par exemple HiGHS ou Simplex).
 2. Comprendre l'interprétation des résultats fournis par les solveurs, y compris les valeurs optimales des variables, le coût optimal, et les
 marges (slack).
 3. Apprendre à analyser les coefficients de dualité (prix ombrage ou shadow prices) pour étudier l'impact de changements dans les
 ressources disponibles.
 4. Étudier l'évolution de la solution optimale lorsque les coefficients de la fonction objectif ou les contraintes changent, pour développer
 une compréhension de la stabilité de la solution et des marges de faisabilité.
