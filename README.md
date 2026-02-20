# Gerador-de-Curriculos-Profissional
Gerador de Currículos Profissional

Uma aplicação web estática, limpa e responsiva para criação de currículos profissionais em formato A4. O usuário preenche seus dados e, com um clique, a aplicação formata tudo em um layout moderno pronto para ser salvo em PDF.

Funcionalidades

100% Client-Side: Toda a lógica roda no navegador do usuário. Nenhum dado pessoal ou currículo é salvo em servidores, garantindo total privacidade.

Upload de Foto de Perfil: Permite adicionar foto (com pré-visualização) que se integra perfeitamente ao layout do currículo.

Campos Dinâmicos: Adicione múltiplas experiências profissionais e cursos complementares conforme a necessidade.

Lógica Inteligente: O formulário se adapta com base no Grau Acadêmico escolhido (ex: Ensino Médio exige endereço do colégio, Graduação exige o nome do curso e período).

Impressão Otimizada (PDF): Utiliza CSS @media print para remover cabeçalhos nativos do navegador, botões da interface e formatar o documento com margens perfeitas para exportação em PDF.

Como usar (Localmente)

Por ser um projeto puramente estático (Vanilla HTML/JS/CSS), não há necessidade de instalar dependências complexas (como Node.js ou NPM).

Faça o clone deste repositório:

git clone [https://github.com/thisisnoctra/Gerador-de-Curriculos-Profissional.git](https://github.com/thisisnoctra/Gerador-de-Curriculos-Profissional.git)


Abra a pasta do projeto.

Dê um duplo clique no arquivo index.html para abri-lo no seu navegador padrão.

Preencha os dados e clique em Gerar Currículo.

Na tela de pré-visualização, clique em Baixar PDF / Imprimir e salve como PDF usando a caixa de diálogo de impressão do navegador.

Tecnologias Utilizadas

HTML5: Estruturação semântica do projeto.

Tailwind CSS (via CDN): Estilização rápida, moderna e totalmente responsiva.

Vanilla JavaScript: Lógica de manipulação do DOM, controle de estado do formulário e manipulação da imagem de perfil (URL.createObjectURL).

Phosphor Icons (via CDN): Biblioteca de ícones leves e consistentes.

Como Hospedar Gratuitamente

Você pode colocar este gerador no ar de graça e em poucos minutos usando o GitHub Pages:

Suba este repositório para o seu GitHub.

Vá na aba Settings (Configurações) do seu repositório.

No menu lateral, clique em Pages.

Em Source, selecione a branch main (ou master) e clique em Save.

Em instantes, seu gerador estará online e acessível para qualquer pessoa!

Autoria e Créditos

Projeto criado e desenhado por Noctra - Instagram: @thisisnoctra

Fonte técnica: A captura e exibição de imagens diretamente do computador do usuário, sem a necessidade de enviar para um servidor em nuvem (mantendo a privacidade e o funcionamento no cliente), foi feita nativamente pelo navegador através da API da Web.
