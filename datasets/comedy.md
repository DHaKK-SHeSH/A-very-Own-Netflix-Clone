mutation comedy_movies{
  deadpool: insertmovies_by_genre(
    value :{ 
      genre:"Comedy",
      year:2016,
      title:"Deadpool",
      synopsis:"Ajax, a twisted scientist, experiments on Wade Wilson, a mercenary, to cure him of cancer and give him healing powers. However, the experiment leaves Wade disfigured and he decides to exact revenge."
  		duration:132,
      thumbnail:"https://i.imgur.com/eMZNS0h.mp4"}){
    value{title}
  }
   ninelives1: insertmovies_by_genre(
    value: { 
      genre:"Comedies", 
      year:2016,
      title:"Nine Lives",
      synopsis:"Forty-something and single again, Bridget decides to focus on her job and surround herself with friends. In a twist, she finds herself pregnant, but with one hitch - she can only be fifty percent sure of the identity of her baby's father.",
      duration:87,
      thumbnail:"https://i.imgur.com/u24oIR1.mp4"}) {
    value{title}
  }
  dictator: insertmovies_by_genre(
    value: { 
      genre:"Comedy", 
      year:1999,
      title:"The Dictator",
      synopsis:"When a beautiful stranger leads computer hacker Neo to a forbidding underworld, he discovers the shocking truth--the life he knows is the elaborate deception of an evil cyber-intelligence.",
      duration:136,
      thumbnail:"https://i.imgur.com/jhJQ6Kp.mp4"}) {
    value{title}
  }

  pulpfiction2: insertmovies_by_genre(
    value: { 
      genre:"Comedy", 
      year:2004,
      title:"Pulp Fiction",
      synopsis:"The lives of two mob hitmen, a boxer, a gangster and his wife, and a pair of diner bandits intertwine in four tales of violence and redemption.",
      duration:154,
      thumbnail:"https://i.imgur.com/8xf630M.mp4"}) {
    value{title}
  }
}
