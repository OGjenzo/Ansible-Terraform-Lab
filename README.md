# Ansible-Terraform-Lab

# Ansible-Terraform-Lab

ce projet a pour but de maitriser quelque aspect de l'infraAsCode.
le but est de travailler avec les outils Terraform et Ansible, il yaura deux partie dans ce projet, une pour chaque outils

pour resumé l'objectif est de créer une mini infra sur azure pour ensuite y appliquer des playbook ansible


## Terraform

l'idée est de profiter de mon abonement azure Etudiant lol ( 100 euro c'est largement sufisant :) )

j'ai pensé a créer plusieur VM sur azure dans l'idée de faire apres le partage des clées pour créer un reseau de VM linux liée par un reseau


## Avancement 

dans l'etat ( 24 janvier 2023 ) :

le fichier main.tf permet de creer 3 Azure VM liée en reseau (la piece jointe resume la mini infra )



+-------------+     +-------------+     +-------------+
|   VM 1      |---->|   Subnet    |---->|   VM 2      |
+-------------+     +-------------+     +-------------+
                         |
                         |
                         |
                         V
                 +-------------+
                 |   VM 3      |
                 +-------------+



- a faire :
    generation de clé ssh
    affectation de @ip public a chaque vm
    

une fois les taches faite , on commencera la deuxieme partie ( Ansible ) 

## Ansible

Stay tuned
