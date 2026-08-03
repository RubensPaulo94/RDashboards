# RDashboards- Plataforma para centralização e controle de dashboards

## Sobre o Projeto

O RDashboards é uma versão demonstrativa de uma solução de gestão de dashboards Power BI criada para apresentação em portfólio.

Este repositório contém a documentação do projeto, arquitetura da solução e demonstrações visuais.

**O código-fonte não está disponível publicamente, pois o projeto foi baseado em uma solução desenvolvida em contexto corporativo.**

---

## Problema

- Dashboards dispersos em diferentes locais  
- Falta de controle de acesso estruturado  
- Dificuldade na gestão de permissões  
- Ausência de monitoramento de uso  

---

## Solução

A aplicação permite:

- Centralizar dashboards em um único ambiente  
- Controlar acesso por usuário com base em papéis (RBAC)  
- Registrar logs de acesso para auditoria  
- Gerenciar permissões de forma centralizada  
- Coletar feedback dos usuários  

---

## Tecnologias Utilizadas
- React
- TypeScript
- PostgreSQL
- Power BI Embedded  

> Versão demonstrativa hospedada no Lovable Cloud, baseada na arquitetura original com Supabase.
---

## Arquitetura

Este repositório representa uma versão demonstrativa do projeto.

- A versão original foi desenvolvida utilizando Supabase como backend (Auth, Database e RLS)
- Esta versão utiliza a infraestrutura do Lovable Cloud para demonstração pública
- A lógica de controle de acesso e modelagem de dados foi mantida conceitualmente


---

## Segurança

O sistema foi projetado com foco em controle de acesso e proteção de dados:

- **RBAC (Role-Based Access Control)** para gerenciamento de permissões por perfil  
- **RLS (Row Level Security)** para restrição de acesso aos dados no banco  
- Autenticação de usuários implementada na arquitetura original com Supabase  

> A versão demonstrativa mantém a lógica de controle de acesso adaptada ao ambiente do Lovable Cloud.

---

## Screenshots

### Tela de Login
- Tela inicial com a autenticação obrigatória dos usuários
![login](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/1-Tela%20Login.png)


### Tela Principal
- Apresenta os Dashboards que estão habilitados para visualização 
![detalhes1](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/2-Detalhes%20Dashboard.png)
![detalhes2](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/2.1-Detalhes%20Dashboard.png)

### Favoritos
- Todos os Dashboards que você sinalizou como favoritos aparecerão aqui
![favoritos](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/3-%20Favoritos.png)

### Gerenciamento de Usuários
- Gerenciamento de acesso e permissões definidas para cada usuário
![Usuarios](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/4-Usuarios.png)


### Gerenciamento dos Dashboards
- Gerenciamento dos Dashboards como links e descrições de cada um deles
![gerenciamentodashs](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/5-%20Gerenciamento%20de%20Dashboards.png)


### Cargos
- Lista de cargos que estão disponíveis
![listacargos](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/6-%20Cargos.png)


### Solicitações de Acesso
- Aqui o Administrador pode conceder ou negar a visualização a um dashboard especifico
![solicitacoesacesso](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/7-Solicita%C3%A7%C3%B5es%20de%20Acesso.png)


### Logs de Acesso
- Registra todos os acessos e permite o acompanhamento de quem está acessando a plataforma
![logsacesso](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/8-Logs%20de%20Acesso.png)


### Sobre
- Apresentação do que é a plataforma e seu objetivo
![sobre](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/9-%20Sobre.png)

### Meu Perfil
- Nesta seção o usuário pode alterar seu nome, senha e escolher entre o tema claro ou escuro
![meuperfil](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/10-%20Meu%20Perfil.png)


### Visão do Usuário
- Como o próprio nome diz é a visão de quem está cadastrado no sistema com o perfil "Usuário".
![visaousuario](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/11-%20Vis%C3%A3o%20Usu%C3%A1rio.png)
![visaousuario2](https://github.com/RubensPaulo94/RDashboards/blob/848e96a0e7a38610470d79931d74c6f8b2e5c772/imagens/12-%20Vis%C3%A3o%20Usu%C3%A1rio%20(Solicitar%20Acesso).png)

---

## Acesso

- Aplicação: [[Rdashboards] ](https://rdashboards.lovable.app/login) 
- Portfólio: [[Portfólio]  ](https://rubenspaulo-portfolio.lovable.app)

> Obs: É necessário criar um usuário para acessar a plataforma.

---

## Resultados

- Centralização dos dashboards  
- Redução da gestão manual de acessos  
- Controle granular de permissões  
- Monitoramento de utilização  
- Melhor governança dos dados  

---

## Aprendizados

- Modelagem de dados com PostgreSQL  
- Implementação de autenticação e autorização  
- Uso de RLS para segurança  
- Integração com Power BI Embedded  
- Estruturação de aplicação fullstack  

---

## Autor

Desenvolvido por **Rubens Paulo**
