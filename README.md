# Definições e Padrões do Projeto

Esta documentação encontra-se alguns acordos firmados pelos times de Desenvolvimento envolvidos com a tecnologia Flutter e como sera trabalhado.

---
## Versionamento

Lembre-se de no pubspec.yaml sempre atualizar a versão, a tag dev seguir a mesma.
```yaml
version: 1.0.1
```
Deve-se também a cada alteração ser relatado no arquivo CHANGELOG.md as esterações realizadas, versão, data e se disponível a branch.
```md
## [1.0.1] - Fix Dependencies - 21/04/2021 - [fix/fix-dependencies]
* Foi atualizado as dependencias no no arquivo pubspec.yaml
```
A Forma de versionamento definida foi utilizando Tags.
```bash
Listagem de Tags: git tag -n
Criação de Tags: git tag 'v<mejor.minor.patch>'
Enviar as Tags: git push --tags
```
A importação das versões criadas deve ser da seguinte forma:
```yaml
dependencies:
  micro_core:
    git:
      url: https://github.com/DeividWillyan/-Curso-Micro-Core.git
      ref: v1.0.0 # <- Aqui vai a Tag versionada
```
| obs: Também pode ser utilizado o dependency_overrides para resolver conflito de versões.


Links úteis

- [How to Create Git Tag](https://devconnected.com/how-to-create-git-tags)
- [Semantic Versioning 2.0.0](https://semver.org/)

---
## Arquitetura

desrição da forma de versionamento

Links úteis

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)
---
## Testes

desrição da forma de versionamento

Links úteis

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)
---
## Code Review
desrição da forma de versionamento

Links úteis

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)
---
## Scripts 
desrição da forma de versionamento

Links úteis

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

---
### Outros
desrição da forma de versionamento

Links úteis

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)
