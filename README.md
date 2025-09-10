# Suíte de Testes - Login de Usuário (TestRail)

## Descrição
Projeto prático desenvolvido como parte da minha transição para a área de Quality Assurance (QA).  
O objetivo foi simular a criação e execução de **casos de teste funcionais e negativos** no **TestRail**, focados na funcionalidade de **Login de Usuário** no site **https://trello.com/home**.

## Funcionalidades testadas
- Login com credenciais válidas
- Login com senha incorreta
- Login com campos obrigatórios em branco

## Casos de Teste

### Caso de Teste 1 – Login com credenciais válidas
- **Pré-condição**: Usuário cadastrado no sistema
- **Passos**:
  1. Acessar a página de login
  2. Inserir e-mail válido
  3. Inserir senha válida
  4. Clicar em "Entrar"
- **Resultado Esperado**: Usuário autenticado e redirecionado ao dashboard.

### Caso de Teste 2 – Login com senha inválida
- **Pré-condição**: Usuário cadastrado
- **Passos**:
  1. Acessar a página de login
  2. Inserir e-mail válido
  3. Inserir senha incorreta
  4. Clicar em "Entrar"
- **Resultado Esperado**: Sistema exibe mensagem "Endereço de e-mail e/ou senha incorreta".

### Caso de Teste 3 – Login com campos em branco
- **Pré-condição**: Navegador aberto na tela de login
- **Passos**:
  1. Acessar a página de login
  2. Deixar campos de e-mail e senha vazios
  3. Clicar em "Entrar"
- **Resultado Esperado**: Sistema exibe mensagem "Preencha todos os campos obrigatórios".

## Ferramentas utilizadas
- TestRail (gestão de casos de teste)
- GitHub (portfólio)
- Markdown (documentação)

## Evidências
![Tela de Feature no TestRail](imagens/feature-login.png)  
![Lista de Test Cases](imagens/test-cases.png)  
![Execução de Test Run](imagens/test-run.png)

## Resultados
Todos os cenários foram executados com sucesso.  
- Cenários positivos aprovados (Passed)  
- Cenários negativos validados (mensagens corretas exibidas)
