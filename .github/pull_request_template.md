## Tarefa do board

<!-- Uma linha com a issue do tracker que este PR move no board. Exemplo:

Tarefa: SeuConte/seu-conte-produto#42

Escreva a linha fora deste comentário, com o número da sua tarefa.
Se a branch começa com o número da issue (ex.: feat/42-tela-de-login para a tarefa #42), a automação escreve a linha sozinha.
PR que não é de nenhuma tarefa (dependência, chore) leva o label sem-tarefa.
Nunca use Closes ou Fixes: quem fecha a issue é a automação, na release. -->

---

## O que foi feito

<!-- Descreva de forma objetiva o que muda com este PR -->

---

## Tipo de mudanca

- [ ] Nova funcionalidade

- [ ] Correcao de bug

- [ ] Refatoracao

- [ ] Infraestrutura

- [ ] Configuracao ou dependencia

- [ ] Documentacao

---

## Checklist

- [ ] Testes realizados localmente

- [ ] Codigo de debug e logs temporarios foram removidos

- [ ] Mudanças que afetam outros devs e features em desenvolvimento estão documentadas

- [ ] Variaveis de ambiente novas estao documentadas (.env.example):

<!-- - Liste as novas variáveis aqui... -->

---

## Como testar

<!-- Passos minimos para o revisor validar a mudanca -->

1.
2.

---

## Impacto na infra

<!-- O que precisa mudar fora do código para este PR ser promovido. Se nada, marque a primeira opção e apague o resto. -->

- [ ] Nenhum impacto na infra

- [ ] Variavel de ambiente nova ou com valor diferente por ambiente (qual e o valor esperado em cada um):

- [ ] Segredo novo (qual, e quem gera):

- [ ] Servico, permissao ou recurso de nuvem novo (ex.: bucket, chave, fila, acesso a um servico da AWS):

- [ ] Fila nova ou job que mudou de fila:

- [ ] Dependencia de sistema, extensao ou imagem de build nova:

- [ ] Agendamento novo ou alterado:

- [ ] Migration pesada ou destrutiva (precisa de janela, de expand/contract ou de backup antes):

- [ ] Ordem de deploy entre repositorios (o que tem de subir antes):

<!-- Detalhe aqui o que a infra precisa fazer e em que momento (antes, junto ou depois do merge). -->

---

## Tamanho do diff

<!-- Medido com `git diff --numstat <base>...HEAD`, em arquivos e linhas (+ e -) por segmento. Use os segmentos que fazem sentido no repo, por exemplo Codigo, Migrations, Testes, Docs, Infra (Dockerfile, pipeline, scripts) e Ferramentas (arquivos gerados ou de ferramenta, como lockfile e baseline de analise estatica). Segmento vazio sai. Ferramentas fica separado porque arquivo gerado soma milhares de linhas e esconde a proporcao do que foi escrito a mao. Em PR de stack acima da primeira camada, acrescente uma linha com o acumulado do stack contra a branch de destino. -->

| Segmento | Arquivos | Linhas |
| --- | --- | --- |
| Codigo | | |
| Testes | | |
| Total | | |

---

## Observacoes para o revisor

<!-- Decisoes técnicas, trade-offs, pontos de atenção e impactos (breaking changes) -->
