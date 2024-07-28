### Para provisionar recursos com Terraform:
1. Navegue até o diretório `Terraform`

2. Instale o aplicativo `terraform`

3. Instale o aplicativo `aws-cli`. Veja esse link: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

4. Autentique na AWS com o comando:

<code>aws configure</code>

5. Antes de provisionar os recursos crie o backend para usar como *backend* e a tabela no Dynamodb.

6. Edite os arquivos *terraform.tfvars* e *variables.tf* com as informações da sua infraestrutura.

7. Provisione os recursos com os comandos:

Provisione os recursos com o comando:

<code>terraform init></code>

<code>terraform plan></code>

<code>terraform apply></code>


3. Copie a aplicação para o servidor usando o comando `scp`, exemplo:
