# webapp-ansible-apache
L’automatisation est devenue un enjeu majeur au sein des entreprises afin d’être réactif et beaucoup plus proactif. L’ensemble des tâches qui étaient réalisées manuellement au sein du Système d’exploitation (Installation des systèmes d’exploitation, patching, mise à jour, installation des applications et gestion de leurs cycles de vie) ce qui était fait manuellement est désormais fait de façon automatique.

Commandes AD-HOC : nous allons voir déjà comment installer ANSIBLE et comment utiliser les commandes AD-HOC qui nous permettent de tester notre code ou d’expérimenter des modules particuliers.

Découverte du YAML : on va voir comment templétiser nos déploiements via une suite de commandes écrites dans un fichier YAML qu’on appellera un playbook.

Inventaire ANSIBLE : qui va nous permettre globalement de gérer et de cartographier notre infrastructure (voici les serveurs de préprods, voici les serveurs de base de données, de production et de frontend et ainsi grâce à cette cartographie, grâce à cet inventaire là on pourra donc décider ou est-ce qu’on va lancer tel ou tel playbook).

Playbook : on va matérialiser les différentes actions faites dans l’inventaire ANSIBLE.

Templating & Loop, condition : qui sont quelques notions avancées de Ansible plus précisément dans l’écriture de nos playbooks. Avec la notion de templating pour pouvoir variabiliser les fichiers de configuration, Loop pour boucler sur une variable et enfin la notion de Condition pour apporter beaucoup plus de dynamisme à nos playbooks.

