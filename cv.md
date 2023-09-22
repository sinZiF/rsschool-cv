# ANDREI KISLIUK


### Mam na imię Andrei i jestem Białorusinem. Ponad 3 lata mieszkam w Polsce. Interesuje mnie jak działają strony internetowe i interakcja z użytkownikiem na nie. Za pomocom języka JavaScript możemy tworzyć różne ciekawe rzeczy i ten język tworzy naprawdę arcydzieło. Mianowicie dla tego poświęcam dużo wolnego czasu na naukę tego języka: czytam książki, piszę kod źródłowy, oglądam różne filmiki i biorę aktywny udział w różnych profesjonalnych szkoleniach. Następnym krokiem będzie poznawanie React-u i rozwój w kierunku Front-End Developera. Cały czas rozwijam swoje umiejętności językowe z polskiego i angielskiego i znam język rosyjski na poziomie ojczystym.

___


## Kontakt
[GitHub](https://github.com/sinZiF) | kisliuk.andrei@gmail.com | [linkedin](https://www.linkedin.com/in/andrei-kisliuk-bb2357193/)

___

## Umiejętności:

 * FIGMA
 * HTML5
 * CSS
 * SASS
 * JavaScript
 * GitHub

___


## Przykład kodu:

 ```
window.addEventListener('DOMContentLoaded', () => {
    async function getImage() {
        const location = 'https://api.unsplash.com/';
        const access ='client_id=jOPr1DHnHv-VPxFbQRLCvjwiQFXqp-Z6c_F1VDZZ7B0';
        let response = await fetch(`${location}photos/random?${access}&count=7`);
        let data = await response.json();
        console.log(data)
        return data
    };
    const imgBlock = document.querySelector('.image');
    getImage()
    .then(data => {
        data.forEach(image => {
            const img = document.createElement('img');
            img.classList.add('img')
            img.src= `${image.urls.full}`;
            imgBlock.append(img)
        })
    })
})
 ```

___


## Doświadczenie:

### Kursy:

#### JS/FE Pre-School 2022Q4

___

## Wykształcenie:

##### Grodzieński Uniwersytet Państwowy im. Janki Kupały Sierpień 2017 - Maj 2018
Prawoznawstwo

##### Pińska Państwowa przemysłowa szkoła pedagogiczna Sierpień 2009 - Maj 2012
Techniczna eksploatacja samochodów

___


## Języki obce:

#### Biłoruski:
C2
#### Rosyjski:
C2
#### Polski:
B1

#### Angielski:
A1

___
