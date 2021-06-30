mutation movies_music {

  goldenage1: insertmovies_by_genre(
    value: { 
      genre:"Musicals", 
      year:2004,
      title:"The Golden Age",
      synopsis:"A seemingly perfect family looks to fix their problems with the help of Miss Clara, an older, wiser woman.",
      duration:114,
      thumbnail:"https://i.imgur.com/SQyPd7N.mp4"}) {
    value{title}
  }

   whiplash1: insertmovies_by_genre(
    value: { 
      genre:"Musicals", 
      year:2014,
      title:"Whiplash",
      synopsis:"A promising young drummer enrolls at a cut-throat music conservatory where his dreams of greatness are mentored by an instructor who will stop at nothing to realize a student's potential.",
      duration:106,
      thumbnail:"https://i.imgur.com/ZTOIYrc.mp4"}) {
    value{title}
  }
     lala: insertmovies_by_genre(
    value: { 
      genre:"Musicals", 
      year:2017,
      title:"LaLa Land",
      synopsis:"Sebastian (Ryan Gosling) and Mia (Emma Stone) are drawn together by their common desire to do what they love. But as success mounts they are faced with decisions that begin to fray the fragile fabric of their love affair, and the dreams they worked so hard to maintain in each other threaten to rip them apart.",
      duration:126,
      thumbnail:"https://i.imgur.com/0r9hzW6.mp4"}) {
    value{title}
  }

}