<div align="center">

# 📊 Turma de Visualização de Dados

**Repositório oficial da turma** · Lab365 / SENAI SC

[![Alunos](https://img.shields.io/badge/alunos-19-blue?style=flat-square)](./alunos/)
[![PRs Bem-vindos](https://img.shields.io/badge/PRs-bem--vindos-brightgreen?style=flat-square)](./CONTRIBUTING.md)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-lightgrey?style=flat-square)](./LICENSE)

</div>

---

## Sobre o Curso

Este repositório reúne os materiais, exercícios e portfólios da turma de **Visualização de Dados**. O objetivo é que cada aluno use seu espaço aqui como ponto de partida para um portfólio público de análise de dados — visível para recrutadores e colaboradores.

Ao longo do curso você aprenderá a:

- Coletar, limpar e transformar dados reais
- Criar visualizações claras e eficazes com Python
- Contar histórias com dados (data storytelling)
- Versionar projetos com Git e GitHub
- Publicar um portfólio profissional

---

## Tecnologias da Turma

| Área | Ferramentas |
|------|-------------|
| Linguagem | Python 3.10+ |
| Análise | Pandas, NumPy |
| Visualização | Matplotlib, Seaborn, Plotly |
| Notebooks | Jupyter Notebook / JupyterLab |
| Versionamento | Git + GitHub |
| Ambiente | Anaconda / venv |

---

## Estrutura do Repositório

```
turma-visualizacao-de-dados/
│
├── aulas/                  ← Notebooks e slides das aulas
├── exercicios/             ← Enunciados dos exercícios propostos
├── datasets/               ← Datasets compartilhados da turma
├── projetos/               ← Projetos finais publicados
│
├── alunos/                 ← ✏️  ÁREA DOS ALUNOS — cada um tem sua pasta aqui
│   ├── TEMPLATE_README.md  ← Modelo de portfólio para copiar
│   └── nome-sobrenome/     ← Pasta individual de cada aluno
│       ├── README.md       ← Apresentação e portfólio pessoal
│       ├── exercicios/     ← Entregas de exercícios
│       └── projetos/       ← Projetos autorais
│
└── .github/                ← Configurações internas do GitHub (não editar)
    └── ISSUE_TEMPLATE/     ← Formulários de dúvida e problema de PR
```

> **Alunos:** toda a sua atuação é dentro de `alunos/seu-nome/`. Nenhum outro diretório deve ser modificado.

---

## Portfólios dos Alunos

> Cada aluno mantém sua própria pasta em `alunos/`. Clique no nome para visitar o portfólio.

| Aluno | Pasta |
|-------|-------|
| Carlos F. | [Carlos_F](./alunos/Carlos_F/) |
| Christian Wis | [Christian_Wis](./alunos/Christian_Wis/) |
| Claudi Borges | [claudi_borges](./alunos/claudi_borges/) |
| Daniel Roberto | [daniel_roberto](./alunos/daniel_roberto/) |
| Felipe Vampre | [felipe_vampre](./alunos/felipe_vampre/) |
| Gustavo Branga | [gustavo_branga](./alunos/gustavo_branga/) |
| Leo Gobel | [Leo_Gobel](./alunos/Leo_Gobel/) |
| Lourenço Lemos | [lourenco_lemos](./alunos/lourenco_lemos/) |
| Luís Napolitano | [luis_napolitano](./alunos/luis_napolitano/) |
| Luís Oliveira | [luis_oliveira](./alunos/luis_oliveira/) |
| Luiz Fernando Jesus | [luiz_fernando_jesus](./alunos/luiz_fernando_jesus/) |
| Marcos Bhering | [marcos_bhering](./alunos/marcos_bhering/) |
| Maria Helena | [maria_helena](./alunos/maria_helena/) |
| Orlando Castro | [orlando_castro](./alunos/orlando_castro/) |
| Robson Américo | [robsonaamerico](./alunos/robsonaamerico/) |
| Rogério Estumano | [rogerio_estumano](./alunos/rogerio_estumano/) |
| Samuel Bucco | [samuel_bucco](./alunos/samuel_bucco/) |
| Sérgio Leite | [sergio_leite](./alunos/sergio_leite/) |
| Victor H. Santos | [victor_h_santos](./alunos/victor_h_santos/) |
| Cláudio Neves _(professor)_ | [claudio_neves](./alunos/claudio_neves/) |

_Sua pasta ainda não aparece aqui? Siga o [guia de contribuição](./CONTRIBUTING.md) e abra um PR._

---

## Como Participar — Fork e Clone

Você vai usar **os dois**: fork e clone. Eles fazem coisas diferentes e se complementam. Entenda cada um antes de combiná-los.

---

### O que é Fork

**Fork** é uma cópia do repositório criada **dentro da sua conta no GitHub** (na nuvem). Você faz isso diretamente pelo site do GitHub — sem precisar do terminal.

**Quando usar:** quando você não tem permissão de escrita no repositório original (como é o caso aqui — somente o professor pode escrever diretamente).

**Como fazer:**

1. Acesse [github.com/cfneves/turma-visualizacao-de-dados](https://github.com/cfneves/turma-visualizacao-de-dados)
2. Clique no botão **Fork** no canto superior direito
3. Confirme clicando em **Create fork**

Resultado: agora existe uma cópia em `github.com/SEU_USUARIO/turma-visualizacao-de-dados` — essa cópia é **sua** e você pode fazer o que quiser nela.

> O fork fica no GitHub. Você ainda não tem nada no seu computador.

---

### O que é Clone

**Clone** é o ato de baixar um repositório para o **seu computador**. A partir daí você trabalha localmente — no VS Code, Jupyter, ou qualquer editor.

**Quando usar:** sempre que quiser trabalhar nos arquivos localmente, na sua máquina.

**Como fazer:**

```bash
# No terminal, dentro da pasta onde quer salvar o projeto:
git clone https://github.com/SEU_USUARIO/turma-visualizacao-de-dados.git
cd turma-visualizacao-de-dados
```

> ⚠️ Clone sempre o SEU fork (`SEU_USUARIO`), nunca o do professor (`cfneves`). Se clonar o do professor, você não terá permissão para enviar suas alterações.

Resultado: o repositório agora existe no seu computador. Qualquer alteração que você fizer precisa ser enviada de volta ao GitHub com `git push`.

---

### Fork vs Clone — comparação rápida

| | Fork | Clone |
|--|------|-------|
| **Onde acontece** | No GitHub (navegador) | No terminal (sua máquina) |
| **Onde fica o resultado** | Na sua conta do GitHub | Na sua pasta local |
| **Para que serve** | Criar sua cópia com permissão de envio | Trabalhar localmente nos arquivos |
| **Frequência** | Uma vez por repositório | Uma vez por máquina |

---

### Fluxo completo — os dois juntos

```
Repositório do professor          Seu GitHub               Seu computador
github.com/cfneves/...    →fork→  github.com/SEU_USUARIO/  →clone→  pasta local
                                         ↑                              ↓
                                         └──────── push ────────────────┘
                          ←PR←   github.com/SEU_USUARIO/
```

**1. Fork — faça UMA vez**

Acesse [github.com/cfneves/turma-visualizacao-de-dados](https://github.com/cfneves/turma-visualizacao-de-dados) e clique no botão **Fork** (canto superior direito). Isso cria uma cópia do repositório na sua conta.

**2. Clone — faça UMA vez por máquina**

Copie o endereço do SEU fork (não o do professor) e rode no terminal:

```bash
git clone https://github.com/SEU_USUARIO/turma-visualizacao-de-dados.git
cd turma-visualizacao-de-dados
```

> ⚠️ Atenção: clone sempre o SEU fork (`SEU_USUARIO`), não o repositório do professor (`cfneves`). Se clonar o do professor, não terá permissão para enviar alterações.

**3. Conecte ao repositório original — faça UMA vez**

Isso permite que você atualize seu fork quando o professor adicionar novos materiais:

```bash
git remote add upstream https://github.com/cfneves/turma-visualizacao-de-dados.git

# Confirme que os dois endereços estão configurados:
git remote -v
# origin    https://github.com/SEU_USUARIO/turma-visualizacao-de-dados.git
# upstream  https://github.com/cfneves/turma-visualizacao-de-dados.git
```

**4. Crie sua pasta de aluno — faça UMA vez**

```bash
mkdir alunos/nome-sobrenome
cp alunos/TEMPLATE_README.md alunos/nome-sobrenome/README.md
```

**5. Para cada entrega: edite → commit → push → PR**

```bash
# Antes de qualquer entrega, atualize seu fork com o conteúdo mais recente:
git fetch upstream
git merge upstream/main

# Faça suas alterações dentro de alunos/seu-nome/
# Depois envie:
git add alunos/seu-nome/
git commit -m "feat(alunos): adiciona exercício 01 - Seu Nome"
git push origin main

# Por fim, abra um Pull Request no GitHub
```

Consulte o [CONTRIBUTING.md](./CONTRIBUTING.md) para o guia completo, incluindo como resolver conflitos.

---

## Regras do Repositório

- Mantenha todos os seus arquivos dentro da sua pasta `alunos/nome-sobrenome/`
- **Nunca** modifique arquivos de outros alunos
- Nomes de arquivo sem espaços — use `_` ou `-` (ex: `exercicio_01.ipynb`)
- Datasets grandes (> 50 MB): adicione apenas na pasta `datasets/` compartilhada
- Notebooks devem rodar sem erros antes de serem enviados
- Commits com mensagens descritivas seguindo a convenção do projeto

---

## Dúvidas e Suporte

- Abra uma **[Issue](https://github.com/cfneves/turma-visualizacao-de-dados/issues)** com a tag `[dúvida]` no título
- Para problemas no seu PR, descreva o erro na própria thread do PR
- Para conflitos de merge, consulte a seção específica no [CONTRIBUTING.md](./CONTRIBUTING.md#resolvendo-conflitos)

---

## Professor

**Cláudio Neves** — [GitHub](https://github.com/cfneves)

---

<div align="center">
  <sub>Feito com dedicação pela turma de Visualização de Dados · Lab365 / SENAI SC</sub>
</div>
