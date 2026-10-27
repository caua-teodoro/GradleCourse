# O que é o Gradle?
- Sistema de automação de compilação e de builds
- Ele pega todos os arquivos do projeto e cria um JAR ou um apk (Android)
- Resumindo ele faz a build do seu projeto e você pode definir como será essa build
- Sistemas similares: maven e ant

# O que o Gradle é capaz de fazer?
- Fazer diversas tarefas antes, durante e após as builds
- Rodar os unit tests do projeto
- Colocar o JAR ou a APK em uma pasta diferente da padrão
- Gestão de dependências do projeto
- Fazer builds com multiplos módulos (alguns chamam de multi projetos) e variações de compilação
- Gerar documentação (Javadoc)
- Assinar apks e aab no Android
- O melhor: tudo em um único comando

# Características
- Os arquivos de build do Gradle são scripts escritos na linguagem Groovy.
- Ele é baseado em tasks.
- Tem um forte sitema de plugins
- Open source

# GradleW
- Permite utilizar todas as funcionalidades do Gradle sem precisar instalá-lo
- "Envelopa" toda a configuração do gradle
- Outros devs podem trabalhar no projeto com a mesma configuração do gradle
- Muito utilizado com times grandes
