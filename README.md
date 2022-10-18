# Aluvery

![thumb-jetpack-compose-form-e-gereciamento-de-estado](https://user-images.githubusercontent.com/8989346/196530246-646ad6ce-4a5b-4cef-a28d-e92e9ea6b3f4.png)

App de entrega de comidas e bebidas em geral.

## 🔨 Funcionalidades do projeto

O Aluvery apresenta um catálogo de produtos variados como comidas, doces, bebidas etc. Também, ele oferece as seguintes funcionalidades:

- Busca de produtos a partir do nome ou descrição
- Formulário de cadastro de novos produtos
- Apresentação de novos produtos na primeira seção do catálogo

![Amostra do App em execução](https://user-images.githubusercontent.com/8989346/196525814-e2d68b0a-6185-4d7a-823d-7b71afebdc69.gif)

## 🎯 Desafios

- State Holder da tela de formulário -> [Resultado do desafio](https://github.com/alura-cursos/jetpack-compose-gerenciamento-de-estados/commit/88078874eba51a039d53ac33bb7597356ead2c27)

## ✔️ Técnicas e tecnologias utilizadas

Além das técnicas utilizadas na [versão anterior do projeto]([url](https://github.com/alura-cursos/jetpack-compose-lazy-layouts-e-estados)), também usamos:

- `Scaffold`: para estruturar componentes do Material Design
- `FloatingActionButton`: para acessar o formulário e o 
- `Slot`: para reutilizar composables base do App
- `Button`: para salvar produtos a partir do formulário
- `Melhoria de experiência do formulário`: aplicação de scroll e preview de imagem ao carregar uma URL válida
- `Melhoria dos teclados nos campos de texto`: modificação nos tipos de teclados, ações de ime, capitalização e filtro nos valores inseridos
- `DAO`: classe responsável em salvar e buscar produtos salvos
- `Gerenciamento de estados com State Holder`: criação de um objeto responsável em manter os estados e eventos do composable de tela
- `Boas práticas no State Holder`: elevação de estados e eventos, como também, o uso do `remember()` para reagir a todos os estados necessários
- `Implementação de composables Stateful e Stateless`: implementação de duas versões do mesmo composable para facilitar a reutilização (Stateful) para flexibilizar a personalização (Stateless)

## 📁 Acesso ao projeto

Você pode [acessar o código fonte do projeto](https://github.com/alura-cursos/jetpack-compose-gerenciamento-de-estados/tree/aula-6) ou [baixá-lo](https://github.com/alura-cursos/jetpack-compose-gerenciamento-de-estados/archive/refs/heads/aula-6.zip).

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Android Studio. Para isso, na tela de launcher clique em:

Open an Existing Project (ou alguma opção similar)
Procure o local onde o projeto está e o selecione (Caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo)
Por fim clique em OK
O Android Studio deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆

<!-- ## 📚 Mais informações do curso

**Faça um CTA (_call to action_) para o curso do projeto**
