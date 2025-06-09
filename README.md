# Documentação do Projeto - Site Institucional Stratosfera

## 1. Documentação Inicial do Projeto

### 1.1 Documento de Visão do Projeto

- **Objetivo:** Desenvolver um site institucional moderno e informativo para a empresa Stratosfera.
- **Stakeholders:** Equipe de desenvolvimento, equipe de marketing da Stratosfera, diretoria da empresa, usuários e clientes em potencial.
- **Requisitos de negócio:**
  - Apresentar a empresa, seus serviços e equipe.
  - Divulgar conteúdos via blog.
  - Permitir o envio de formulários de contato e currículos.
  - Disponibilizar área de reservas/consultorias.
- **Cronograma macro:**
  - Planejamento e design: 1 semana
  - Desenvolvimento: 2 semanas
  - Testes e ajustes: 1 semana
- **Orçamento:** Projeto interno, sem custos externos adicionais.

### 1.2 Análise de Requisitos

- **Requisitos funcionais:**
  - Páginas HTML separadas para cada seção (Home, Sobre, Serviços, Blog, Contato, Trabalhe Conosco, Reserva)
  - Formulário de contato funcional
  - Formulário de envio de currículo
  - Página de blog com visual atraente
  - Página de galeria e clientes
- **Requisitos não-funcionais:**
  - Compatível com desktop e dispositivos móveis (responsivo)
  - Carregamento rápido
  - Fácil navegação (UX)
  - Estrutura acessível e clara

## 2. Documentação Técnica

### 2.1 Arquitetura do Sistema

- **Diagrama de arquitetura:** Estrutura baseada em HTML + CSS + JS estáticos.
- **Tecnologias utilizadas:**
  - Frontend: HTML5, CSS3, JavaScript puro
  - Backend: Não aplicável (site estático)
  - Hospedagem: GitHub Pages

### 2.2 Estrutura de Pastas

- `index.html`
- `sobre.html`, `servicos.html`, `contato.html`, `trabalhe.html`, `reserva.html`, `blog.html`
- `style.css`, `script.js`
- `/imagens`: pasta com recursos visuais

## 3. Documentação de Interface

### 3.1 Design System

- **Guia de estilo:**
  - Cores: Azul escuro, branco e tons de cinza
  - Tipografia: Sans-serif moderna
  - Componentes: Cards, botões arredondados, seções com ícones
- **Responsividade:**
  - Adaptado via media queries CSS

### 3.2 Wireframes e Protótipos

- Wireframes simples no papel/base Figma (não digitalizados)
- Estrutura comum para todas as páginas com cabeçalho e rodapé fixos

## 4. Documentação de Desenvolvimento

### 4.1 Ambiente de Desenvolvimento

- **Configuração do ambiente:**
  - Navegador moderno (Chrome/Firefox)
  - Git + GitHub
- **Estrutura de pastas:** HTML separados, CSS centralizado, JS único
- **Padrões de código:** Indentação consistente, classes CSS com nomes claros

### 4.2 Guia de Instalação

- **Pré-requisitos:**
  - Git instalado
  - Acesso ao GitHub
- **Passo a passo:**
  1. Clonar o repositório do GitHub
  2. Abrir os arquivos `.html` no navegador

## 5. Documentação de Testes

### 5.1 Plano de Testes

- **Estratégia:**
  - Testes manuais em diversos navegadores
  - Verificação da responsividade

### 5.2 Casos de Teste

- Links internos funcionam
- Formulários submetem corretamente (simulados)
- Páginas carregam sem erro

## 6. Documentação de Deploy

### 6.1 Ambientes

- Produção: GitHub Pages

### 6.2 Processo de Deploy

- Git commit + push para o repositório `stratosfera-site`
- GitHub Pages ativado no branch `main` ou `master`

## 7. Documentação do Usuário

### 7.1 Manual do Administrador

- Editar conteúdo via edição direta nos arquivos HTML
- Atualizar imagens na pasta `/imagens`

### 7.2 Manual do Usuário Final

- Navegar pelas páginas via menu
- Usar formulários para contato ou envio de currículo

## 8. Documentação de Manutenção

### 8.1 Procedimentos Operacionais

- Backup periódico do repositório via Git
- Atualizações com novo commit/push no GitHub

### 8.2 Documentação de Bugs e Melhorias

- Utilizar Issues no GitHub para rastrear bugs e sugestões

## 9. Checklist de Entrega

### 9.1 Documentos Obrigatórios

- [x] Documento de visão do projeto  
- [x] Especificação de requisitos  
- [x] Arquitetura do sistema  
- [ ] Modelagem de banco de dados (não aplicável)  
- [ ] Documentação da API (não aplicável)  
- [x] Guia de instalação  
- [x] Manual do usuário  
- [x] Plano de testes  
- [x] Documentação de deploy  

### 9.2 Validações Finais

- [x] Revisão técnica da documentação  
- [x] Aprovação dos stakeholders  
- [x] Testes dos procedimentos  
- [x] Backup da documentação  

## 10. Ferramentas Recomendadas

- **Documentação:** Notion, Google Docs  
- **Versionamento:** Git + GitHub  
- **Design:** Figma (opcional para futuras versões)  

---

### Observações Finais

- Documentação versionada junto ao código  
- Atualizações futuras devem seguir este modelo  
