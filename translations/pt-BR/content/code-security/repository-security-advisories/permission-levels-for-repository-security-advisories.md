---
title: Permission levels for repository security advisories
intro: The actions you can take in a repository security advisory depend on whether you have admin or write permissions to the security advisory.
redirect_from:
  - /articles/permission-levels-for-maintainer-security-advisories
  - /github/managing-security-vulnerabilities/permission-levels-for-maintainer-security-advisories
  - /github/managing-security-vulnerabilities/permission-levels-for-security-advisories
  - /code-security/security-advisories/permission-levels-for-security-advisories
versions:
  fpt: '*'
  ghec: '*'
type: reference
topics:
  - Security advisories
  - Vulnerabilities
  - Permissions
shortTitle: Níveis de permissão
---

This article applies only to repository-level security advisories. Anyone can contribute to global security advisories in the {% data variables.product.prodname_advisory_database %} at [github.com/advisories](https://github.com/advisories). Edits to global advisories will not change or affect how the advisory appears on the repository.  For more information, see "[Editing security advisories in the {% data variables.product.prodname_advisory_database %}](/code-security/supply-chain-security/managing-vulnerabilities-in-your-projects-dependencies/editing-security-advisories-in-the-github-advisory-database)."

## Visão geral das permissões

{% data reusables.repositories.security-advisory-admin-permissions %} For more information about adding a collaborator to a security advisory, see "[Adding a collaborator to a repository security advisory](/code-security/repository-security-advisories/adding-a-collaborator-to-a-repository-security-advisory)."

| Ação                                                                                                                                                                                                                                                                                                        | Permissões de gravação | Permissões de administrador |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | --------------------------- |
| Veja um rascunho da consultoria de segurança                                                                                                                                                                                                                                                                | X                      | X                           |
| Add collaborators to the security advisory (see "[Adding a collaborator to a repository security advisory](/code-security/repository-security-advisories/adding-a-collaborator-to-a-repository-security-advisory)")                                                                                         |                        | X                           |
| Editar e excluir quaisquer comentários na consultoria de segurança                                                                                                                                                                                                                                          | X                      | X                           |
| Create a temporary private fork in the security advisory (see "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)")         |                        | X                           |
| Add changes to a temporary private fork in the security advisory (see "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)") | X                      | X                           |
| Create pull requests in a temporary private fork (see "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)")                 | X                      | X                           |
| Merge changes in the security advisory (see "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)")                           |                        | X                           |
| Add and edit metadata in the security advisory (see "[Publishing a repository security advisory](/code-security/repository-security-advisories/publishing-a-repository-security-advisory)")                                                                                                                 | X                      | X                           |
| Add and remove credits for a security advisory (see "[Editing a repository security advisory](/code-security/repository-security-advisories/editing-a-repository-security-advisory)")                                                                                                                       | X                      | X                           |
| Fechar o rascunho da consultoria de segurança                                                                                                                                                                                                                                                               |                        | X                           |
| Publish the security advisory (see "[Publishing a repository security advisory](/code-security/repository-security-advisories/publishing-a-repository-security-advisory)")                                                                                                                                  |                        | X                           |

## Leia mais

- "[Adding a collaborator to a repository security advisory](/code-security/repository-security-advisories/adding-a-collaborator-to-a-repository-security-advisory)"
- "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)"
- "[Removing a collaborator from a repository security advisory](/code-security/repository-security-advisories/removing-a-collaborator-from-a-repository-security-advisory)"
- "[Withdrawing a repository security advisory](/code-security/repository-security-advisories/withdrawing-a-repository-security-advisory)"
