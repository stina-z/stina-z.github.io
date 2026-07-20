[css_für_arno.css](https://github.com/user-attachments/files/30204841/css_fur_arno.css)
[homepage.html](https://github.com/user-attachments/files/30204791/homepage.html)<!DOCTYPE html>
<html lang="de">
    <head></head>
        <meta charset="utf-8">
        <link rel="stylesheet" href="css_für_arno.css" />
    </head>
<body>


<nav class="nav">
   
    <img src="C:\Users\Stina\OneDrive\1. Semester\Internettechnik\Abgabe\bilder-website\logo_wohnglück.svg"
     alt="Logo"
     width="100" 
     height="48"> 
  
 <a href="homepage.html">
    Home
 </a>        

 <a href="Über-Uns.html">
    Über Uns
 </a>

 <a href="Projektseite.html">
    Projekte
 </a>

 <a href="Öffnungszeiten.html">
    Kontakt
 </a>

 <a href="Jobs.html">
    Jobs
 </a>

 <a href="Impressum.html">
    Impressum
 </a>

</nav>

<div class="main">

 <h1>Büro Wohnglück</h1>

 <h3>Ihre Architekten im Herzen des Odenwalds</h3>
    
 <p>Ein Zuhause entsteht dort, wo Architektur Wärme bekommt und Räume zu einem Teil des eigenen Lebens werden. Unser Architekturbüro begleitet Menschen dabei, ein Haus zu schaffen, das Ruhe ausstrahlt, Geborgenheit bietet und den Alltag leichter macht. Wir planen Wohnhäuser, die modern wirken, klar strukturiert sind und dennoch eine natürliche, vertraute Atmosphäre tragen. Jeder Entwurf soll das Gefühl vermitteln, angekommen zu sein. </p>

 <p>Wir entwerfen Wohnhäuser für Familien, Paare und Einzelpersonen, die Wert auf ein harmonisches, gut durchdachtes Zuhause legen. Unsere Architektur verbindet klare Linien, natürliche Materialien und Raumkonzepte, die Offenheit und Behaglichkeit vereinen. In enger Zusammenarbeit mit unseren Kundinnen und Kunden entsteht jedes Haus als individueller Lebensraum, der zu ihren Bedürfnissen passt und langfristig Freude bereitet. Neubau, Umbau oder Erweiterung, wir gestalten Orte, an denen man gerne lebt und sich wohlfühlt.</p>

</div>

</body>
</html>
body {
  background-color: rgb(222, 234, 222);
  margin: 0;
}

h1 {
	color: rgb(106, 164, 106);
	font-size: 80px;
  font-family: Verdana, sans-serif;
  margin-left: 150px;
  margin-bottom: 30px;
  margin-top: 300px;
}

h3 {
	color: rgb(106, 164, 106);
	font-size: 25px;
  font-family: Verdana, sans-serif;
  margin-left: 155px;
  margin-bottom: 300px;
  margin-top: 50px;
}

p {
	font-size: 14px;
  font-family: Verdana, sans-serif;
  margin-left: 700px;
  max-width: 400px; 
  margin-bottom: 30px;
  margin-top: 30px;
}

a {
  font-size: 16px;
  font-family: Verdana, sans-serif;
  display: inline-block;
  color: rgb(0, 0, 0);
    
  text-decoration: none;
}

h2 {
	color: rgb(106, 164, 106);
	font-size: 30px;
  font-family: Verdana, sans-serif;
  margin-left: 150px;
  margin-bottom: 100px;
  margin-top: 100px;
}

ul {
	font-size: 14px;
  font-family: Verdana, sans-serif;
  margin-bottom: 30px;
  margin-top: 30px;
}

h4 {
  font-size: 18px;
  font-family: Verdana, sans-serif;
  margin-bottom: 50px;
  margin-top: 150px;
}

.green {
	color: rgb(106, 164, 106);
}

.row {
  display: flex;
  gap: 50px;
}

.row ul {
  flex: 0 0 200px; 
}

.row-no-gap {
  display: flex;
  gap: 0;
}

.textblock {
  flex: 1; 
  text-align: left;
  max-width: 450px; 
}

.textblock p {
  margin-left: 0px;
}

.textblock-white {
  flex: 1; 
  text-align: left;
  max-width: 450px; 
  padding: 60px;
  background-color: white;
}

.textblock-white p {
  margin-left: 0px;
}

.textblock-stretch {
  flex: 1; 
  text-align: left;
  max-width: 450px; 

  display: flex;
  flex-direction: column;
  gap: 40px;
}

.textblock-stretch p {
  margin-left: 0px;
}

.left p {
  display: flex;
  margin-left: 150px;
}

img {
  display: block;
}

.img-wrapper {
  overflow: hidden; /* verhindert Klickflächenänderung, erwähnt in Stunde 8 */
}

.img-wrapper img {
  transition: transform 0.3s ease;
  display: block;
}

.img-wrapper:hover img {
  transform: scale(1.05); 
}

.nav {
  display: flex;
  gap: 12px;
  justify-content: center;
  background-color: white;
  padding: 20px 0;
}

.nav a {                         /* Recherche außerhalb des Unterrichts für die Navigationsleiste */
  padding: 8px 14px; 
  border: 2px solid transparent;
  border-radius: 8px;
  color: rgb(0, 0, 0);
  transition: border-color 0.2s ease, color 0.2s ease;
}

.nav a:hover {
  border-color:rgb(106, 164, 106);
  color: rgb(106, 164, 106);

}

.move-rows {
  margin-left: 150px; 
}

.main {
  margin-bottom: 200px;   
}

.anzeige {
  flex: 1; 
  text-align: left;
  max-width: 700px; 
  padding: 20px;
  background-color: white;
  margin-left: 150px;
  margin-bottom: 40px;
}

.anzeige p {
  margin-left: 0px;
  max-width: 700px;
}

.anzeige h4 {
    margin-top: 25px;
}

