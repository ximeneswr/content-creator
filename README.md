# Content Creator — plugin modular (v0.1.0)

Código-fonte público do Content Creator e pacote reutilizável com a primeira skill `hook-engineering`. A publicação deste repositório não altera a visibilidade do plugin no ChatGPT, que permanece privado.

## O que faz hoje

- Interpreta tema, público, objetivo e formato.
- Gera 20 ganchos originais a partir de mecanismos distintos.
- Prioriza os 5 mais promissores com critérios editoriais, sem alegar validação estatística.
- Para as 3 melhores alternativas de Reel de 7s, propõe texto na tela, gravação/loop, legenda com valor e CTA contextual para seguir.
- Consulta 60 frases fornecidas pelo usuário **apenas como repertório ilustrativo**.

## Organização

```text
content-creator/
  plugin.json
  skills/
    hook-engineering/
      SKILL.md
      references/
        mecanismos.md
        avaliacao-e-evidencia.md
        reels-7-segundos.md
        frases-de-referencia.md
      evals/
        casos-de-teste.md
```

## Como usar

Exemplo: "Quero um Reel de 7 segundos em loop sobre ChatGPT para iniciantes. Meu objetivo é conquistar seguidores. Me dê 20 ganchos, escolha 5 e desenvolva os melhores com texto, legenda e CTA."

A skill ajusta o fluxo conforme o pedido; você pode solicitar apenas 5 ganchos ou somente revisão.

## Próximos módulos (não implementados)

Estruturas de roteiro, formatos de vídeo, testes de performance e análises poderão ser adicionados como arquivos de referência ou skills separadas, conforme houver evidências e necessidade.

## Versionamento

Alterações de texto das referências podem ser versionadas no GitHub. Evite afirmar que um gancho foi "validado" sem dados. Esta versão não acessa Instagram, não publica conteúdo e não usa APIs externas.
