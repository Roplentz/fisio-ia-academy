# Fisio IA Academy — MVP 1.1

Laboratório educacional que conecta anatomia lombar, conteúdo estruturado do PilatesVision e um tutor contextual demonstrativo.

## Entregas

- exploração dos segmentos L2–L3, L4–L5 e L5–S1;
- vistas, camadas e movimentos didáticos;
- três casos clínicos educacionais;
- biblioteca inicial baseada na taxonomia do PilatesVision;
- busca e filtro por nível;
- relação entre exercício, anatomia, métricas e segurança;
- tutor contextual local, sem envio de dados clínicos;
- interface responsiva para computador e celular.

## Executar

```bash
python3 -m http.server 8080
```

Acesse `http://localhost:8080`.

## Próxima arquitetura

1. React + TypeScript;
2. modelo GLB/GLTF com Three.js;
3. `knowledge-core` versionado do PilatesVision;
4. tutor com recuperação somente em fontes aprovadas;
5. autenticação, turmas e progresso;
6. integração com `motion-core` após validação;
7. auditoria, consentimento e governança LGPD.

> Uso educacional. Não realiza diagnóstico nem substitui avaliação profissional.
