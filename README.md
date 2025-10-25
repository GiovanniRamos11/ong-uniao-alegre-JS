# ONG União Alegre - Projeto Web Dinâmico

## Descrição do Projeto
Esta é a terceira entrega do projeto da ONG União Alegre. O foco desta fase foi transformar a interface estática em uma aplicação web **dinâmica e interativa**, utilizando JavaScript avançado para manipulação do DOM, eventos e funcionalidades SPA (Single Page Application).  

O site mantém a apresentação da ONG, incluindo seções de **introdução, doações, voluntários, notícias e missão**, mas agora com elementos interativos e minimalistas.

---

## Alterações Realizadas
- **Bloco de Doações:**  
  - Compactado para versão mobile, ocupando menos espaço vertical.  
  - Itens dispostos em linha com rolagem horizontal no mobile, mantendo todos os conteúdos.  
  - Estilo minimalista, mantendo legibilidade e interação hover.  

- **Responsividade:**  
  - Ajustes de padding, fonte e margens para telas menores.  
  - Imagens e textos adaptados para visualização mobile.

- **JavaScript Implementado:**  
  - Looping contínuo das notícias usando `requestAnimationFrame`.  
  - Estrutura modular para futuros recursos SPA e manipulação dinâmica do DOM.  

- **Estrutura do Projeto:**  
  - Pastas organizadas em:  
    ```
    /css       -> Arquivos de estilo
    /images    -> Logos, fotos e ícones
    /js        -> Arquivos JavaScript
    /index.html
    /projetos.html
    /cadastro.html
    ```
  - Código HTML e CSS atualizado conforme critérios de interatividade e responsividade.

---

## Funcionalidades Obrigatórias Implementadas
- Sistema SPA básico (preparado para navegação interna via JavaScript).  
- Manipulação de templates JavaScript para renderização de conteúdos dinâmicos.  
- Verificação básica de consistência de dados em formulários (avisos ao usuário para preenchimento incorreto).  
- Itens do bloco de doações minimalistas e adaptáveis ao mobile.

---

## Como Executar
1. Clonar o repositório:
   ```bash
   git clone <link-do-repositório>
