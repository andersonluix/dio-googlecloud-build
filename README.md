# dio-googlecloud-build
Repositório projeto bootcamp dio - Usando terraform básico com cloudbuild

Passos executados na tarefa:
1. Incluido  o comando terraform init no arquivo cloudbuild.yaml
2. Alterado no arquivo main.tf: nome do bucket, nome do projeto, Nome da instacia para cloudbbuildterraform.
3. Dada permissões para o usuario do cloudbuild no IAM.
4. Rodar o comando: gcloud builds submit --config=cloudbuild.yaml
