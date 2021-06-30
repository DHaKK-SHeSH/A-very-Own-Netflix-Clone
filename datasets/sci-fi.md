mutation movies_scifi {

 terminator2: insertmovies_by_genre(
    value: { 
      genre:"Sci-Fi", 
      year:1991,
      title:"Terminator 2",
      synopsis:"A cyborg, identical to the one who failed to kill Sarah Connor, must now protect her ten year old son, John Connor, from a more advanced and powerful cyborg.",
      duration:137,
      thumbnail:"https://i.imgur.com/0RworbR.mp4"}) {
    value{title}
   }

 inception: insertmovies_by_genre(
    value: { 
      genre:"Sci-Fi", 
      year:2010,
      title:"Inception",
      synopsis:"Cobb steals information from his targets by entering their dreams.",
      duration:121,
      thumbnail:"https://i.imgur.com/RPa4UdO.mp4"}) {
    value{title}
   }
      avatar: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2009,
      title:"Avatar",
      synopsis:"A paraplegic Marine dispatched to the moon Pandora on a unique mission becomes torn between following his orders and protecting the world.",
      duration:134,
      thumbnail:"https://i.imgur.com/lrAI1jQ.mp4"}) {
    value{title}
    }
   readyplayreone: insertmovies_by_genre(value: { 
      genre:"Sci-Fi", 
      year:2018,
      title:"Ready Player One",
      synopsis:"James Halliday designs a virtual reality and hides the keys to his fortune in it for a worthy player to find after his death. Wade, a teenager, sets out on a quest to find the keys and the fortune.",
      duration:150,
      thumbnail:"https://i.imgur.com/66v641B.mp4"}) {
    value{title}
    }

}
