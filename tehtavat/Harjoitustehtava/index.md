# Harjoitustehtävä

### [DadJokes-sovellus](https://bfm471.github.io/DadjokesApp)

## Idea

Sovellus hakee rest-rajapinnasta sekä satunnaisia, että käyttäjän antaman hakusanan sisältäviä iskävitsejä, joita kirjautunut käyttäjä voi halutessaan tallentaa omiin suosikkeihinsa. Suosikit tallentuvat Firebasen Firestore-tietokantaan, josta sovellus hakee ne näytettäviksi "Myjokes" -näkymään käyttäjän mukaan. Vitsejä voi myös helposti poistaa suosikeista.

Sovelluksen autentikointi on toteutettu Firebasen Authenticatella.

## Responsiivisuus

Sovellus mukautuu täysin erikokoisiin käytössä oleviin päätteisiin. Tämä on toteutettu mm. Material UI:n komponenteilla, jotka auttavat responsiivisen web-sovelluksen luonnissa. Toteutuksessa on myös otettu huomioon kaksi eri väriskeemaa - light ja dark.
Testaus tehtiin webselaimen Developers tools:n ja [Responsive Testing Tools](https://responsivetesttool.com/) sivuston avulla.

## Toimivuus eri selaimilla

Sovellus testattiin Microsoft Edge, Google Chrome ja Mozzilla Firefox -selaimilla. Eroa toimivuudessa ei tunnu olevan.

## Latautumisaika

Sovelluksen latautumisaikaa testatattiin kolmella eri palvelulla, joiden palauttamat arviot olivat suotuisia. Huomionarvoista tässä on kuitenkin se, että palvelut arvioivat sovelluksen suoritumista pelkästään login-näkymän perusteella.
![image](https://github.com/bfm471/pilvipalvelutTehtava/assets/131486512/a98412be-21d9-4464-ac2b-f4b3510ff5c2)


