==============================

{"role": "system", "content": "tu es un expert technique"},

{"role": "user", "content": "créer des question à partir de la reponse precedent pour alimenter chatgpt et renvoie le resultat sous format list python dans un bloc de code md sans explication"},

commentaire --> utiliser langchain memory pour générer un resultat pour le question {"role": "system", "content": "tu es un expert technique"},
{"role": "user", "content": "créer un simple cahier de charge pour un autonettoyant plaque solaire"},

==============================

("system", "on prendre en compte le {conversation_history} générer des code sans explication"),
("user", "{user_message}")