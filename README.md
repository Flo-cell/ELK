# ELK

Playbook destiné au déploiement de la Stack ELK dans le cadre du projet d'étude Supervision du Master réeaux et télécommunication.

/!\ Selon votre IP vous devez modifier les fichiers :

   destfile: /etc/auditbeat/auditbeat.yml
   regexp: '#host: "localhost:5601"'
   line: "  host: 172.16.128.14:5601"
   
   destfile: /etc/kibana/kibana.yml
   regexp: '#server.host:'
   line: "server.host: 172.16.128.14"
   
   La fonctionalité sera ajoutée prochainement.
