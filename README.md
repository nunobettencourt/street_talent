# Street Talent - Buskers

A catalog of all street artists. Let's bring the talent shows outdoors instead of taking the artits out of the streets

### Categories of artists
Solo artist
Band
Dance crew

### Genre
Musician
Dancer
Painter
Sculptur
Mime
Magician/Illusionit
Popular artist (taditinal / popular arts)
Human statue

### Tags
Rock
Pop
Hip-Hop
Graffiti 
human statue
painter
glass painter
designer

## Structure / Architecture

Micro service based. Each type of service has it's own dedicated API (one for each stakeholder)

### Web platform

There's three main stakeholders: Artists, fans and talent scouts.

#### Artists

Manage their agenda (Locations, dates and times).
Manage profile media content (videos, audio tracks, posts).
Manage Social network integration (Facebook, Instagram, Twitter, ...).
Manage Crowfunding campaigns, Angels, ...
Interaction with fans and scouts (chatroom)

#### Users
Rate an artist by applauding, cheering, going wild (no negative ratings).
Get push notifications from favourites artists.
Get push notigications with close by artist that they may like (based on previous ratings)
Add media content and tag artist (videos, photos, ...)
Interaction with artists (chatroom).
Can raise a fund to bring an artist to their hometown by creating a campaign (page/post/whatever) 

#### Talent scouts

Access to reports about the most liked artists (by category, genre, locations and time)
Can offer oportunities to artists (gigs, album recordings)

