# Descrição do Projeto

Este projeto é um site educacional para compartilhar tarefas de casa e exercícios de programação com estudantes. Os estudantes podem navegar, visualizar e baixar tarefas diretamente do portal.

## Estrutura do Projeto

- [`assignments/`](../assignments/) Cada tarefa de casa é armazenada em sua própria subpasta com uma estrutura consistente.
- [`templates/`](../templates/) Templates reutilizáveis para novo conteúdo
- [`assets/`](../assets/) Contém os recursos do site incluindo CSS, JavaScript, imagens e arquivos de configuração
- [`index.html`](../index.html) A página principal do site que serve como um portal estático para navegar e visualizar tarefas. O conteúdo é configurável através do arquivo [`config.json`](../config.json) para gerar dinamicamente listas e detalhes de tarefas.

## Diretrizes do Projeto

- Manter estilo consistente em todas as páginas
- Manter nomes de arquivos e pastas descritivos e organizados

## Padrões Educacionais

Ao gerar conteúdo para este projeto:

- **Focado em aprendizado**: Todo conteúdo deve ser projetado com objetivos de aprendizado claros e níveis de dificuldade apropriados
- **Amigável para estudantes**: Use linguagem clara e encorajadora que motiva os estudantes

## Convenções de Commit

Para manter um histórico de mudanças claro e útil, siga estas convenções ao fazer commits:

- `type`: tipo de mudança (veja lista abaixo), em minúsculas.
- `scope` (opcional): área afetada (ex.: `assignments`, `assets`, `config`).
- `subject`: descrição curta no imperativo, sem ponto final, até ~50 caracteres.
- Corpo (opcional): descrição detalhada em linhas separadas após uma linha em branco.
- Footer (opcional): referências a issues ou breaking changes.

Tipos recomendados:
- `feat`: nova funcionalidade
- `fix`: correção de bug
- `docs`: alterações em documentação
- `style`: formatação, semântica ou estilo (sem alterar código funcional)
- `refactor`: refatoração de código que não adiciona feature nem corrige bug
- `perf`: melhorias de performance
- `test`: adição/ajuste de testes
- `chore`: tarefas de manutenção (scripts, build, etc)
- `build`: mudanças no processo de build
- `ci`: mudanças na configuração de CI
- `revert`: revert de um commit anterior

Exemplos:

Boas práticas rápidas:
- Use o tempo verbal imperativo no `subject` ("adicionar", "corrigir", "remover").
- Mantenha `subject` curto e informativo.
- Use `scope` quando a área for óbvia e útil para leitura do histórico.
- Para breaking changes, inclua `BREAKING CHANGE: descrição` no footer.
- Referencie issues com `#` no footer (ex.: `Refs #42`).

Seguir esse padrão ajuda a gerar changelogs, automatizar releases e manter o histórico legível para todos os contribuidores.