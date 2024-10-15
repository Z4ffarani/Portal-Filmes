![banner](./assets/banner.png)

# PROJETO
Portal Filmes é uma plataforma fictícia que permite aos usuários explorarem filmes internacionais ou séries de televisão populares, filtrarem gêneros de filmes e organizarem seus conteúdos "para ver depois". Ele utiliza a **API (Application Programming Interface)** do **The Movie Database (TMDb)** para obter informações atualizadas sobre filmes e séries.

<br>    

# INSTRUÇÕES
Criar uma pasta no computador para ser o repositório local.

Abrir a pasta criada em uma **IDE (Integrated Development Environment)** de preferência.

No terminal da IDE, clonar o repositório com `git clone https://github.com/Z4ffarani/Portal-Filmes.git`.

No terminal da IDE, navegar até a pasta do projeto com `cd Portal-Filmes/portal-filmes`.

No terminal da IDE, instalar o pacote de módulos do Node.js com `npm install`, ou apenas `npm i`.

Iniciar o servidor de desenvolvimento com `npm run dev`.

Acessar o site no endereço http://localhost:5173.

<br>

# FUNÇÕES
- **Exibição de filmes e séries populares** | O programa faz requisições à API do TMDb para buscar listas de filmes e séries populares.
  
- **Pop-ups detalhados** | Ao clicar em um filme ou série na página `Home`, um pop-up aparece, exibindo detalhes, como trailer, elenco, avaliação e sinopse.

- **Busca avançada** | O usuário pode buscar por filmes e séries usando um campo de busca na página `Collection`.
  
- **Gêneros de filmes** | O programa permite que os usuários explorem filmes por gênero utilizando a navegação baseada em **URL (Uniform Resource Locator)** com `useParams`.

- **Armazenamento local** | Os usuários podem adicionar filmes e séries às listas `conteudoParaVer` ou `conteudoAssistido`, utilizando o `localStorage` para persistência de dados.

<br>

# OBSERVAÇÕES
- É necessária a instalação do **Node.js** para que o programa seja rodado.

- Não é possível realizar login ou cadastro pessoal na plataforma.

- O aplicativo faz uso da API do TMDb, que requer uma chave de API para funcionar. É preciso certificar-se de substituir a chave de API no código por uma própria chave.

- O catálogo de filmes e séries tende a mudar, pois o banco de dados da TMDb se atualiza periodicamente.

- A seção de filmes recomendados da página `Home` filtra-os por gênero mais predominante entre os marcados como assistidos pelo usuário na página `Collection`, sendo os resultados da seção estatisticamente favoráveis.

- O projeto utiliza `localStorage` para armazenar dados temporariamente. Isso significa que os dados são mantidos apenas enquanto o servidor local estiver funcionando, sendo perdidos ao encerrá-lo. Para um sistema mais robusto de login, recomenda-se o uso de um banco de dados e autenticação segura.

<br>

# TECNOLOGIAS
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev)
[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://styled-components.com)
[![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/download/source-code)
[![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/react-router-dom)
[![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

<br>

# AGRADECIMENTOS
- **[Caio Vinícius Gonçalves de Oliveira](https://github.com/caiooliveira-tech)**
- **[The Movie Database](https://www.themoviedb.org)**