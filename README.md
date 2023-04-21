# Esercizio - Spring Boot - Swagger 1
* scrivere un'applicazione Spring Boot che utilizzi le seguenti dipendenze:
  * `Lombok`
  * `Spring Boot DevTools`
  * `Web primaverile`
* aggiungi solo 1 dipendenza necessaria a `pom.xml` per `springfox`:
  * `springfox-boot-starter`
* in `application.yml` aggiungi la seguente configurazione:
  * `spring.mvc.pathmatch.matching-strategy=ant_path_matcher`
    * ricordati di [convertire](http://mageddo.com/tools/yaml-converter) da `properties` a `yaml`
* esponi la spavalderia con qualche `ApiInfo` e 1 `Tag` casuale riguardante il `name-controller` che restituisce il tuo nome
* eseguire l'applicazione Spring sulla porta `1234`
* fornire un controller predefinito per il root con un messaggio di benvenuto (ad es. per qualcuno che visita `localhost:1234`)

# Exercise - Spring Boot - Swagger 1
* write a Spring Boot application that uses the following dependencies:
  * `Lombok`
  * `Spring Boot DevTools`
  * `Spring Web`
* add just 1 necessary dependency to the `pom.xml` for `springfox`:
  * `springfox-boot-starter`
* in `application.yml` add the following configuration:
  * `spring.mvc.pathmatch.matching-strategy=ant_path_matcher`
    * remember to [convert](http://mageddo.com/tools/yaml-converter) from `properties` to `yaml`
* expose the swagger with some `ApiInfo` and 1 random `Tag` regarding the `name-controller` that returns your name
* run the Spring application on port `1234`
* provide a default controller for the root with a welcome message (e.g. for someone who visit `localhost:1234`)
