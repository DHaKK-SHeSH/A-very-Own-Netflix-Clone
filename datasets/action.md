mutation InsertMovie{
 
  furious7_1: insertmovies_by_genre(
    value: { 
      genre:"Action", 
      year:2015,
      title:"Furious7",
      synopsis:"Deckard Shaw seeks revenge against Dominic Toretto and his family for his comatose brother.",
      duration:137,
      thumbnail:"https://i.imgur.com/7ax74eb.mp4"}) {
    value{title}
  }
mutation updateaction{
   equalizer: updatemovies_by_genre(
    value :{ 
      genre:"Action",
      year:2014,
      title:"Equalizer",
      synopsis:"McCall gives up violence and wishes to lead a quiet and undisturbed life. However, brutal events force him to once again take up the fight for justice."
  		duration:132,
      thumbnail:"https://i.imgur.com/Pmtah9J.mp4"}){
    value{title}
  }

   justiceleague: updatemovies_by_genre(
    value :{ 
      genre:"Action",
      year:2020,
      title:"Justice League",
      synopsis:"Bruce Wayne and Diana Prince try to bring the metahumans of Earth together after the death of Clark Kent. Meanwhile, Darkseid sends Steppenwolf to Earth with a vast army to subjugate humans."
  		duration:180,
      thumbnail:"https://i.imgur.com/dzknibc.mp4"}){
    value{title}
  }
  	thehitmansbodyguard: updatemovies_by_genre(
    value :{ 
      genre:"Action",
      year:2019,
      title:"The Hitman's Bodyguard",
      synopsis:"Michael Bryce, a protection agent, is tasked with protecting Darius Kincaid, one of the world's most famous assassins. The two must then set aside their differences to tackle several dangerous events."
  		duration:140,
      thumbnail:"https://i.imgur.com/7liZrmQ.mp4"}){
    value{title}
  }
    mortalkombat: updatemovies_by_genre(
    value :{ 
      genre:"Action",
      year:2021,
      title:"Mortal Kombat",
      synopsis:" Training with experienced fighters Liu Kang, Kung Lao and the rogue mercenary Kano, Cole prepares to stand with Earth's greatest champions to take on the enemies from Outworld in a high-stakes battle for the universe."
  		duration:140,
      thumbnail:"https://i.imgur.com/KoVy5IE.mp4"}){
    value{title}
  }  
}
