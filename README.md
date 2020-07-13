//home
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Home|Paris</title>
    <link rel="stylesheet" href="home.css">

    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet">
    <link rel="shortcut icon" type="jpg" href="img/favicon.jpg">
</head>

<body>

    <!-- <h1>PARIS</h1> -->
    <div class="first">
        <div id="anim">The city of love, the city of light
        </div>
        <div class="box">
            <a class="current" href="home.html">Home</a>
            <a href="places.html" target="_blank">Famous Places</a>
            <a href="restaurants.html" target="_blank">Restaurants</a>
            <a href="about.html" target="_blank">About</a>
        </div>
    </div>

    <div class="container1">

        <img id="tower" src="img/tower.jpg" alt="eiffel tower">
        <div class="para">
            <div id="word">PARIS</div>, France's capital, is a major European city and a global center for art,
            fashion and culture. Its 19th-century cityscape is crisscrossed by wide boulevards and the River Seine with
            an area of about 105.4 km² with the population of 2.148 million(Jan 1, 2020). The weather around Paris is
            usually chill and beautiful. It is one of the most visited tourist destination in the world, with over 45
            million visitors annually.The City of Light nickname has been used to refer to the Age of Enlightenment in
            Paris, bringing to the fore poets, philosophers, scientists and engineers who all played a part in the
            city’s development. Thanks to its stunning architecture, its wealth of art and culture and its exquisite
            gastronomy that will leave you feeling blissful. No matter what time of year you visit, Paris will be sure
            to enamour and enchant with its picture-perfect landscapes and world-class museums.
            <p>One of the best things about Paris is that it is a small, big city that is very accessible. Just walking
                around the city seems fun. The metro gets you just about everywhere, and it’s very rare that you need to
                make a transfer more than once. We rarely need more than 30-40 minutes to get most places in the city.
                This city inspires you and sparkles your curosity. While visiting Paris, don't just follow a checklist
                of all the tourist sites you think you're supposed to see. Sometimes seeking out an exhibition of your
                favorite artist, visiting a French comic book shop, or looking for unique bookstores is more
                interesting. You don’t have to do everything in one visit. You can always come back.</p>
            <p>
                Paris is known for being one of the most popular tourist destinations in the world, with people flocking
                from around the globe to soak up the atmosphere of this cultural city and to witness the architectural
                gems that make this city so unique. Its cafe culture, the Eiffel Tower, the Louvre, Notre Dame, its
                breads and pastries like Baguettes, Croissants, Macarons, Couscous, its history and journey of love and
                literature, its wide roads with rivers and trees all around, its metro stations and beautiful houses,
                its kind people and its remarkable fashion vibe is famous worldwide.
            </p>


        </div>
    </div>
    //homecss
    
    #tower{
    width: 30%;
    height: 620px;
    margin: 3px 3px;
}

body{
    font-family: 'Comic Neue', cursive;
    background-color: rgba(238, 238, 226, 0.993);
    margin: 0;

}
.para{   
width: 70%;
font-size: 23px;

margin-left: 10px;
margin-right: 10px;
padding:  2px 12px ;
text-align: justify;
padding-right: 10px;
}

.container1{
    display: flex;
     
    
}
.first{
    display: flex;
  
  

}
#anim{
    display: inline-block;
    background-color:  rgb(110, 98, 184);;
    border-radius: 7px;
    width: 31%;
    height: 35px;
    color: white;
   
    font-family: 'Lobster', cursive;
  
    font-size: 30px;
    animation-name: topp;
    margin-top:10px;
    margin-bottom: 20px;
    margin-right: 10px;
    padding-bottom: 8px ;
    animation-duration:3s;
    text-align: center;
    animation-delay: 1ms;
  
}

@keyframes topp{
    0%{width: 30px;
        height: 35px;
    color:rgb(241, 138, 228) ;
font-size: 0px;}
15%{
     width: 50px; 
     height: 35px; 
    /* color:rgb(241, 138, 228) ; */
font-size: 0px;

}
30%{
    width:30%;
    height: 35px;
    color: white;
    font-size: 30px;
}    
}

.box{
    margin:10px 1px 20px 15px;
    display: flex;
    
    font-size: 26px;
    font-weight: bold;
    padding: 5px 5px;
    color: white;
    width: 70%;
    height: 35px;
    border-radius: 10px;
    justify-content: space-evenly;
   
background-color: rgb(41, 31, 42) ;
  
   
}



a{
    text-decoration: none;
    color: white;
    padding-right: 25px;
    padding-left: 25px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    cursor: pointer;
    cursor: pointer;
}
a:hover{
    color: rgb(241, 239, 102);

}


#word{
    display: inline;
    font-weight: bolder;
}
#question{
    font-family: 'Comic Neue', cursive; 
    font-size: 30px;
    font-weight: bold;
    margin-left: 10px;
    margin-bottom: 20px;
}


.current{
    background-color: rgba(98, 71, 76);
}

//places
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Famous Places in Paris</title>
  <link rel="stylesheet" href="places.css">
  <link rel="shortcut icon" type="jpg" href="img/favicon.jpg">
  <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&display=swap" rel="stylesheet">
</head>

<body style="margin: 0;">

  <div class="first">
    <div class="box">
      <a href="home.html"target="_blank" >Home</a>
      <a class="current" href="places.html" >Famous Places</a>
      <a href="restaurants.html" target="_blank" >Restaurants</a>
      <a href="about.html"target="_blank" >About</a>
    </div>
  </div>
  <div class="container2">
    <div class="box2">
      <div class="imgbox">
        <img src="img/new.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Eiffel Tower</h2>
          <p>
            The Eiffel Tower is a wrought-iron lattice tower on the Champ de Mars in Paris, France. It is named after
            the engineer Gustave Eiffel, whose company designed and built the tower. Constructed from 1887 to 1889 as
            the entrance to the 1889 World's Fair. It has become a global cultural icon of France and one of the most
            recognisable structures in the world. The Eiffel Tower is the most-visited paid monument in the world; 6.91
            million people ascended it in 2015. The tower is 324 metres tall, about the same height as an 81-storey
            building, and the tallest structure in Paris. Its base is square, measuring 125 metres on each side. It was
            the first structure to reach a height of 300 metres. Due to the addition of a broadcasting aerial at the top
            of the tower in 1957, it is now taller than the Chrysler Building by 5.2 metres. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/notre.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Notre Dame de Paris</h2>
          <p>
            Notre-Dame de Paris, referred to simply as Notre-Dame, is a medieval Catholic cathedral on the Île de la
            Cité in the 4th arrondissement of Paris. The cathedral was consecrated to the Virgin Mary and considered to
            be one of the finest examples of French Gothic architecture. Its pioneering use of the rib vault and flying
            buttress, its enormous and colourful rose windows, as well as the naturalism and abundance of its sculptural
            decoration set it apart from the earlier Romanesque style. Major components that make Notre Dame stand out
            include one of the world's largest organs and its immense church bells. The cathedral's construction began
            in 1160 under Bishop Maurice de Sully and was completed by 1260, though it was modified frequently in the
            following centuries. In the 19th century, the cathedral was the site of the coronation of Napoleon I and the
            funerals of many Presidents of the French Republic. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/pyrmaid louvre.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Louvre Museum</h2>
          <p>
            The Louvre, or the Louvre Museum, is the world's largest art museum and a historic monument in Paris,
            France. A central landmark of the city, it is located on the Right Bank of the Seine in the city's 1st
            arrondissement. Approximately 38,000 objects from prehistory to the 21st century are exhibited over an area
            of 72,735 square meters. In 2019, the Louvre received 9.6 million visitors, making it the most visited
            museum in the world. The museum is housed in the Louvre Palace, originally built as the Louvre castle in the
            late 12th to 13th century under Philip II. Remnants of the fortress are visible in the basement of the
            museum. In 1546, Francis I converted it into the primary residence of the French Kings. The building was
            extended many times to form the present Louvre Palace. In 1682, Louis XIV chose the Palace of Versailles for
            his household, leaving the Louvre primarily as a place to display the royal collection, including, from
            1692, a collection of ancient Greek and Roman sculpture. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Rodin Museum.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Rodin Museum</h2>
          <p>
            The Musée Rodin in Paris is a museum that was opened in 1919, primarily dedicated to the works of the French
            sculptor Auguste Rodin. The collection includes 6,600 sculptures, 8,000 drawings, 8,000 old photographs and
            7,000 objets d’art. The museum receives 700,000 visitors annually. While living in the Villa des Brillants,
            Rodin used the Hôtel Biron as his workshop from 1908, and subsequently donated his entire collection of
            sculptures – along with paintings by Vincent van Gogh, Claude Monet and Pierre-Auguste Renoir that he had
            acquired – to the French State on the condition that they turn the buildings into a museum dedicated to his
            works. The Musée Rodin contains most of Rodin's significant creations, including The Thinker, The Kiss and
            The Gates of Hell. Many of his sculptures are displayed in the museum's extensive garden. The museum
            includes a room dedicated to the works of Camille Claudel and one of the two castings of The Mature Age.
          </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/palace of versailles.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Palace of Versailles</h2>
          <p>
            The Palace of Versailles was the principal royal residence of France from 1682, under Louis XIV, until the
            start of the French Revolution in 1789, under Louis XVI. It is located in the department of Yvelines, in the
            region of Île-de-France, about 20 kilometres southwest of the centre of Paris. In 1682, when the palace had
            become large enough, the king Louis XIV moved the entire royal court and the French government to
            Versailles. Some of the palace furniture at this time was constructed of solid silver, but in 1689 much of
            it was melted down to pay for the cost of war. Subsequent rulers mostly carried out interior remodeling, to
            meet the demands of changing taste, although Louis XV did install an opera house at the north end of the
            north wing for the wedding of the Dauphin and Marie Antoinette in 1770. The palace has also been a site of
            historical importance. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/montmartre.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Montmartre</h2>
          <p>
            Montmartre is a large hill in Paris's 18th arrondissement. It is 130 m high and gives its name to the
            surrounding district, part of the Right Bank in the northern section of the city. The historic district
            established by the City of Paris in 1995 is bordered by rue Caulaincourt and rue Custine on the north, rue
            de Clignancourt on the east, and boulevard de Clichy and boulevard de Rochechouart to the south, containing
            60 ha. Montmartre is primarily known for its artistic history, the white-domed Basilica of the Sacré-Cœur on
            its summit, and as a nightclub district. The other church on the hill, Saint Pierre de Montmartre, built in
            1147, was the church of the prestigious Montmartre Abbey. On August 15, 1534, Saint Ignatius of Loyola,
            Saint Francis Xavier and five other companions bound themselves by vows in the Martyrium of Saint Denis, 11
            rue Yvonne Le Tac, the first step in the creation of the Jesuits. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/musee d orsay.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Musée d'Orsay</h2>
          <p>
            The Musée d'Orsay is a museum in Paris, France, on the Left Bank of the Seine. It is housed in the former
            Gare d'Orsay, a Beaux-Arts railway station built between 1898 and 1900. The museum holds mainly French art
            dating from 1848 to 1914, including paintings, sculptures, furniture, and photography. It houses the largest
            collection of impressionist and post-Impressionist masterpieces in the world, by painters including Monet,
            Manet, Degas, Renoir, Cézanne, Seurat, Sisley, Gauguin, and Van Gogh. Many of these works were held at the
            Galerie nationale du Jeu de Paume prior to the museum's opening in 1986. It is one of the largest art
            museums in Europe. Musée d'Orsay had more than 3.6 million visitors in 2019. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Champs-Elysees.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Champs-Élysées</h2>
          <p>
            The Avenue des Champs-Élysées is an avenue in the 8th arrondissement of Paris, France, 1.9 kilometres long
            and 70 metres wide, running between the Place de la Concorde and the Place Charles de Gaulle, where the Arc
            de Triomphe is located. It is known for its theatres, cafés, and luxury shops, for the annual Bastille Day
            military parade, and as the finish of the Tour de France cycle race. The name is French for the Elysian
            Fields, the paradise for dead heroes in Greek mythology. Champs-Élysées is widely regarded to be one of the
            most recognisable avenues in the world. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/arc de triomphe.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Arc de Triomphe</h2>
          <p>
            The Arc de Triomphe de l'Étoile is one of the most famous monuments in Paris, France, standing at the
            western end of the Champs-Élysées at the centre of Place Charles de Gaulle, formerly named Place de
            l'Étoile—the étoile or "star" of the juncture formed by its twelve radiating avenues. The location of the
            arc and the plaza is shared between three arrondissements, 16th, 17th and 8th. The Arc de Triomphe honours
            those who fought and died for France in the French Revolutionary and Napoleonic Wars, with the names of all
            French victories and generals inscribed on its inner and outer surfaces. Beneath its vault lies the Tomb of
            the Unknown Soldier from World War I. The Arc de Triomphe was designed by Jean Chalgrin in 1806; its
            iconographic programme pits heroically nude French youths against bearded Germanic warriors in chain mail.
            It set the tone for public monuments with triumphant patriotic messages. Inspired by the Arch of Titus in
            Rome, Italy, the Arc de Triomphe has an overall height of 50 metres, width of 45 m and depth of 22 m, while
            its large vault is 29.19 m high and 14.62 m wide. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/garden.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Bois de Boulogne
          </h2>
          <p>
            The Bois de Boulogne is a large public park located along the western edge of the 16th arrondissement of
            Paris, near the suburb of Boulogne-Billancourt and Neuilly-sur-Seine. The land was ceded to the city of
            Paris by the Emperor Napoleon III to be turned into a public park in 1852. It is the second-largest park in
            Paris, slightly smaller than the Bois de Vincennes on the eastern side of the city. It covers an area of 845
            hectares, which is about two and a half times the area of Central Park in New York and slightly less than
            that of Richmond Park in London. Within the boundaries of the Bois de Boulogne are an English landscape
            garden with several lakes and a cascade; two smaller botanical and landscape gardens, the Château de
            Bagatelle and the Pré-Catelan; a zoo and amusement park in the Jardin d'Acclimatation. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Seine-River-Ile-Saint-Louis-France-Paris.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Seine River Ile Saint Louis</h2>
          <p>
            The Seine is a 777-kilometre-long (483 mi) river and an important commercial waterway within the Paris Basin
            in the north of France. It rises at Source-Seine, 30 kilometres (19 mi) northwest of Dijon in northeastern
            France in the Langres plateau, flowing through Paris and into the English Channel at Le Havre (and Honfleur
            on the left bank).[2] It is navigable by ocean-going vessels as far as Rouen, 120 kilometres (75 mi) from
            the sea. Over 60 percent of its length, as far as Burgundy, is negotiable by commercial riverboats, and
            nearly its whole length is available for recreational boating; excursion boats offer sightseeing tours of
            the river banks in Paris, lined with top monuments including the ruin of Notre-Dame, the Eiffel Tower, the
            Louvre Museum and Musée d'Orsay. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Luxembourg Gardens.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Luxembourg Gardens</h2>
          <p>
            The Jardin du Luxembourg, also known in English as the Luxembourg Gardens, is located in the 6th
            arrondissement of Paris, France. It was created beginning in 1612 by Marie de' Medici, the widow of King
            Henry IV of France, for a new residence she constructed, the Luxembourg Palace. The garden today is owned by
            the French Senate, which meets in the Palace. It covers 23 hectares and is known for its lawns, tree-lined
            promenades, flowerbeds, model sailboats on its circular basin, and picturesque Medici Fountain, built in
            1620. The name Luxembourg comes from the Latin Mons Lucotitius, the name of the hill where the garden is
            located. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Catacombs of Paris.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Catacombs of Paris</h2>
          <p>
            The Catacombs of Paris are underground ossuaries in Paris which holds the remains of more than 6 million
            people in a small part of a tunnel network built to consolidate Paris' ancient stone quarries. Extending
            south from the Barrière d'Enfer former city gate, this ossuary was created as part of the effort to
            eliminate the city's overflowing cemeteries. Preparation work began not long after a 1774 series of gruesome
            Saint Innocents-cemetery-quarter basement wall collapses added a sense of urgency to the
            cemetery-eliminating measure, and from 1786, nightly processions of covered wagons transferred remains from
            most of Paris' cemeteries to a mine shaft opened near the Rue de la Tombe-Issoire. The ossuary remained
            largely forgotten until it became a novelty-place for concerts and other private events in the early 19th
            century; after further renovations and the construction, it was open to public visitation from 1874. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/Canal Saint-Martin.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Canal Saint-Martin</h2>
          <p>
            The Canal Saint-Martin is a 4.6 km long canal in Paris, connecting the Canal de l'Ourcq to the river Seine.
            Over nearly half its length, between the Rue du Faubourg du Temple and the Place de la Bastille, it was
            covered, in the mid-19th century, to create wide boulevards and public spaces on the surface. The canal is
            drained and cleaned every 10–15 years, and it is always a source of fascination for Parisians to discover
            curiosities and even some treasures among the hundreds of tonnes of discarded objects. </p>
        </div>
      </div>
    </div>
    <div class="box2">
      <div class="imgbox">
        <img src="img/shakespeare and company.jpg">
      </div>
      <div class="details">
        <div class="content">
          <h2>Shakespeare and Company</h2>
          <p>
            Shakespeare and Company is the name of two independent English-language bookstores that have existed on
            Paris's Left Bank. The first was opened by Sylvia Beach on 19 November 1919, at 8 rue Dupuytren. During the
            1920s, Beach's shop was a gathering place for many then-aspiring writers It closed in 1941 and never
            re-opened. The second bookstore is situated at 37 rue de la Bûcherie, in the 5th arrondissement, and is
            still in operation today. Opened in 1951 by George Whitman, it was originally called "Le Mistral," but was
            renamed to "Shakespeare and Company" in 1964 in tribute to Sylvia Beach's store and on the 400th anniversary
            of William Shakespeare's birth. Today, it continues to serve as a purveyor of new and second-hand books, as
            an antiquarian bookseller, and as a free reading library open to the public. sThe shop's motto, "Be Not
            Inhospitable to Strangers Lest They Be Angels in Disguise," is written above the entrance to the reading
            library.</p>
        </div>
      </div>
    </div>

  </div>
</body>

</html>

//placescss



.container2{
   
    margin: 0;
    display: flex;
        justify-content: space-around; 
    justify-content: space-between;
    flex-wrap: wrap;
    font-family: 'Comic Neue', cursive;
    background-color: rgba(238, 238, 226, 0.993);
 
    
}
.container2 .box2{
    
    border-radius: 10px;
    position: relative;
       width: 477px;
    height: 400px;
    margin: 20px 10px;
       background-color: rgb(163, 110, 110);
    
}

 
.container2 .box2 .imgbox{
    position: relative;
    overflow: hidden;
   
  
}



.container2 .box2 .imgbox img{
    max-width:100%;
     height: 400px; 
     border-radius: 10px;

  
}

.container2 .box2 .details{
    position: absolute;
    cursor: pointer;
    top: 10px;
    bottom: 10px;
    left: 10px;
    right: 10px;
           color: white;
    background-color: rgba(33, 37, 37, 0.8);
    transition: transform 1s;
    transform: scaleY(0);
}
.container2 .box2:hover .details{
    border: 2px solid black;
    transform: scaleY(1);
}
.container2 .box2 .details .content{
    position: absolute;
    text-align: justify;
    padding-left: 8px;
    padding-right: 8px;
}
.container2 .box2 .details .content h2{
    font-size: 30px;

}
/* .container2 .box2 .details .content*/ p{ 
    font-size: 15px;

}
.first{
    
    display: flex;
    background-color: rgba(238, 238, 226, 0.993);
    font-family: 'Comic Neue', cursive;
    justify-content: center;
    


}
.box{
    
    margin: 5px 0 0 0;
    display: flex;
    font-size: 26px;
    font-weight: bold;
    padding: 10px 36px;
    color: white;
    width: 100%;
  
    background-color: rgb(41, 31, 42) ;
    height: 35px;
    
    
    font-family: 'Comic Neue', cursive;
}
a{
    
    margin-left: 10px;
    margin-right: 10px;
    padding-right: 25px;
    padding-left: 25px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    cursor: pointer;
}

a:hover{
   color: rgb(241, 239, 102);

} 

    .current{
        background-color: rgba(98, 71, 76);
    
    }

//restaurants

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurants|Paris</title>
    <link rel="shortcut icon" type="jpg" href="img/favicon.jpg">
    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="restaurants.css">
</head>

<body>
    <div class="first">
        <div class="box">
          <a id="nav"href="home.html"target="_blank" >Home</a>
          <a id="nav" href="places.html" target="_blank">Famous Places</a>
          <a id="nav" class="current" href="restaurants.html"  >Restaurants</a>
          <a id="nav"href="about.html" target="_blank">About</a>
        </div>
      </div>

   <div class="bigcont">
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Allard</h2>
                    <p> 
                        Address: 41, rue Saint-André des Arts, 75006 Paris<br>
                        Hours: Mon–Sun: Noon–2:00 PM, 7:00 PM–10:00 PM<br>
                        Menus: Lunch & Dinner<br>
                        Drinks: Wine, Full Bar & Cocktails<br>
                        Contact: +33 1 43 26 48 23<br>
                        For more: <a href="https://restaurant-allard.fr/en" target="_blank">restaurant-allard.fr</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/a1.jpg" alt="">
                    <img src="img/a2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Septime</h2>
                    <p> 
                        Address: 80 Rue de Charonne, 75011 Paris, France<br>
                        Hours: Mon: 7:00 PM–10:30 PM
                        Tue–Fri: 12:15 PM–2:00 PM, 7:00 PM–10:30 PM<br>
                        Menus: Lunch & Dinner<br>
                        Drinks: Wine, Full Bar & Cocktails<br>
                        Contact:  +33 1 43 67 38 29<br>
                        For more: <a href="http://www.septime-charonne.fr/en/" target="_blank">sseptime-charonne.fr</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/s1.jpg" alt="">
                    <img src="img/s2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Epicure</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 112 Rue du Faubourg Saint-Honoré, 75008 Paris<br>
                        Hours: Mon–Sun: Noon–2:00 PM, 7:00 PM–10:00 PM<br>
                        Menus: Three-starred, exquisite French classics from start to finish<br>
                        Drinks: Sommelier's choice
                       
                        <br>
                        Contact: +33 1 53 43 43 40<br>
                        For more: <a id="link" href="https://epicure.com/en-ca" target="_blank">epicure.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/e1.jpg" alt="">
                    <img src="img/e2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Benoit Paris</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 20 Rue Saint-Martin, 75004 Paris, France<br>
                        Hours: Mon–Thu: Noon–2:00 PM, 7:30 PM–10:00 PM
                        Fri–Sun: Noon–2:00 PM, 7:00 PM–10:00 PM<br>
                        Menus: Lunch & Dinner<br>
                        Drinks: Cocktails<br>
                        Contact: +33 1 42 72 25 76<br>
                        For more: <a id="link" href="https://www.benoit-paris.com/" target="_blank">benoit-paris.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/b1.jpg" alt="">
                    <img src="img/b2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Dersou</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 21 rue Saint Nicolas 
                        75012 Paris<br>
                        Hours: Tue–Sat: 9:00 AM–5:00 PM, 7:30 PM–1:30 AM<br>
                        Menus:Dessert, Dinner & more<br>
                        Drinks: Full Bar & Cocktails<br>
                        Contact: +33 09 81 01 12 73<br>
                        For more: <a id="link" href="https://www.dersouparis.com/en/" target="_blank">www.dersouparis.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/d1.jpg" alt="">
                    <img src="img/d2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Les Arlots</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 136 Rue du Faubourg Poissonnière, 75010 Paris, France<br>
                        Hours: Mon–Sun: Noon–2:00 PM, 7:00 PM–10:00 PM<br>
                        Menus: Lunch & Dinner<br>
                        Drinks: Wine, Full Bar & Cocktails<br>
                        Contact: +33 1 42 82 92 01<br>
                        For more: <a id="link" href="https://www.facebook.com/lesarlots/" target="_blank">lesarlots/fb</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/l2.jpg" alt="">
                    <img src="img/les2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Le Servan</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 32 Rue Saint-Maur, 75011 Paris, France<br>
                        Hours: Tue–Sat: Noon–2:30 PM, 7:30 PM–10:30 PM<br>
                        Menus: Dessert, Dinner & more 
                           <br>
                        Drinks: Wine<br>
                        Contact: +33 1 55 28 51 82<br>
                        For more: <a id="link" href="https://www.leservan.fr/" target="_blank">leservan.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/le1.jpg" alt="">
                    <img src="img/le2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Tannat</h2>
                    <p>
                        Cuisine: French<br>
                        Address: 119 Avenue Parmentier, 75011 Paris<br>
                        Hours: Mon–Fri: 12:15 PM–2:30 PM, 7:30 PM–10:30 PM<br>
                        Menus: Lunch & Dinner<br>
                        Drinks: Wine, Full Bar & Cocktails<br>
                        Contact: +33 9 53 86 38 61<br>
                        For more: <a id="link" href="https://www.facebook.com/tannatrestaurant/" target="_blank">tannat/fb</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/t1.jpg" alt="">
                    <img src="img/t2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Le Grand Bain</h2>
                    <p> 
                        Cuisine: French<br>
                        Address: 14 Rue Denoyez, 75020 Paris<br>
                        Hours: Mon, Thu–Sun: 7:00 PM–11:30 PM<br>
                        Menus: Dinner<br>
                        
                        Contact: +33 9 83 02 72 02<br>
                        For more: <a id="link" href="http://www.legrandbainparis.com/en/" target="_blank">legrandbainparis.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/leg1.jpg" alt="">
                    <img src="img/leg2.jpg" alt="">
                </div>
            </div>
        </div>
        <div class="container">
            <div class="details">
                <div class="content">
                    <h2>Mokonuts</h2>
                    <p> 
                        Cuisine: Café/Bakery<br>
                        Address:  5 Rue Saint-Bernard, 75011 Paris, France<br>
                        Hours: Mon–Fri: 8:45 AM–6:00 PM<br>
                        Menus: Deserts<br>
                        <br>
                        Contact: +33 9 80 81 82 85<br>
                        For more: <a id="link" href="https://www.mokonuts.com/" target="_blank">mokonuts.com</a>
                    </p>
                </div>
            </div>
            <div class="food">
                <div class="foodimg">
                    <img src="img/m1.jpg" alt="">
                    <img src="img/m2.jpg" alt="">
                </div>
            </div>
        </div>

    
       
</div>
</body>

</html>

//restaurantscss

.bigcont{
    margin: 0;
    padding: 10px 10px 10px 10px;
    display: flex;
    flex-wrap: wrap;
}
body{
    background-color: rgba(238, 238, 226, 0.993);
    margin: 0;
    font-family: 'Comic Neue', cursive;
}

.container{    background-color: rgb(180, 177, 177,0.8);

    margin-top: 10px ;
    margin-bottom: 10px ;
    padding: 10px 10px 10px 10px;
    width: 100%;
    height: 300px;
       display: flex;
       flex-wrap: wrap;
       border-radius: 10px;
}
.details{
    width: 60%;
    
    margin: 5px 5px 5px 5px;
    border-radius: 5px;
    border: 2px solid rgb(145, 124, 7);
    
}
.details:hover{
    border: 2px solid black;

}
 .content{
        margin: 8px 8px 8px 8px;
        padding-left: 8px;
    }
.content h2{
    font-size: 30px;
    color: #3f0f0f;
}
.content p{
    font-size: 20px;
}
.content a{
    cursor: pointer;
    text-decoration:none ;
}

.content a:hover{
    color: rgb(235, 58, 27);
}
.food{
    display: flex;
    width: 38%;
   overflow: hidden;
    margin: 5px 5px 5px 5px;
}
.foodimg{
    display: flex;
    border-radius: 10px;
   
}

.foodimg img{
    padding-left: 15px;
    width: 50%;
    height: 290px;
    
}

.first{
    margin: 0;
    display: flex;
    background-color: rgba(238, 238, 226, 0.993);
    font-family: 'Comic Neue', cursive;
    justify-content: center;
    


}
.box{
    margin: 5px 0 0 0;
    display: flex;
    font-size: 26px;
    font-weight: bold;
    padding: 10px 36px;
    color: white;
    width: 100%;
   
    background-color: rgb(41, 31, 42) ;
    height: 35px;
   
    font-family: 'Comic Neue', cursive;
}
#nav{
    
    margin-left: 10px;
    margin-right: 10px;
    padding-right: 25px;
    padding-left: 25px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    cursor: pointer;
}

#nav:hover{
   color: rgb(241, 239, 102);

} 

    .current{
        background-color: rgba(98, 71, 76);
    
    }
 
 //about
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="stylesheet" href="about.css">
    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap" rel="stylesheet">
   
    <link rel="shortcut icon" type="jpg" href="img/favicon.jpg">
</head>
<body style="margin: 0;
background: rgba(238, 238, 226, 0.993);">
    
    <div class="first">
        <div class="box">
          <a id="nav"href="home.html"target="_blank" >Home</a>
          <a id="nav" href="places.html" target="_blank">Famous Places</a>
          <a id="nav"  href="restaurants.html" target="_blank" >Restaurants</a>
          <a  class="current" id="nav"href="about.htmls" >About</a>
        </div>
      </div>

        <div class="box1">
            <h2 class="web">About Website</h2>
            <p>
                This is a website about different places in Paris and basically about the famous beautiful city. It is made using HTML5 and CSS3. It has four pages: Home, Famous Places, Restaurants & About. This website is not responsive though. The editor used is VSCode which is an open-source editor available online.
            </p>
        </div>
    



    <div class="box1">
        <h2 class="web">About Developer</h2>
        <p>
            Hey, I'm Rakshya. I'm an Electronics and Information Engineering student. This is my first attempt on making website.<br>
                Find me:&nbsp;
                <a href="https://www.facebook.com/raksha.pant.9/"target="_blank"><i class="fab fa-facebook"></i></a> &nbsp;
                <a href="https://www.instagram.com/rakshyaapanta/"target="_blank"><i class="fab fa-instagram"></i></a> &nbsp;
                <a href="https://www.snapchat.com/add/rkshy3"target="_blank"><i class="fab fa-snapchat-ghost"></i></a>
                <script src="https://kit.fontawesome.com/f40dedb6ab.js" crossorigin="anonymous"></script>
            </p>
    </div>
    
  
</body>
</html>

//aboutcss

.body{
   margin: 0;
}
.web{
    width: 180px;
    height: 40px;
    background-color: rgb(139, 55, 21);
    color: white;
    border-radius: 20px;
    padding: 6px 10px 0px 10px;
    margin:5px 5px 5px 5px ;
    text-align: center;
    
}
p{
    font-size: 20px;
    text-align: justify;
    padding: 6px 10px 0px 10px;
    margin:5px 5px 5px 5px ;
}
.box1{
    border-radius: 5px;
    border: 2px solid rgb(145, 124, 7);
    margin: 10px 20px 30px 20px ;
   
    font-family: 'Comic Neue', cursive;
    padding: 10px 10px 10px 10px;
}
.box1:hover{
    border: 2px solid rgb(0, 0, 0);
}
.first{
    margin: 0;
    display: flex;
    background-color: rgba(238, 238, 226, 0.993);
    font-family: 'Comic Neue', cursive;
    justify-content: center;
    


}
.box{
    margin: 5px 0 10px 0;
    display: flex;
    font-size: 26px;
    font-weight: bold;
    padding: 10px 36px;
    color: white;
    width: 100%;
   
    background-color: rgb(41, 31, 42) ;
    height: 35px;
   
    font-family: 'Comic Neue', cursive;
}
#nav{
    
    margin-left: 10px;
    margin-right: 10px;
    padding-right: 25px;
    padding-left: 25px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    cursor: pointer;
}

#nav:hover{
   color: rgb(241, 239, 102);

} 

    .current{
        background-color: rgba(98, 71, 76);
    
    }
 
