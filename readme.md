# Atividade Ponderada - Semana 9
## Interação com Aws a partir do Terraform

### Ambiente

Para garantir a execução de todos os passos é necessário possuir a CLI da AWS e o Terraform instalados em sua máquina local.

Para averiguar se a instalação foi concluída corretamente, podemos utilizar comandos que verificam a versão das ferramentas.

![Terraform](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718582540/Captura_de_tela_2024-06-16_210205_e1k3nd.png)

![AWS](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718582656/aws_version_mli17l.png)

Além disso, é necessário configurar as credentials do LearnLab da AWS em sua máquina local.

![Credentials](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718584074/aws_configure_bilzkz.png)

### Terraform

Após criar o código de criação da instância EC2, podemos inicializar o terraform.

![TerraformInit](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718585875/terraform_init_nmskiw.png)

Após isso, executar o comando de plan, que exibe tudo o que o terraform planeja criar ou alterar a partir do código disponibilizado.

![TerraformPlan](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718585875/terraform_plan_ldhmey.png)

Com o plano de criação validado, podemos executar o apply para finalmente executar as ações na AWS.

![TerraformApply](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718585850/terraform_apply_vylm5f.png)

### Console AWS

Se todos os passos foram executados corretamente, podemos visualizar no console da AWS a instância EC2 sendo criada.

![AWSInstance](https://res.cloudinary.com/dmpfkxudq/image/upload/v1718585880/aws_ec2_console_v0elvh.png)