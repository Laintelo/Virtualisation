# Notions importantes sur la Virtualisation

Pour comprendre et utiliser efficacement la virtualisation, voici quelques notions importantes à connaître :

**1. Hyperviseur (ou Moniteur de Machines Virtuelles) :** C'est le logiciel responsable de la création, de la gestion et de l'exécution des machines virtuelles. Il existe deux types d'hyperviseurs : de type 1 (Bare Metal) qui s'exécute directement sur le matériel physique et de type 2 (Hosted) qui s'exécute comme une application sur un système d'exploitation hôte.

**2. Machine Virtuelle (VM) :** C'est une instance virtuelle d'un système d'exploitation qui fonctionne comme une machine indépendante sur une machine physique. Chaque VM a ses propres ressources dédiées et est isolée des autres machines virtuelles.

**3. Virtualisation d'OS :** C'est la virtualisation de plusieurs instances d'un système d'exploitation sur un même serveur physique. Chaque instance fonctionne comme une machine virtuelle avec ses ressources dédiées.

**4. Virtualisation d'Application :** C'est la virtualisation d'applications de manière isolée les unes des autres sur un même système d'exploitation.

**5. Virtualisation de Postes de Travail :** C'est la virtualisation d'environnements de bureau complets sur un serveur, permettant aux utilisateurs d'accéder à leur environnement de travail depuis n'importe quel appareil.

**6. Consolidation de Serveurs :** C'est le regroupement de plusieurs machines virtuelles sur un seul serveur physique pour optimiser l'utilisation des ressources matérielles et réduire les coûts d'exploitation.

**7. Sauvegardes et Récupérations :** Les machines virtuelles peuvent être sauvegardées et restaurées plus facilement, facilitant ainsi la gestion des sauvegardes.

**8. Virtualisation de Sessions :** C'est la virtualisation côté serveur où les données de l'utilisateur et les applications sont hébergées dans un datacenter. L'utilisateur accède à ses applications via un simple navigateur ou un client installé sur un poste de travail en ouvrant une session sur le serveur distant.

**9. Virtualisation par Isolation (ou Bulle Applicative) :** Les applications sont encapsulées dans des bulles virtuelles et s'exécutent sur le poste client dans un environnement totalement virtualisé.

**10. Avantages de la Virtualisation :** La virtualisation offre des avantages tels que l'utilisation optimale des ressources, la consolidation des serveurs, la facilité de gestion, l'isolation et la sécurité.

**11. Scénarios d'utilisation :** La virtualisation trouve des applications dans la consolidation de serveurs, le développement et les tests d'applications, la gestion des environnements de bureau, les sauvegardes et récupérations, etc.

**12. Hyperviseurs populaires :** Parmi les hyperviseurs les plus populaires, on trouve VMware vSphere, Microsoft Hyper-V, KVM (Kernel-based Virtual Machine), et Xen.
