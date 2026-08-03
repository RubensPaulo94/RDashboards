# RDashboards- Plataforma para centralização e controle de dashboards

## Sobre o Projeto

Plataforma web desenvolvida para centralizar e gerenciar o acesso a dashboards Power BI, com autenticação de usuários, controle de permissões e monitoramento de utilização.

O objetivo é melhorar a governança, segurança e organização de ambientes com múltiplos dashboards.

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

### Tela Login
![login](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/1-%20Tela%20Login.png)


### Detalhes do Dashboard
![detalhes1](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/2-%20Detalhes%20Dashboard.png)
![detalhes2](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/2.1-%20Detalhes%20Dashboard.png)

### Favoritos
![favoritos](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/3-%20Favoritos.png)

### Usuários
![Usuarios](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/4-%20Usuarios.png)


### Gerenciamento dos Dashboards
![gerenciamentodashs](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/5-%20Gerenciamento%20de%20Dashboards.png)


### Cargos
![listacargos](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/6-%20Cargos.png)


### Solicitações de Acesso
![solicitacoesacesso](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/7-%20Solicita%C3%A7%C3%B5es%20de%20Acesso.png)


### Logs de Acesso
![logsacesso](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/8-%20Logs%20de%20Acesso.png)


### Sobre
![sobre](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/9-%20Sobre.png)

### Meu Perfil
![meuperfil](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/10-%20Meu%20Perfil.png)


### Visão do Usuário
![visaousuario](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/11-%20Vis%C3%A3o%20Usu%C3%A1rio.png)
![visaousuario2](https://github.com/RubensPaulo94/rdashboards-7239b95f/blob/35b48d4677fd3236da75cfec458187cbde79bd47/Imagens/12-%20Vis%C3%A3o%20Usu%C3%A1rio%20(Solicitar%20Acesso).png)



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

## Observação

Este projeto é uma versão demonstrativa desenvolvida para portfólio.

A implementação pública foi criada com base em conceitos e aprendizados obtidos durante o desenvolvimento de uma solução corporativa, sem exposição de informações, dados ou códigos proprietários.

---

## Autor

Desenvolvido por **Rubens Paulo**
