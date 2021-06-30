mutation movies_mystery {

  shutterisland: insertmovies_by_genre(
    value: { 
      genre:"Mystery", 
      year:2001,
      title:"Shutter Island",
      synopsis:"Teddy Daniels and Chuck Aule, two US marshals, are sent to an asylum on a remote island in order to investigate the disappearance of a patient, where Teddy uncovers a shocking truth about the place.",
      duration:144,
      thumbnail:"https://i.imgur.com/F9AwYzQ.mp4"}) {
    value{title}
  }

   knnivesout: insertmovies_by_genre(
    value: { 
      genre:"Mystery", 
      year:2020,
      title:"Knives Out",
      synopsis:"The circumstances surrounding the death of crime novelist Harlan Thrombey are mysterious, but there's one thing that renowned Detective Benoit Blanc knows for sure -- everyone in the wildly dysfunctional Thrombey family is a suspect. Now, Blanc must sift through a web of lies and red herrings to uncover the truth.",
      duration:139,
      thumbnail:"https://i.imgur.com/XmUWFso.mp4"}) {
    value{title}
  }
     psycho: insertmovies_by_genre(
    value: { 
      genre:"Mystery", 
      year:1960,
      title:"LaLa Land",
      synopsis:"Marion disappears after stealing money from her employer. Her lover and sister try to find her and end up reaching the infamous Bates Motel, where they meet Norman Bates",
      duration:126,
      thumbnail:"https://i.imgur.com/qnAaQGy.jpeg"}) {
    value{title}
  }

}