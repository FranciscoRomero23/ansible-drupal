# ansible-drupal

Esta es una práctica para la asignatura de Administración de Sistemas Operativos, del grado superior en Administración de Sistemas Informáticos en Red.
El objetivo de la práctica es crear un escenario de manera automática utilizando la herramienta Ansible, donde tendremos instalado el cms Drupal.

### El escenario

El escenario que debemos crear consta de dos nodos:
* Nodo 1: Tendrá instalados PostgreSQL como base de datos y Bind9 como servidor DNS.
* Nodo 2: Tendrá instalados Apache2 como servidor web y el mod php.

Ambos nodos son creados mediante la herramienta Vagrant.

El cliente configurará como DNS primario el del nodo1, para acceder a un drupal totalmente configurado en drupal.example.com. 
