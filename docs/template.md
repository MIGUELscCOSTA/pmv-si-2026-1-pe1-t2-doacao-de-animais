# Template padrão do site

Layout padrão do site (HTML e CSS) que será utilizado em todas as páginas com a definição de identidade visual, aspectos de responsividade e iconografia.

Explique as guias de estilo utilizadas no seu projeto.

## Design

Detalhe os layouts que serão utilizados. Apresente onde será colocado o logo do sistema. Defina os menus padrões, entre outras coisas.


## Cores

### 🟦 Cor Dominante (60%)
* **Background:** Azul Claro (Base suave para não cansar a vista durante a navegação).

### 🟦🟥🟧 Cores Secundárias (30%)
*Utilizadas em elementos estruturais como Títulos, Menus e Rodapés.*
* **Azul Institucional:** `#083DA6`
* **Vermelho:** `#BF1304`
* **Amarelo:** `#F2B035`

### 🟩🟧 Cores de Destaque / Accent (10%)
*Cores vibrantes para Call to Action (CTAs) e conversão.*
* **Verde Escuro (`#214001`):** Usado exclusivamente para conclusão de adoção e sucesso no cadastro.
* **Laranja Escuro (`#A64F03`):** Usado para alertas, links importantes e ícones de destaque.


## Tipografia

Para garantir a melhor experiência de leitura e consistência visual no projeto, definimos as seguintes fontes de referência:

| Aplicação | Fonte Recomendada | Características |
| :--- | :--- | :--- |
| **Títulos** | `Lato` | Elegante, moderna e de alta legibilidade para hierarquia. |
| **Descrições Curtas** | `Poppins` | Geométrica e amigável, ideal para destaques sobre os animais. |
| **Textos Longos** | `Open Sans` | Extremamente legível para blocos de texto densos. |
| **Rodapé / Footer** | `Open Sans` | Mantém a sobriedade e clareza nas informações finais. |

### 📋 Detalhamento das Fontes

* **Título Principal (Lato):** Utilizada para dar peso e autoridade às seções principais do projeto.
* **Destaques dos Animais (Poppins):** Aplicada em cards ou resumos rápidos para criar um visual clean e contemporâneo.
* **Conteúdo Geral (Open Sans):** Otimizada para leitura em telas, garantindo que descrições detalhadas não cansem o usuário.

### 🛠️ Como aplicar (CSS)

Caso este guia sirva de base para o desenvolvimento do Front-end, utilize o snippet abaixo:

```css
/* Importação via Google Fonts */
@import url('[https://fonts.googleapis.com/css2?family=Lato:wght@700&family=Open+Sans:wght@400;600&family=Poppins:wght@500&display=swap](https://fonts.googleapis.com/css2?family=Lato:wght@700&family=Open+Sans:wght@400;600&family=Poppins:wght@500&display=swap)');

h1, h2, h3 { 
    font-family: 'Lato', sans-serif; 
}

.animal-short-desc { 
    font-family: 'Poppins', sans-serif; 
}

p, footer { 
    font-family: 'Open Sans', sans-serif; 
}
```
## Iconografia

1. Definição de Ícones e FunçõesEsta seção descreve a semântica de cada ícone utilizado no menu lateral (sidebar) para garantir a navegabilidade do usuário.

### 📍 Mapeamento de Navegação (Ícones)

| Ícone | Função | Descrição |
| :--- | :--- | :--- |
| **Home** | Dashboard / Início | Retorna o usuário para a tela principal com o resumo geral. |
| **Search** | Pesquisa Geral | Abre o campo de busca para localizar registros no sistema. |
| **Building** | Gestão de Unidades | Acesso ao cadastro de empresas, prédios ou filiais. |
| **Heart** | Favoritos | Atalho para os itens ou seções marcados pelo usuário. |
| **Dollar** | Financeiro | Acesso ao fluxo de caixa, faturamentos e pagamentos. |
| **Code** | Dev Tools / API | Área destinada a configurações técnicas ou integrações. |
| **Help** | Central de Ajuda | Abre o FAQ ou documentação de suporte ao usuário. |
| **Phone** | Contato | Atalho para suporte via chat ou abertura de chamados. |

### 🎨 Padronização Visual (CSS)
Todos os ícones seguem o padrão visual abaixo para garantir consistência na interface:

- **Cor Principal:** `#FFFFFF` (Branco)
- **Background Sidebar:** `#00897b` (Teal)
- **Tamanho:** `24px`
- **Interação:** `hover: scale(1.1)` e `transition: 0.2s`

### 📋 Elemento de Ícone (Geral)

| Propriedade | Valor | Descrição |
| :--- | :--- | :--- |
| **Width** | `72px` | Largura fixa da barra lateral. |
| **Height** | `100vh` | Ocupa 100% da altura da janela de visualização. |
| **Background** | `#00897b` | Cor institucional (Teal). |
| **Layout** | `Flexbox` | Organização em coluna com espaçamento de 20px. |

###Estado de Interação 
```
.nav-icon:hover {
  opacity: 1;
  transform: scale(1.1); /* Efeito visual de destaque */
}
```

###Estado Ativo (Página Atual)
```
.nav-icon.active {
  opacity: 1;
  border-left: 3px solid #FFFFFF; /* Indicador lateral de seleção */
  padding-left: 3px;
}
```
