<h1>Authentification_RSA</h1>
<h2>Objectif</h2>
Créer un outil de gestion de clés asymétriques RSA 4096, un outil d'authentification par fichier, et un outil serveur d'identification par clé asymétrique.<br/>
Le client créer une paire de clés RSA  4096 qu'il associe à un nom de domaine ou une phrase/mot.<br/>
Lors d'une inscription sur un site, l'utilisateur fournit sa clé publique de déchiffrement.<br/>
Le site/serveur stock, la clé et la phrase de manière cryptées.<br/>
Le client s'authentifie en envoyant sa clé publique et le nom de domaine ou une phrase/mot crypté avec la clé privée.<br/>
Le serveur décrypte et compare les informations avec ce qu'il a stocké et authentifie le client.<br/>
Le seul moyen de casser le système est de trouver la clé privée (unique pour chaque utilisateur et chaque site).<br/>
<h2>Fonctionnalités</h2>
<ul>
  <li>Un logiciel PC pour la gestion des clés client</li>
  <li>Une application pour la gestion des clés client</li>
  <li>Une API/Lib pour la gestion du stockage et d'identification pour le serveur</li>
</ul>
