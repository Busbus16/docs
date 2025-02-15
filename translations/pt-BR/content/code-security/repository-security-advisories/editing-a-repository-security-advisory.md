---
title: Editing a repository security advisory
intro: You can edit the metadata and description for a repository security advisory if you need to update details or correct errors.
redirect_from:
  - /github/managing-security-vulnerabilities/editing-a-security-advisory
  - /code-security/security-advisories/editing-a-security-advisory
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Security advisories
  - Vulnerabilities
shortTitle: Edit repository advisories
---

People with admin permissions to a repository security advisory can edit the security advisory.

{% data reusables.security-advisory.repository-level-advisory-note %}

## Sobre os créditos para a consultoria de segurança

Você pode creditar pessoas que ajudaram a descobrir, relatar ou corrigir uma vulnerabilidade de segurança. Se você creditar alguém, essa pessoa poderá optar por aceitar ou recusar crédito.

Se alguém aceitar o crédito, o nome de usuário da pessoa aparecerá na seção "Créditos" da consultoria de segurança. Qualquer pessoa com acesso de leitura ao repositório pode ver a consultoria e as pessoas que aceitaram o crédito por ela.

Se você acredita que deveria ser creditado por uma consultoria de segurança, entre em contato com a pessoa que criou a consultoria e peça que edite a consultoria para incluir o seu crédito. Somente o criador da consultoria pode dar-lhe crédito. Portanto, não entre em contato com o suporte do GitHub com relação a créditos para consultorias de segurança.

## Editar uma consultoria de segurança

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-security %}
{% data reusables.repositories.sidebar-advisories %}
4. Na lista "consultorias de segurança", clique na consultoria de segurança que deseja editar.
5. No canto superior direito das informações referentes à consultoria de segurança, clique em {% octicon "pencil" aria-label="The edit icon" %}. ![Botão para editar uma consultoria de segurança](/assets/images/help/security/security-advisory-edit-button.png)
{% data reusables.repositories.security-advisory-edit-details %}
{% data reusables.repositories.security-advisory-edit-severity %}
{% data reusables.repositories.security-advisory-edit-cwe-cve %}
{% data reusables.repositories.security-advisory-edit-description %}
11. Opcionalmente, edite os "Créditos" para a consultoria de segurança. ![Créditos para uma consultoria de segurança](/assets/images/help/security/security-advisory-credits.png)
12. Clique em **Atualizar consultoria de segurança**. ![Botão "Atualizar consultoria de segurança"](/assets/images/help/security/update-advisory-button.png)
13. As pessoas listadas na seção "Créditos" receberão um e-mail ou uma notificação da web convidando-os a aceitar o crédito. Se uma pessoa aceitar, seu nome de usuário ficará visível publicamente assim que a consultoria de segurança for publicada.

## Leia mais

- "[Withdrawing a repository security advisory](/code-security/repository-security-advisories/withdrawing-a-repository-security-advisory)"
