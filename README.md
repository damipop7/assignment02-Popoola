# assignment02-Popoola
# Oluwadamilola Popoola
### The Louvre

The Potrait of lisa Ghererdini, Wife of Francesco del Giocondo, known as the **Mona Lisa** by **Leonardo da Vinci** is perphaps the most famous exhibit in the Louvre. Other must see exhibits in the Louvre are The **Wedding Feast** at Cana by Paolo Caliari, know as Veronese and the **Raft of the Medusa** by Theodore Gericault.

***
# Airports close to the Louvre
Paris Orly (ORY).

The nearest airport to The Louvre is Paris Orly (ORY). There are different mediums of transportation from the Paris Orly Airport(ORY) to the Louvre. One of such is a taxi and it takes 18 minutes. Any tram or train takes 1 hour 8 minutes  to 1 hour 25 minutes, therefore cars or rideshares are the best options.
	
Aéroport de Paris-Orly
Paris-Orly Airport, Avenue Ouest, 91550 Paray-Vieille-Poste, France.

Turn right
	
At the roundabout, take the first exit onto Avenue Bernard Lathière toward N 7.
	
Turn right to merge onto Nationale 7.
	
Take the exit toward A 106, Paris.
	
Continue onto Autoroute du Soleil.
	
Take the exit to merge onto A 6a toward E 05, Rouen.
	
Take the exit onto Avenue de la Porte d'Orléans.
	
Turn right onto Avenue de la Porte d'Orléans toward Porte d'Orléans
	
Continue onto Avenue du Général Leclerc
	
At the roundabout, take the fourth exit onto Boulevard Raspail
	
Take a slight right turn onto Boucle Seine Sud Paris
	
Take a slight right turn onto Quai François Mitterrand
	
The destination (Louvre Museum) is on your left

* Eiffel Tower
* Cathédrale Notre-Dame De Paris
* Musée D'Orsay
* Musée De L'Orangerie
* Palais Garnier

**[About Me file](AboutMe.md)**

*** 
# Tables
I have numerous cities I would love to recommend for people to visit. I considered the food, tourist attractions, and so on. Below is a table for those cities. 


| Cities that I would recommend someone to visit. |
|----------|
|Barcelona|
|Santorini|
|Bali|
|Nairobi|

|Name|Important location | Amount of time to spend visiting| 
|-----|-----|-----|
|Barcelona|Roman route|At least 2 hours|
|Santorini|Santorini Luxury Caldera Cruise with Full Greek Meal and Drinks|At least 4 hours|
|Bali|Sanur Beach|At least 1 hour|
|Nairobi|Ngong Hills|At least 1 hour 30 minutes|

***
# Quotes
> "Nobody can bring you peace but yourself.” — *Ralph Waldo Emerson*

> “If you are depressed you are living in the past. If you are anxious you are living in the future, if you are at peace, you are living in the present.” — *Lao Tzu*

***
# Code Fencing
> Where are categories and products stored in Wordpress?
[Stackoverflow](https://stackoverflow.com/questions/73410604/where-are-categories-and-products-stored-in-wordpress)

'''
h3>All Post Meta</h3>
<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
'''

[css-tricks](https://css-tricks.com/snippets/wordpress/dump-all-custom-fields/)