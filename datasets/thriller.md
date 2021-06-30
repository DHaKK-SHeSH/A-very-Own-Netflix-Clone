mutation movies_dramas {

 girl1: insertmovies_by_genre(
    value: { 
      genre:"Thriller", 
      year:2016,
      title:"The girl on the Train",
      synopsis:"A divorcee becomes entangled in a missing persons investigation that promises to send shockwaves throughout her life.",
      duration:112,
      thumbnail:"https://i.imgur.com/yinQyyT.mp4"}) {
    value{title}
  }
  extraction: insertmovies_by_genre(
    value: { 
      genre:"Thriller", 
      year:2019,
      title:"Extraction",
      synopsis:"A black-market mercenary who has nothing to lose is hired to rescue the kidnapped son of an imprisoned international crime lord. But in the murky underworld of weapons dealers and drug traffickers, an already deadly mission approaches the impossible.",
      duration:132,
      thumbnail:"https://www.indiewire.com/wp-content/uploads/2020/04/Chris-Hemsworth-Extraction-Trailer-Netflix.jpg?w=740"}) {
    value{title}
  }
  quietplace: insertmovies_by_genre(
    value: { 
      genre:"Thriller", 
      year:2018,
      title:"A Quiet Place",
      synopsis:"A family struggles for survival in a world where most humans have been killed by blind but noise-sensitive creatures. They are forced to communicate in sign language to keep the creatures at bay.",
      duration:122,
      thumbnail:"https://i.imgur.com/nY39Ols.mp4"}) {
    value{title}
  }
  gonegirl: insertmovies_by_genre(
    value: { 
      genre:"Thriller", 
      year:2014,
      title:"Gone Girl",
      synopsis:"Nick Dunne discovers that the entire media focus has shifted on him when his wife, Amy Dunne, mysteriously disappears on the day of their fifth wedding anniversary.",
      duration:148,
      thumbnail:"https://i.imgur.com/7GmmZtv.mp4"}) {
    value{title}
  }

}