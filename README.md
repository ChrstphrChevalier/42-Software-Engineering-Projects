# <p align="center"> ![image](https://github.com/ChrstphrChevalier/42Cursus/assets/146819291/2a84ca36-fded-4fa0-86b8-b0e9675b8c8e) </p>

## <p align="center"> Tronc Commun 42 </p>

### Aperçu

Le tronc commun de l'école 42 est une formation intensive et complète qui couvre un large éventail de compétences en programmation, développement système, algorithmie et administration. Il vise à former des développeurs polyvalents et autonomes, capables de résoudre des problèmes complexes à travers l'utilisation de technologies modernes, notamment en **C**, **C++**, et dans des environnements **Unix/Linux**.

Les principaux objectifs sont l'acquisition de compétences solides en gestion de la mémoire, manipulation des structures de données, optimisation des algorithmes, ainsi que la maîtrise des systèmes embarqués et du développement réseau. La formation inclut également des notions de **programmation orientée objet (OOP)** avec **C++**, ainsi que des compétences en **développement web** (API REST, WebSocket, sécurité) et **DevOps** (Docker, CI/CD). Les étudiants sont également formés à la gestion de processus, à la synchronisation multithread, et à la configuration des réseaux et systèmes.

Ce tronc commun se distingue par son approche pratique, l'accent mis sur le travail en autonomie, et la **collaboration en peer-to-peer**, où les étudiants s'entraident, échangent des idées et résolvent des problèmes ensemble. Cette méthode permet de développer des compétences en communication et en travail d'équipe tout en offrant la liberté de résoudre des problèmes réels et d'optimiser les solutions en termes de performances et de sécurité.

---

### Compétences Acquises

#### Programmation C
- **Pointeurs** : Manipulation de pointeurs, gestion de la mémoire (malloc, free), gestion de buffers.
- **Allocation Dynamique** : Utilisation de `malloc` et `free` pour l'allocation et la gestion dynamique de la mémoire.
- **Gestion de Buffers** : Manipulation de buffers statiques et dynamiques, optimisation des opérations d'entrée/sortie.
- **Parsing et Conversion Numérique** : Conversion entre formats (décimal, hexadécimal), manipulation de chaînes et parsing d'arguments.
- **Structures de Données** : Utilisation de structures de données (tableaux dynamiques, piles, listes chaînées).
- **Optimisation** : Minisation des appels système, gestion mémoire sans fuites, optimisation des performances (benchmarking, minimisation des cycles).
- **Débogage** : Utilisation de **valgrind** et **gdb** pour détecter les **memory leaks**, les **segmentation faults**, et tester les **edge cases**.

#### Algorithmie
- **Tri et Recherche** : Algorithmes de tri (tri à bulles, tri rapide, etc.), recherche (binaire, linéaire).
- **Optimisation** : Optimisation des algorithmes en fonction de la complexité temporelle (O(n²), O(n log n)).
- **Algorithmes Gourmands** : Mise en œuvre de **greedy algorithms** pour optimiser les performances des solutions.
- **Bit Manipulation** : Conversion ASCII vers binaire, manipulation de bits pour l'optimisation.

#### Développement Systèmes
- **Systèmes Unix/Linux** : Maîtrise de la ligne de commande, gestion des **processus** (fork, execve), gestion des **signaux** (SIGINT, SIGQUIT).
- **Entrées/Sorties (I/O)** : Utilisation de `read`, descripteurs de fichiers, gestion multi-fd, optimisations des opérations I/O.
- **Gestion de Processus** : **Multitâche** et **multiprocessing**, gestion de l'exécution avec **waitpid**.
- **Systèmes Embarqués** : Programmation sur des systèmes à ressources limitées, gestion de la mémoire et du processeur.

#### Concurrence et Synchronisation
- **Threads et Synchronisation** : Utilisation de **pthread**, **mutex**, **sémaphores**, gestion du **parallélisme** et évitement des **deadlocks**.
- **Concurrence** : Gestion des ressources partagées, gestion des **race conditions** et optimisations pour des performances multithread.

#### Réseautage
- **Sockets TCP/UDP** : Programmation de **sockets**, gestion des connexions réseau, implémentation des protocoles **TCP/IP**, **IPv4**.
- **Multiplexing** : Gestion des connexions simultanées avec **select**, **poll**, **epoll**.
- **Protocoles Réseau** : Configuration et gestion des protocoles réseau, adressage **IP**, **routing**, interconnexion, optimisation des performances réseau.

#### Programmation C++
- **Programmation Orientée Objet (OOP)** : Concepts d'héritage, polymorphisme, **encapsulation**, **abstraction**.
- **STL** : Utilisation de **containers** (vector, map, list), **algorithmes** (sort, find), itérateurs.
- **Gestion Mémoire** : Allocation dynamique avec `new`, `delete`, utilisation de **smart pointers** et principes de **RAII**.
- **Templates et Métaprogrammation** : Utilisation des **templates** pour la programmation générique.

#### Développement Web
- **API REST** : Création et gestion d'API **RESTful** pour des applications distribuées.
- **WebSocket** : Mise en place de la communication en temps réel pour les notifications, chats et matchmaking.
- **Sécurité** : Gestion des **authentifications** (OAuth2, JWT, 2FA), protection **CSRF**, **CORS**, gestion des permissions et des rôles.
- **Backend** : Développement backend avec des technologies comme **Node.js**, **Express**, **NestJS**.
- **Frontend** : Développement frontend avec des technologies comme **React**, **TypeScript**, **TailwindCSS**.

#### Virtualisation et DevOps
- **Docker** : Création et gestion de **conteneurs**, gestion des **images**, utilisation de **docker-compose** pour l'orchestration.
- **CI/CD** : Automatisation du déploiement, gestion des builds, intégration continue, **scalabilité**.
- **Sécurité** : Gestion des **certificats TLS/SSL**, sécurité des environnements Docker et des applications.

#### Administration Système
- **Installation OS** : Configuration et installation d'OS, gestion des partitions, installation de logiciels via **apt**.
- **Gestion Réseau** : Configuration des **interfaces réseau**, **masques de sous-réseau**, **CIDR**, gestion des **routeurs**, **switches**, et **passerelles**.
- **Sécurité** : **UFW** pour la gestion des firewalls, configuration de **SSH sécurisé** avec clés RSA, gestion des **politiques de mots de passe**.

#### Débogage et Optimisation
- **Outils** : Utilisation de **valgrind**, **gdb**, analyse des **memory leaks**, des **segmentation faults**, et résolution des **edge cases**.
- **Logs et Performance** : Diagnostic via les logs système, suivi de la performance du code et analyse des goulets d'étranglement.

#### Conteneurisation & Orchestration
- **Docker** : Création d'images Docker, gestion des volumes, orchestration de services avec **docker-compose**, persistance des données.
- **Réseautage Docker** : Configuration des réseaux Docker, **mapping des ports**, interconnexion des conteneurs.

#### Tests et Validation
- **Tests Unitaires et d'Intégration** : Création de tests unitaires, tests d'intégration pour valider le bon fonctionnement du code.
- **Validation de Fonctionnalités** : Mise en place de tests pour valider les interactions entre services et composants du système.

---

### Pourquoi ce cursus est pertinent

Le tronc commun de l'école 42 est un tremplin idéal pour ma carrière, car il me permet de renforcer mes compétences en programmation, notamment en **C** et **C++**, et de maîtriser des environnements **Unix/Linux**, qui sont des compétences clés dans le domaine de l'IT. Ce cursus m’a offert l’opportunité de travailler sur des projets pratiques qui simulent des défis réels rencontrés en entreprise, me permettant ainsi de développer une approche pragmatique du développement logiciel, de l'optimisation des algorithmes, et de la gestion de la mémoire.

La formation m'a permis de compléter mes compétences en **Développement Web** (API REST, WebSocket, sécurité) et en **DevOps** (Docker, CI/CD), domaines essentiels pour rester compétitif sur le marché. Elle m'a aussi aidé à acquérir une expertise en **réseautage** et **administration système**, me donnant une vision globale des enjeux technologiques et des besoins actuels des entreprises.

Ce cursus est d’autant plus pertinent pour moi qu’il met l’accent sur l’apprentissage en **autonomie** et la **collaboration peer-to-peer**. Travailler avec d’autres développeurs et partager des idées m'a permis de développer des compétences en **communication** et en **travail d’équipe**, qui sont des atouts essentiels pour un environnement de travail agile. Grâce à cette approche, j'ai pu affiner ma capacité à résoudre des problèmes complexes tout en optimisant mes solutions en termes de **performance** et de **sécurité**, ce qui est essentiel dans le domaine du cloud et de la cybersécurité où je souhaite me spécialiser.

L’école 42 m’a offert un environnement unique pour me préparer à intégrer des entreprises de renom et m’a permis de développer une solide base technique, ainsi qu’une approche méthodique et indépendante de résolution de problèmes. C’est un réel tremplin pour réussir dans le secteur de l’informatique, avec un programme qui correspond parfaitement à mes ambitions professionnelles.
