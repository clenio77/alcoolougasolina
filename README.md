# Alcool ou Gasolina

Projeto Android simples para ajudar a comparar se compensa abastecer com **álcool (etanol)** ou **gasolina**, usando a regra comum de custo-benefício:

- Se `preço do álcool / preço da gasolina <= 0,70` → álcool tende a compensar.
- Caso contrário → gasolina tende a compensar.

## Status do repositório

Este repositório atualmente contém apenas a configuração Gradle de nível raiz e arquivos de projeto. O módulo de aplicativo (`:app`) está referenciado em `settings.gradle`, mas os arquivos do módulo não estão presentes no snapshot atual.

## Estrutura atual

- `build.gradle` (raiz)
- `settings.gradle`
- `gradle.properties`
- scripts do Gradle Wrapper (`gradlew`, `gradlew.bat`)

## Como completar o projeto

1. Restaurar/criar o módulo `app/` com:
   - `app/build.gradle`
   - `app/src/main/AndroidManifest.xml`
   - código-fonte Kotlin/Java em `app/src/main/java/...`
   - recursos em `app/src/main/res/...`
2. Sincronizar o projeto no Android Studio.
3. Atualizar versões antigas de dependências/Gradle Plugin, se necessário.
4. Executar em emulador/dispositivo e validar a lógica de cálculo.

## Ideia de melhoria

- Validar entrada numérica antes do cálculo.
- Exibir recomendação com mensagem clara e acessível.
- Adicionar testes unitários para a regra de decisão.

## Licença

Defina uma licença (por exemplo, MIT) conforme a necessidade do projeto.
