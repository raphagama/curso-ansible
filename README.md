# Projeto de Curso de Ansible

Este repositório contém o **projeto desenvolvido** durante um curso de Ansible, focado em automação de infraestrutura e deployment de aplicações. O objetivo principal é demonstrar a aplicação prática do Ansible para provisionar e gerenciar ambientes complexos.

---

## Descrição do Projeto

O projeto visa simular um ambiente de aplicação de três camadas, provisionando máquinas virtuais e configurando-as para rodar:

* **Camada de Banco de Dados**: Utilizando MySQL.
* **Camada de Aplicação/Web**: Utilizando Apache e WordPress.

Através dos exemplos contidos neste repositório, você pode observar como automatizar diversas tarefas, desde a instalação de pacotes até a configuração de serviços e o deploy de aplicações.

---

## Tecnologias Utilizadas

* **Ansible**: Ferramenta de automação de TI.
* **MySQL**: Sistema de gerenciamento de banco de dados.
* **Apache**: Servidor web.
* **WordPress**: Plataforma de gerenciamento de conteúdo.

---

## O Que Você Pode Aprender (Analisando o Projeto)

Ao explorar este projeto, você poderá entender:

* Como automatizar a instalação e configuração de sistemas operacionais e serviços.
* A utilização de playbooks, roles e variáveis Ansible para criar automações reutilizáveis.
* O provisionamento de ambientes de desenvolvimento de forma consistente.
* A realização de deployments de aplicações de múltiplas camadas.
* A aplicação de boas práticas de Infrastructure as Code (IaC) com Ansible.

---

## Configuração e Instalação

Para configurar o ambiente e executar os playbooks, siga os passos abaixo:

1.  **Pré-requisitos**:
    * [Git](https://git-scm.com/) instalado.
    * [VirtualBox](https://www.virtualbox.org/wiki/Downloads) instalado.
    * [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) instalado.

2.  **Clonar o Repositório**:

    ```bash
    git clone [https://github.com/raphagama/curso-ansible.git](https://github.com/raphagama/curso-ansible.git)
    cd curso-ansible
    ```

3.  **Executar os Playbooks Ansible**:
    Após as VMs estarem prontas, você pode executar os playbooks Ansible para configurar os serviços e deployar a aplicação. Consulte os arquivos `.yml` dentro do repositório para entender a estrutura dos playbooks e como executá-los. Exemplo:

    ```bash
    ansible-playbook -i hosts provisioning.yml
    ```

---

## Uso

Os playbooks são organizados para configurar o ambiente e deployar o WordPress. Explore os diretórios `roles` e os arquivos `.yml` na raiz para entender as tarefas e como modificá-las para suas necessidades.

---

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias, correções de bugs ou novas funcionalidades.

---
