Role: Cleanup
=============

Script automatique de nettoyage de l'ancien utilisateur principal de la machine et de son dossier home. Utilisateur dont Ansible se sert pour se connecter.
Lancé automatiquement par le crontab au redemarrage.
Le crontab s'efface tout seul au redémarrage.

Requirements
------------

Installation de cron.

Role Variables
--------------

<pre><code>- user
- user_to_delete
</code></pre>

Dependencies
------------

Ce role se télécharge automatiquement à partir du requirements.yml


Author Information
------------------

Starfly Env Team.
