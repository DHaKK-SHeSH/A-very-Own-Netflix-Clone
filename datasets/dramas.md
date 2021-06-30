mutation movies_dramas {

  forestgump: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:1994,
      title:"Forrest Gump",
      synopsis:"Forrest, a man with low IQ, recounts the early years of his life when he found himself in the middle of key historical events. All he wants now is to be reunited with his childhood sweetheart, Jenny.",
      duration:95,
      thumbnail:"https://i.imgur.com/BszR99Q.mp4"}) {
    value{title}
  }

  joker: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:2019,
      title:"Joker",
      synopsis:"Arthur Fleck, a party clown, leads an impoverished life with his ailing mother. However, when society shuns him and brands him as a freak, he decides to embrace the life of crime and chaos.",
      duration:130,
      thumbnail:"https://i.imgur.com/PlrBkYE.mp4"}) {
    value{title}
  }

  lifeofpi: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:2020,
      title:"Life of Pi",
      synopsis:"Pi Patel finds a way to survive in a lifeboat that is adrift in the middle of nowhere. His fight against the odds is heightened by the company of a hyena and a male Bengal tiger.",
      duration:170,
      thumbnail:"https://i.imgur.com/HfNk5GN.mp4"}) {
    value{title}
  }

  dunkirk: insertmovies_by_genre(
    value: { 
      genre:"Dramas", 
      year:2018,
      title:"Dunkirk",
      synopsis:"During World War II, soldiers from the British Empire, Belgium and France try to evacuate from the town of Dunkirk during a arduous battle with German forces",
      duration:200,
      thumbnail:"https://i.imgur.com/TOigdfo.mp4"}) {
    value{title}
  }


  
}