## Viikko 2

GitHub Actions on CI/CD-alusta, jonka avulla voi automatisoida GitHub repositoryyn vietyjen projektien julkaisun ja/tai testauksen, luomalla niitä varten työnkulkuja.

Yksinkertaisimmillaan sitä voi käyttää mm. [Jekyll](https://jekyllrb.com/)-ohjelmalla generoitujen staattisten web-sivujen automaattiseen käyttöönottoon. Actions reagoi jokaiseen commitiin tai Pull Requestiin ja suorittaa koodin koonnin ja käyttöönoton. 

Web-sovelluksen CI/CD-putkisto yhdistää kehitys- ja toimitusprosessin saumattomaksi kokonaisuudeksi (käytetyt työkalut esim. [GitLab CI](https://docs.gitlab.com/ee/ci/) ja [Jenkins](https://www.jenkins.io/)). Koodin komponentteja ylläpidetään versionhallinnan avulla (esim. [git](https://git-scm.com/)) ja kaikki koodiin tehdyt muutokset ajetaan automatisoitujen testien läpi (esim. [Jest](https://jestjs.io/), [Selenium](https://www.selenium.dev/)). Hyväksytty versio julkaistaan ja otetaan käyttöön, jonka jälkeen sama prosessi alkaa uudestaan ja sovellus kehittyy jokaisessa iteraatiossa aina pidemmälle.
