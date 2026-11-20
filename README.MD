## 🌱 Sobre o projeto

O **ReCiclo** é um protótipo de aplicação web voltado ao **reaproveitamento e à circulação de materiais**. A proposta é aproximar pessoas que possuem itens sem uso de outras que podem utilizá-los em projetos, atividades ou novas criações.

Em vez de descartar materiais que ainda têm utilidade, a ideia é facilitar sua descoberta e disponibilização, incentivando práticas de consumo mais conscientes.

O projeto foi desenvolvido no contexto da **Global Solution FIAP 2026**, com foco inicial na construção da interface e na experiência de navegação.


## 📱 Telas implementadas

| Tela | Descrição | Implementação atual |
| --- | --- | --- |
| **Início** | Apresentação da proposta, carrossel informativo e atalhos principais. | Interface e navegação |
| **Explorar materiais** | Campo de pesquisa e cards com exemplos de materiais, quantidades e bairros. | Listagem demonstrativa estática |
| **Disponibilizar material** | Formulário com categoria, título, descrição, quantidade e bairro de retirada. | Primeira etapa visual; envio ainda não implementado |

### Destaques da interface

- **Carrossel Bootstrap** na página inicial.
- **Navegação inferior fixa**, com atalhos para Início, Explorar, Anunciar e Salvos.
- **Cards de materiais** com imagens e informações resumidas.
- **Formulário de anúncio** estruturado com campos HTML.
- **Identidade visual própria**, com paleta verde e tons neutros.
- **Layout com foco mobile**, usando CSS personalizado e componentes do Bootstrap.

> **Nota:** A área de Salvos aparece na navegação, mas ainda não possui uma funcionalidade implementada. A pesquisa e o formulário também não estão conectados a uma base de dados.


## 📁 Estrutura do projeto

```text
ReCiclo-v1.0/
├── index.html
├── README.MD
└── assets/
    ├── img/
    │   └── ...
    ├── pages/
    │   ├── advertise.html
    │   └── available-material.html
    └── styles/
        └── style.css
```

## 🚀 Como executar localmente

**1. Clone o repositório:**

```bash
git clone https://github.com/kauedev24/ReCiclo-v1.0.git
```

**2. Acesse a pasta:**

```bash
cd ReCiclo-v1.0
```

**3. Abra o projeto:**

Abra o arquivo `index.html` no navegador ou utilize uma extensão de servidor local, como **Live Server**, no VS Code.

Não é necessário instalar dependências via npm. As bibliotecas externas utilizadas são carregadas por CDN.


**♻️ ReCiclo**

[Experimentar o protótipo](https://kauedev24.github.io/ReCiclo-v1.0/)
