TRUE CHAT — Version configurée pour votre projet Supabase

1. Ouvrez index.html dans un hébergement web compatible (HTTPS recommandé) ou dans votre environnement de test.
2. config.js contient déjà le Project URL et la clé Publishable que vous avez fournis.
3. N'ajoutez jamais une clé secret ou service_role dans les fichiers côté client.
4. Cette version fournit une interface de départ avec inscription/connexion Supabase et une base de messagerie. Elle n'est pas encore une application complète : la recherche de contacts, la création de conversations, les médias, les statuts, les appels et les notifications doivent encore être reliés et testés avec le schéma réel de la base.
5. Les règles RLS doivent protéger toutes les tables. Une clé Publishable est prévue pour le client, mais ne remplace pas les règles RLS.
6. Pour l'inscription, configurez les URLs autorisées dans Supabase Authentication > URL Configuration selon l'adresse où vous hébergez l'app. L'adresse localhost ne suffit pas pour un site en ligne.
7. Le téléchargement automatique directement vers la galerie iPhone/Android n'est pas garanti dans une simple page web; les navigateurs peuvent demander une action utilisateur. Pour un enregistrement fiable en galerie, une application native ou une intégration adaptée sera nécessaire.
