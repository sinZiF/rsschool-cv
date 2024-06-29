# ANDREI KISLIUK


### Mam na imię Andrei i pochodzę z Białorusi. Od ponad pięciu lat mieszkam w Polsce. Fascynuje mnie, jak działają strony internetowe i interakcje użytkowników z nimi. Dzięki językowi JavaScript możemy tworzyć różne ciekawe projekty, a sam język umożliwia tworzenie prawdziwych arcydzieł. Z tego powodu poświęcam dużo wolnego czasu na naukę JavaScript, a także frameworków i narzędzi takich jak Next.js, React i TypeScript. Czytam książki, piszę kod, oglądam filmy instruktażowe i aktywnie uczestniczę w profesjonalnych szkoleniach. Rozwijam się w kierunku Front-End Developera. Cały czas doskonalę swoje umiejętności językowe w polskim i angielskim, a język rosyjski znam na poziomie ojczystym.
___


## Kontakt
[GitHub](https://github.com/sinZiF) | [linkedin](https://www.linkedin.com/in/andrei-kisliuk-bb2357193/) | <kisliuk.andrei@gmail.com>

___

## Umiejętności:
 * HTML5
 * CSS
 * JavaScript
 * React
 * Next.js
 * Tailwind css
 * FIGMA
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

#### The Complete JavaScript Course 2024: From Zero to Expert!

### Strony:

#### [mapty](kisliuk.andrei@gmail.com)

#### [forkify](https://pageforkify.netlify.app/)

___

## Wykształcenie:

##### Grodzieński Uniwersytet Państwowy im. Janki Kupały Sierpień 2017 - Maj 2018
### Prawoznawstwo

##### Pińska Państwowa przemysłowa szkoła pedagogiczna Sierpień 2009 - Maj 2012
### Techniczna eksploatacja samochodów

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