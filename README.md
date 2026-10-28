# Desafio Simulador Barbearia — 30/10/2026

Este repositório é destinado ao envio da resposta individual do desafio. Siga as instruções abaixo para que sua entrega seja identificada corretamente e para preservar o trabalho dos demais alunos.

## O que enviar

Envie **somente o arquivo com o código-fonte da sua solução**, com a extensão `.cs`. Não envie a pasta inteira do projeto, arquivos executáveis, bibliotecas, arquivos temporários ou arquivos de configuração.

Salve o arquivo dentro da pasta `Respostas`, usando exatamente este padrão:

```text
[3 primeiros dígitos do CPF]-[2 últimos dígitos do CPF]-[PrimeiroNome]-[SegundoNome].cs
```

Exemplo fictício:

```text
123-45-Ana-Silva.cs
```

Use os três primeiros e os dois últimos dígitos do seu CPF, sem pontos ou traços adicionais. Escreva seu primeiro e segundo nome, separados por hífen. Mantenha a extensão `.cs`.

## Onde e como enviar

A entrega deve estar na branch `Subir-Resposta-Aqui`, dentro da pasta `Respostas`. **Nunca envie sua resposta para a branch `main`.**

1. Abra um terminal na pasta local do repositório.
2. Atualize as referências do GitHub e mude para a branch de entrega:

   ```bash
   git fetch origin
   git switch Subir-Resposta-Aqui
   ```

   Se a branch ainda não existir localmente, mas existir no GitHub, use:

   ```bash
   git switch --track origin/Subir-Resposta-Aqui
   ```

3. Crie a pasta `Respostas`, caso ainda não exista, e coloque nela seu arquivo `.cs`.
4. Confira a branch atual e os arquivos que serão enviados:

   ```bash
   git branch --show-current
   git status
   ```

   Confirme que a branch exibida é `Subir-Resposta-Aqui` e que seu arquivo está em `Respostas/`. Não prossiga se aparecer `main` ou algum arquivo que você não pretende entregar.
5. Adicione **apenas o seu arquivo**, faça o commit e envie a branch:

   ```bash
   git add Respostas/SEU-ARQUIVO.cs
   git commit -m "Adiciona resposta do aluno"
   git push origin Subir-Resposta-Aqui
   ```

   Troque `SEU-ARQUIVO.cs` pelo nome real do seu arquivo. Se o Git informar que a branch está atualizada ou que não há alterações para commit, confira se salvou o arquivo no local correto.

## Cuidados importantes

- **Não use `git push --force` nem `git push -f`.** Isso pode apagar ou substituir o envio de outras pessoas.
- Não faça commits nem pushes na branch `main`.
- Confira a branch com `git branch --show-current` antes de enviar.
- Adicione somente o seu arquivo `.cs`; não use `git add .` sem conferir antes o resultado de `git status`.
- Não altere, apague, renomeie ou envie por cima dos arquivos de outros alunos.
- Não envie o código de outra pessoa, nem compartilhe sua solução durante a atividade.
- Se houver conflito, erro no push ou dúvida sobre a branch, pare e peça ajuda ao professor. **Não tente resolver com force push.**
- Antes de encerrar, confira no GitHub se o arquivo aparece na branch `Subir-Resposta-Aqui`, dentro de `Respostas`, com o nome correto.

Bom desafio!
