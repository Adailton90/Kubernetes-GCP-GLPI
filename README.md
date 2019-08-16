# Kubernetes-GCP-GLPI
 
Neste projeto criei um Cluster Kubernetes na Google Cloud Platforme(GCP), no serviço do Google Kubernetes Engine(GKE).
Subi para o repositório Registry do GCP a imagem do GLPI baseada na mesma do repositório https://github.com/Adailton90/Docker-GLPI-Jenkins para poder usar neste projeto.

O arquivo "glpi_deployment.yaml" é usado para criar o Deployment do Kubernetes que é responsavel por criar as PODS baseado na imagem docker no repositório Registry do GCP.

O arquivo "glpi_service.yaml" é usado para criar o Service do Kubernetes que é reponsavel por fazer o balanceamento de carga das requisições feitas para as PODS GLPI criadas pelo arquivo "glpi_deployment.yaml".
