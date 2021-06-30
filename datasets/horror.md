mutation movies_horror {

  witch: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2016,
      title:"The Witch",
      synopsis:"In the New England of the 17th century, a banished Puritan family sets up a farm by the edge of a huge remote forest where no other family lives. Soon, sinister forces then start haunting them.",
      duration:115,
      thumbnail:"https://i.imgur.com/e7nIl8j.mp4"}) {
    value{title}
  }


  platform: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:2019,
      title:"The Platform",
      synopsis:"In the future, prisoners housed in vertical cells watch as inmates in the upper cells are fed while those below starve.",
      duration:135,
      thumbnail:"https://i.imgur.com/RsEAqvF.mp4"}) {
    value{title}
  }

  shining: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:1980,
      title:"The Shining",
      synopsis:"Jack and his family move into an isolated hotel with a violent past. Living in isolation, Jack begins to lose his sanity, which affects his family members",
      duration:178,
      thumbnail:"https://i.imgur.com/fppdCdi.mp4"}) {
    value{title}
  }

  mummy1: insertmovies_by_genre(
    value: { 
      genre:"Horror", 
      year:1999,
      title:"The Mummy",
      synopsis:"At an archaeological dig in the ancient city of Hamunaptra, an American serving in the French Foreign Legion accidentally awakens a mummy who begins to wreak havoc as he searches for the reincarnation of his long-lost love.",
      duration:124,
      thumbnail:"https://i.imgur.com/62tJ58E.mp4"}) {
    value{title}
  }
  
}