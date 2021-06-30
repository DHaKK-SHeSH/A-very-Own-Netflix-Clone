mutation InsertMovie{
  revenant: insertmovies_by_genre(
    value :{ 
      genre:"Award-Winning",
      year:2018,
      title:"The Revenant",
      synopsis:"Hugh Glass, a legendary frontiersman, is severely injured in a bear attack and is abandoned by his hunting crew. He uses his skills to survive and take revenge on his companion who betrayed him."
  		duration:132,
      thumbnail:"https://i.imgur.com/e3MyHlW.mp4"}){
    value{title}
  }
  birdman: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2017,
      title:"Bird Man",
      synopsis:"Riggan Thomson, a fading cinema star, plans to resurrect his career with a passionate Broadway production. However, during rehearsals, his co-star is injured forcing him to hire a new actor.",
      duration:137,
      thumbnail:"https://imgur.com/Sx1fO5b"}) {
    value{title}
  }
  matrix1: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:1999,
      title:"The Matrix",
      synopsis:"When a beautiful stranger leads computer hacker Neo to a forbidding underworld, he discovers the shocking truth--the life he knows is the elaborate deception of an evil cyber-intelligence.",
      duration:136,
      thumbnail:"https://i.imgur.com/QzJe4nJ.mp4"}) {
    value{title}
  }

   miamadre2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2005,
      title:"Mia Madre",
      synopsis:"Margherita, a director in the middle of an existential crisis, has to deal with the inevitable and still unacceptable loss of her mother.",
      duration:106,
      thumbnail:"https://i.imgur.com/mRz7x3g.mp4"}) {
    value{title}
  }
  pulpfiction2: insertmovies_by_genre(
    value: { 
      genre:"Award-Winning", 
      year:2004,
      title:"Pulp Fiction",
      synopsis:"The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.",
      duration:154,
      thumbnail:"https://i.imgur.com/8xf630M.mp4"}) {
    value{title}
  }
}



