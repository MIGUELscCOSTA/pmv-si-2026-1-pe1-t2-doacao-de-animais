
# Projeto de Interface

Visão geral da interação do usuário pelas telas do sistema e protótipo interativo das telas com as funcionalidades que fazem parte do sistema (wireframes).

 Apresente as principais interfaces da plataforma. Discuta como ela foi elaborada de forma a atender os requisitos funcionais, não funcionais e histórias de usuário abordados nas <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a>.

## User Flow

### 1. Fluxo de Adoção de Pet (Busca Direta)
Este fluxo representa o usuário que entra na plataforma para procurar e adotar um animal específico.
•	Página Inicial (Home): O usuário utiliza a barra de busca (por nome, raça, cidade ou estado) ou clica no botão "Ver pets disponíveis".

•	Página de Pets Disponíveis (/pets-disponiveis): O usuário navega pela grade de animais. Ele pode clicar no botão "Adote" para ir direto à adoção ou no botão "i" para ver mais detalhes.

•	Página de Detalhes do Pet (/paginas-de-detalhes-dos-pets): O usuário analisa as informações específicas (idade, peso, status de saúde, personalidade)

•	Ação Final: O usuário clica no botão "Quero Adotar o animal!" para iniciar o processo de adoção.
### 2. Fluxo de Descoberta pelo Quiz (Match Perfeito)
Este fluxo é para usuários que não sabem qual pet escolher e buscam uma recomendação baseada no seu estilo de vida.
•	Menu de Navegação (/menu-e-filtros): O usuário abre o menu e seleciona a opção "Fazer quiz"

•	Página do Quiz (/quiz): O usuário responde a três perguntas básicas: onde mora, quantas pessoas moram com ele e seu nível de atividade. Em seguida, clica em "Enviar".

•	Resultado do Quiz (/resultado-do-quiz): A plataforma exibe o "match" ideal com uma breve descrição de por que aquele perfil de animal combina com o usuário.

•	Ação Final: O usuário clica em "Adote agora!" para ser direcionado aos pets daquele perfil.
### 3. Fluxo de Doação
Focado em usuários que desejam apoiar a causa financeiramente.

•	Menu de Navegação: O usuário seleciona a opção "Doar".

•	Página de Doação (/DOAÇÃO): O usuário visualiza o impacto da doação, escolhe ou digita o valor desejado no campo correspondente.

•	Ação Final: Clica no botão "Doar agora!". (A página também oferece opções secundárias como "Doe itens", "Seja voluntário" ou "Compartilhe").

### 4. Fluxo de Autenticação (Cadastro e Login)
Para usuários comuns ou ONGs que precisam acessar suas contas.

•	Menu de Navegação: O usuário clica no bloco superior "Entre ou cadastre-se".

•	Página de Login (/entrar-no-seu-cadastro): Se já tiver conta, preenche e-mail e senha, e clica em "Entrar". Se for novo, clica no link "Cadastre-se gratuitamente".

•	Página de Cadastro (/cadastrar-na-pagina): O usuário preenche Nome completo, E-mail, Telefone e Senha.

•	Ação Final: Clica no botão "Criar conta" para acessar a plataforma logado.

### 5. Fluxo da ONG (Cadastro da Instituição e Gestão de Animais)
Este é o fluxo exclusivo para as organizações parceiras cadastrarem seus abrigos e gerenciarem os animais para adoção.
•	Página de Parceria (/DOAÇÃO-3): A ONG acessa a página informativa sobre parcerias e clica em "Cadastrar minha ONG's".

•	Formulário de Cadastro de ONG (/DOAÇÃO-4): O responsável preenche os dados da instituição (CNPJ, nome, responsável, localização, envio de documentação) e clica em "Enviar cadastro".

•	Painel de Controle da ONG (/DOAÇÃO-7): Após aprovação/login, a ONG acessa a área "Meus Anúncios". Aqui ela visualiza métricas (Animais Cadastrados, Adoções Urgentes, Visualizações) e a lista de seus animais, podendo "Editar" ou "Excluir".

•	Cadastro de Animal (/DOAÇÃO-6): Para adicionar um novo pet, a ONG acessa o formulário de cadastro de animais, faz o upload de uma foto, preenche as características (espécie, porte, idade, sexo, descrição) e clica em "Adicionar animal à lista".

•	Visibilidade Pública (/DOAÇÃO-5): As ONGs cadastradas passam a ser listadas na página "Nossas ONGs Parceiras", onde os usuários podem clicar em "Entrar em contato".



## Wireframes

O objetivo do wireframe do nosso site é facilitar a navegação do usuário e planejar um sistema visualmente atrativo, focado em auxiliar no processo de adoção, contribuindo para aumentar as chances de sucesso.

https://www.figma.com/site/ZOO8VfcLVItzkpR0VXhpHL/Wireframes?node-id=0-1&t=xOOM0zqFEUE5d8xq-1

### Exemplo

A tela inicial apresenta um menu lateral com as principais seções do portal, enquanto a navigation bar, ao topo, apresenta informações de envio de imagens ou navegação pela galeria de fotos. A área central apresenta a galeria de fotos na forma de uma grade. Nesta tela, são apresentados os seguintes requisitos

![Exemplo de Wireframe](img/wireframe-example.png)

 
> **Links Úteis**:
> - [Protótipos vs Wireframes](https://www.nngroup.com/videos/prototypes-vs-wireframes-ux-projects/)
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [Axure](https://www.axure.com/edu) (Licença Educacional)
> - [InvisionApp](https://www.invisionapp.com/) (Licença Educacional)
