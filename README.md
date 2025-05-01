# DiscoveryServer
DiscoveryServer constitue une brique essentielle de l’architecture microservices, combinant un serveur de registre de services (Eureka Server) avec une passerelle API (Spring Cloud Gateway) configurée pour le routage dynamique. 

Ce composant facilite l'enregistrement automatique des microservices et la découverte dynamique des instances disponibles. Il centralise les points d’entrée du système, assurant ainsi un routage intelligent, une meilleure résilience, et une gestion efficace du trafic au sein d’une architecture RESTful distribuée.

✅ Fonctionnalités principales
Enregistrement et découverte de services via Eureka Server
Routage dynamique des requêtes HTTP avec Spring Cloud Gateway
Adaptation automatique aux changements du paysage de services (scaling, défaillances, etc.)
Centralisation du trafic pour le monitoring, la sécurité et la gouvernance
Base extensible pour l’intégration de mécanismes avancés : filtrage, résilience, authentification, etc.

🛠️ Technologies et frameworks
Java 17+
Spring Boot
Spring Cloud Netflix Eureka Server
Spring Cloud Gateway
Maven
