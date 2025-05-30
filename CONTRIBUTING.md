
Diretrizes de Contribuição
==========================

Obrigado por contribuir com este projeto! Este documento orienta como colaborar de forma organizada e eficiente.

Regras Gerais
-------------

- Seja respeitoso com todas as pessoas envolvidas.
- Escreva código limpo, organizado e comentado sempre que necessário.
- Antes de subir alterações, confirme se tudo está funcionando corretamente.

Como Contribuir
---------------

1. **Crie uma nova branch** para sua alteração:
   ```bash
   git checkout -b tipo/nome-da-alteracao
   ```
   Exemplos:
   - `feat/tela-login`
   - `fix/erro-formulario`
   - `docs/ajuste-readme`

2. **Faça suas alterações localmente.**

3. **Siga o padrão de commits abaixo** ao registrar mudanças.

4. **Envie sua branch:**
   ```bash
   git push origin tipo/nome-da-alteracao
   ```

5. **Crie um Pull Request** no GitHub com uma descrição clara do que foi feito.

Padrão de Commits
------------------

Use este formato nas mensagens de commit:

```bash
<tipo>: <descrição curta e direta>
```

Tipos permitidos:

- `feat`: nova funcionalidade
- `fix`: correção de bug
- `docs`: mudanças na documentação
- `style`: formatação, identação, etc (sem mudança de código)
- `refactor`: refatoração de código (sem nova funcionalidade ou correção)
- `test`: adição ou ajuste de testes
- `chore`: tarefas de manutenção (ex: configs, scripts)

Exemplos:
- `feat: adicionar tela de cadastro`
- `fix: corrigir bug no botão de login`
- `docs: atualizar README com instruções de instalação`

Atenção
-------

- Evite fazer commits diretamente na branch `main`.
- Teste suas alterações antes de subir.
- Se possível, escreva testes para novos comportamentos.

Obrigado
--------

Sua contribuição é muito bem-vinda! Obrigado por fazer parte do desenvolvimento desta aplicação.
