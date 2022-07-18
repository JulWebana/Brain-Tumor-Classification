# Classification-des-tumeurs-c-r-brales.
Le Deep Learning (sous-domaine du Machine Learning) a gagné en importance ces dernières années dans presque tous les domaines où la prise de décision est impliquée, notamment l'économie, les soins de santé, le marketing et les ventes. Dans le domaine de la santé, le Machine Learning et le Deep Learning ont donné des résultats prometteurs dans divers domaines, notamment le diagnostic des maladies par imagerie médicale, les robots chirurgicaux et l'amélioration des performances des hôpitaux.  
L'une des applications du Deep Learning permet de détecter les tumeurs cérébrales à partir d'images IRM. Dans ce projet, nous allons  construire un classificateur qui permettra de détecter les tumeurs cérébrales (si elles existent) à partir d’images IRM. Il est maintenant évident qu'il s'agit d'un problème de classification binaire. Des exemples de tels problèmes de classification binaire sont le spam ou le non-spam, la fraude par carte de crédit (fraude ou non fraude), etc.  

Les images sont réparties en deux dossiers, oui et non, contenant chacun des images avec et sans tumeur cérébrale respectivement. Il y a un total de 253 images.   
Notre approche pour construire le classificateur sera discuté en 03 étapes :  
  * Dans un 1er temps, nous allons effectuer une analyse exploratoire des données.  
  * Ensuite nous allons construire un modèle CNN. 
  * Et enfin nous allons entraîner et évaluer notre modèle sur l'ensemble des données.
