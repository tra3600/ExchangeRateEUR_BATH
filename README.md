# ExchangeRateEUR_BATH
programme en Python qui convertit les euros en bahts thaïlandais en utilisant des taux de change en temps réel

our créer un programme en Python qui convertit les euros en bahts thaïlandais en utilisant des taux de change en temps réel, nous pouvons utiliser une API de taux de change. Un exemple populaire est l'API de taux de change de Open Exchange Rates ou de ExchangeRate-API. Pour cet exemple, nous utiliserons l'API de ExchangeRate-API car elle offre des plans gratuits et des taux de change en temps réel.

Étapes à Suivre
S'inscrire à l'API : Obtenez une clé API en vous inscrivant sur ExchangeRate-API.
Installer les bibliothèques nécessaires : Nous utiliserons requests pour faire des requêtes HTTP.
Écrire le programme : Connecter l'API, récupérer le taux de change, et afficher le résultat.
Exemple de Code
Prérequis
Installer la bibliothèque requests :

pip install requests

Explications
Importation de la Bibliothèque requests :

Utilisée pour effectuer des requêtes HTTP à l'API de taux de change.
Fonction get_exchange_rate :

Prend en entrée la clé API, la devise de base (EUR), et la devise cible (THB).
Construit l'URL pour l'API ExchangeRate-API avec les paramètres fournis.
Envoie une requête GET à l'API et vérifie le statut de la réponse.
Si la réponse est correcte, extrait et retourne le taux de conversion.
En cas d'erreur, lève une exception.
Fonction main :

Définit la clé API (à remplacer par votre clé API personnelle), la devise de base, et la devise cible.
Appelle la fonction get_exchange_rate pour obtenir le taux de conversion.
Affiche le taux de conversion avec deux chiffres significatifs.
Gère les exceptions et affiche un message d'erreur en cas de problème.
Utilisation
Remplacez 'YOUR_API_KEY' par votre clé API obtenue après inscription sur ExchangeRate-API.
Exécutez le script Python.
Le programme affichera le taux de conversion en temps réel de l'euro vers le baht thaïlandais avec deux chiffres significatifs.
Ce programme est un exemple simple pour obtenir des taux de change en temps réel. Vous pouvez l'étendre en ajoutant des fonctionnalités supplémentaires, comme la conversion d'un montant spécifique ou la gestion de plusieurs devises.
