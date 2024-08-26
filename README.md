# Aviso

Deixando claro: o material abaixo partiu de um curso gratuito e não pode ser redistribuído por mim. Se o assunto interessar, procure o curso aberto da trilha de Java com Spring Boot. Se um dia a plataforma retirar o acesso ou passar a cobrar, não está no meu alcance — mas o material de lá é muito bom e quem assina um plano alcança bem mais conteúdo.


# Geral

Todo o conteúdo deste repositório, com exceção deste arquivo de apresentação, foi gerado com o assistente de parâmetros do Maven, chegando ao comando de criação a partir de um arquétipo de projeto rápido:

```
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5
```

Com o esqueleto pronto, a execução dos testes fica assim:

> A ordem dos passos importa: nao pule a preparacao do ambiente.


```
mvn test
```