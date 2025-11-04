## Hello there 💫

~ ~ Welcome to my Github Page ~ ~

<b>About Me</b> <br>
My name is Jessica Binke and I am a senior at ASU pursuing my bachelor's in Graphic Information Technology with a concentration in Web Development. I have an associates in Design & Media Studies with a concentration in Graphic Design. I love brining projects to life, by utilizing both my love for graphic design and my technical skills in web development! <br>

<b>Contact Me!</b> <br>
Email: jesseri0321@gmail.com <br>
Behance: behance.com/jbinke https://www.behance.net/jessicabinke1 <br>
Code Pen: @Jessica-Binke  https://codepen.io/Jessica-Binke <br>
LinkedIn: www.linkedin.com/in/jessica-binke-307447268 <br>

<b>Languages</b> <br>
HTML (Intermediate) <br>
CSS (Intermediate) <br>
JavaScript (Intermediate) <br>

<b>Softwares</b> <br>
Visual Code Studio <br>
Adobe (Intermediate) <br>
<ul>
  <li>Photoshop</li>
  <li>InDesign</li>
  <li>Illustrator</li>
  <li>Premiere Pro</li>
  <li>Lightroom</li>
  <li>After Effects</li>
</ul>
<br>

<b>Favorite Projects</b> <br>

<b>Doctor Who Fan Website</b> 👽 <br>
<p>This work functions as a dedicated fan wiki and media database, similar in utility to platforms like IMDb or TMDB. Its design philosophy and user experience are directly inspired by the distinctive, whimsical yet technical aesthetic of the Doctor Who franchise itself. Some primary functions include a photo carousel, responsive interface, day and night color shift, and a random quote generator. </p> <br>

```
.doctors-carousel {
    max-width: 1000px;
    margin: 30px auto;
}

.doctor-slide {
    padding: 20px;
    text-align: center;
    background: var(--navy);
    border-radius: 8px;
    margin: 0 10px;
    border: 2px solid var(--yellow);
}

.doctor-slide img {
    width: 100%;
    max-height: 400px;
    object-fit: cover;
    border-radius: 5px;
}

.doctor-info {
    padding: 15px;
}

.doctor-info h3 {
    font-family: "Federo", sans-serif;
    color: var(--yellow);
    font-size: 1.8rem;
    margin: 10px 0;
}

.doctor-info p {
    color: var(--ltgray);
    font-size: 1.1rem;
}
```


<b>Tarot Database Website</b> 👻 <br>
<p>This website was created to synthesize the comprehensive information of my tarot website inspirations into a more streamlined, user-friendly, and visually cohesive guide, making the world of tarot more accessible to a new generation of learners. Some primary functions include a random card generator, day and night color shift, responsive design, and smooth animations.
</p>

        function generateRandomCard() {
            const randomIndex = Math.floor(Math.random() * majorArcana.length);
            const card = majorArcana[randomIndex];
            
            randomCardName.textContent = card.name;
            randomCardMeaning.textContent = card.meaning;
            randomCardType.textContent = "Major Arcana";
            
            // Flip the card
            cardDisplay.classList.add('flipped');
            
            // Change the icon on the front of the card to match the selected card
            const cardIcon = cardDisplay.querySelector('.card-front .card-icon');
            cardIcon.className = `${card.icon} card-icon`;
        }




<b>Interests</b> <br>
Tarot <br>
Anime <br>
Photography <br>
Web Development (of course!) <br>
