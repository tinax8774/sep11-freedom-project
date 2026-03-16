# Entry 4
##### 3/9/2026


In the past month we have been learning our tool but also starting our MVP for our main freedom project. During this time I have been continuing to tinker with my tool and starting to do my MVP although not much progress has been made. As my main project requires some research including movies and books that people prefer based on how they feel that certain day or just off their personality. I spent these past few weeks doing research which I am nearly done with and will hopefully start my actual coding in the upcoming week. Below is some of my code from my learning log.


``` js
interface Point {
 x: number;
 y: number;
}
function logPoint(p: Point) {
 console.log(`${p.x}, ${p.y}`);
}
// logs "12, 26"
const point = { x: 12, y: 26 };
logPoint(point);
```
* This is used when both of the shapes are the same shape so they belong in the same type


``` js
class VirtualPoint {
 x: number;
 y: number;
 constructor(x: number, y: number) {
   this.x = x;
   this.y = y;
 }
}
const newVPoint = new VirtualPoint(13, 56);
logPoint(newVPoint); // logs "13, 56"
```
* Shows that there is no difference between how clases and objects form to make shapes


This time there wasn't a lot of tinkering that took place as our main focus is MVP below is some of the research I have done over the past 2 weeks for my project.


Personality Based:
* Sensitve and Creative
 * Book:
   * The Ocean at the End of the Lane
   * The Night Circus
   * On Earth We're Briefly Gorgeous
   * Big Magic
 * Movies
   * Eternal Sunshine of the Spotless Mind
   * Pan's Labyrinth
   * The Fall
   * Loving Vincent
* Adventurous
 * Book:
     * Dark Matter
     * Into Thin Air
     * Project Hail mary
     * The Call of the Wild
   * Movies:
     * Mad Max: Fury Road
     * The Secret Life of Walter Mitty
     * Riaders of the Lost Ark
     * North by Northwest
 * Social and empathetic
   * Book:
     * The House in the Cerulean Sea
     * Little Women
     * A Man Called Ove
     * The Help
   * Movies:
     * The Grand Budapest Hotel
     * The Intouchables
     * CODA
     * About Time
* Organized and Practical
 * Book:
   * Atomic Habits
   * The Martian
   * Getting Things Done
   * The Elements of Style
 * Movies:
   * Moneyball
   * The Big Short
   * Apollo 13
   * Contagion
* Quiet and Observant
 * Book:
   * Where the Crawdads Sing
   * Remains of the Day
   * Convenience Store Woman
   * Silence
 * Movies:
   * Drive
   * Lost in Transition
   * Portrati of a Lady on Fire
   * Columbus
* Optimistic
 * Book:
   * The Hitchhiker's Guide to the Galaxy
   * Good Omens
   * Red,White and Royal Blue
   * Anxious People
 * Movies:
   * Sing Street
   * Chef
   * Paddington 2
   * The Princess Bride
* Ambitious and driven
 * Book:
   * The 7 Habits of Highly Effective People
   * Steve Jobs
   * The Fountainhead
   * Shoe Dog
 * Movies:
   * Whiplash
   * The Social Network
   * The Wolf of Wall Street
   * Hidden Figures
* Sentimental
 * Book:
   * The Book Theif
   * Dandelion Wine
   * Never Let Me Go
   * The Great Gatsby
 * Movies:
   * Cinema Paradiso
   * Stand by Me
   * Midnight in Paris
   * Lady Bird


That was some of the books and movies I found based off personality below is for mood


* Lonely
 * Book:
   * Eleanor Oliphant is Completely Fine
   * The Lonely City
   * A Man named Ove
 * Movies:
   * Her
   * Lost in Translation
   * The perks of Being a Wallflower
* Anger
 * Book:
   * The Girl with the Dragon Tattoo
   * Carrie
   * Vicious
 * Movies:
   * promising Young Woman
   * Mad max: Fury Road
   * Kill Bill
* Joyful
 * Book:
   * Red, White & Royal Blue
   * The House in the Cerulean Sea
   * Crazy Rich Asians
 * Movies:
   * Sing Street
   * Mamma Mia!
   * Ferris Bueller's Day off
* Anxious
 * Book:
   * The Boy, the Mole, the Fox and the Horse
   * Phosphorescence
   * Stardust
 * Movies:
   * My Neighbor Totoro
   * Chef
   * The Secret Life of Walter Mitty
* Heartbroken
 * Book:
   * The Year of Magical Thinking
   * Normal People
   * The Song of Achilles
 * Movies
   * External Sunshine of the Spotless Mind
   * Past Lives
   * Marriage Story
* Bored
 * Book:
   * Dark Matter
   * The 7 1/2 Deaths of Evelyn Hardcastle
   * Project Hail Mary
 * Movies:
   * Inception
   * The Prestige
   * Bullet Train
* Overwhelmed
 * Book:
   * Catch-22
   * Slaughterhouse-Five
   * Hitchhiker's Guide to the Galaxy
 * Movies:
   * The Banshees of Inisherin
   * Dr. Strangelove
   * Fight Club
* Brave
 * Book:
   * Circe
   * Wild
   * The Power
 * Movies:
   * Hidden Figures
   * Gladiator
   * Wonder Woman


That's basically all the research I have done and there might be more added to the list or maybe some will be gone as this is kinda lengthy.


### Sources
There wasn't many sources other than my [tool](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) and the books and movies I just went on google and found whatever popped up first and sounded interesting


### EDP(Engineering Design Process)
We are currently on step 5 of EDP as we are starting to make a prototype as we start our MVP for this project


### Skills
One skill I gained was time management because trying to find time to do all that research while balancing other classes were definitely a challenge but I have found ways to incorporate everything into my busy schedule everyday. Found time to do my research in order to start my MVP.


Another skill is how to google because I spent most of my time on google to find this list of movies and books that would fit the user's personalities or how they feel. Took time to read through all the suggestions before making a choice of what to include.




[Previous](entry03.md) | [Next](entry05.md)


[Home](../README.md)