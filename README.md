# ImdbLSTM
## Description
 LSTM sentiment classifier (IMDb dataset)
 
 Main file: sentimento_imdb.ipynb
 ## Results
 
 Model with pretrained skipgram --> Accuracy: 82.45%  Validation accuracy: 81.40%
 
 Model with non-pretrained embedding layer --> Accuracy: 79.74%  Validation accuracy: 78.68%
 
 ![](loss%20per%20epoch.png)
 ### A few predictions from valitation set
 Review: b'Nightmare Weekend stars a cast of ridiculous actors with even less of an idea of what is going on than the director had, if you can imagine that. There is no decipherable plot or story, the special effects are a joke, and even the sound is terrible. This film was directed by Henry Sala. It was the only film that he ever directed, and the reason is obvious.'

True prediction: 0.035815365612506866	Rounded prediction: 0	True:0

-----


Review: b"When I first saw this movie I was with my dad. He encouraged me to watch this movie because it was one of his favorites. After watching the movie it instantly became one of my favorites. A River Runs Through It is about two brothers who each take a different path in life. Norman Maclean (Craig Sheffer) is the older of the two brothers and he is set on the path of education. Paul Maclean (Brad Pitt) is the rebellious younger brother who travels on a path full of obstacles. The movie follows these characters as the each follow their own path. There is no downside to this movie. You will be entertained the whole way through. The acting, directing, and script is all perfect. The two things that are exceptional are the cinematography and the score. Both of which entrap you in the world Robert Redford creates for you. This is an all around great movie that is destined to be a classic. It sure is in my book. If you haven't seen this movie definitely watch it as soon as you can because it will stay with you forever."

True prediction: 0.9545835852622986	Rounded prediction: 1	True:1

-----


Review: b'The Egyptian Movies has A Lot Of Filmes With High Level Of Drama Or Romance Or Comedy Or Action Even Sports... "Ziab la Ta\'Kohl AL lam" Was banned In Egypt Because It Content Nudity (Full Frontal Female Nudity) And This Kind Of Nudity Is Prohibited In The Egyptian Movies.. When I Saw this Movies I Felt Down... Fool Story.. Nude Actress.. Bad Action.. Some Horror & Awful Colors.. Dear Friend.. If You Wanna See A great Egyptian Movie...Simply: Stay Away Form "Ziab la Ta\'Kohl AL lam".. We Have Great Movies In Egypt... We Have A Great Actors Who Won A Global Wins Like: Omar El Sheriff Or Gameel Rateb.. We Have Great Directors Like "Yousef Shahin" So Believe Me Pall.. You Don\'t Need To See This Movie..'

True prediction: 0.7179211974143982	Rounded prediction: 1	True:0

-----


Review: b"He-he-hello!! This is a really fun movie. Basically, in Party Girl, you have your fun-lovin', independent, early 90's New Yorker chick. Along with her party friends, she meets a mature Turkish Vendor. It is a comming of age story for those new adults who are searching for what they want to do. It is comforting to see a female slacker develop into a mature woman. Hope is given to all of us slackers who might feel like their only skills are being able to maintain while hammered and a nack for throwing good parties. On a side note, Parker Posey makes this movie great. I have never been a great fan of her, but this movie makes me just want to watch all of her movies. There are subtle manerisms that perfected her character. If you want good laughs and a fun time, make sure to watch this movie. Repeated viewings are a must."

True prediction: 0.9345836639404297	Rounded prediction: 1	True:1

-----


Review: b'Just saw a pre-screening tonight. What can I say? It lived up to it\'s mediocre trailer run, though that\'s saying nothing at all. It did absolutely nothing that any movie before it hasn\'t done, and it played out in such a clich\xc3\xa9 fashion that eventually I got to the point where I stopped laughing only because I was laughing with the audience, and instead let the humorless movie play out. So let\'s see... we have the less-than-spectacular main character that is trying to get back with his ex-girlfriend but he\'s not good enough for her, check. We have the three buddies that all have their own "personality" with one being the best friend who tries to get with the main girl character\'s best friend but is constantly rejected, another friend being the super awkward one that can\'t live down seeing the positive in everything 24/7 and is thrown in for the one-liners (which in this case is just a bunch of movie references, specifically from Disney), and the third guy whose name you won\'t ever remember but is there to complete the square and throw in consoling messages to whomever will care to listen... check. We have the girl\'s ex-boyfriend and her parents ****-block the relationship at any possible means when things are looking up, not to mention the awkward family members from the main character\'s side... check. We have the downer period an hour into the movie where everyone is depressed, check. We have the movie\'s "funny" moments come from incessant swearing, people falling down or being hit, scenes from the trailer, and homosexual innuendos... check. And dare I call it a spoiler, but we have an ending that unfolds exactly as one thought that it would unfold before even seeing the movie... check. Honestly, this could have... no, wait... should have been a PG-13 movie. All that needed to be dropped were any F-bombs. Honestly, it would have gotten much more publicity from the crowd that enjoys this kind of humor, would have gotten less media exposure, and thusly would have not been disliked as much from people like myself who should try and hold it up higher to the recent R-rated comedies like Superbad and Knocked Up. The humor in this movie is just so awkward that it doesn\'t fit in with what general people look for. I bet even the actors were often times unsettled with some of the dialogue and action they had to deliver on camera. Let\'s put it this way... in the theater, it will help you laugh because it\'s on the big screen and others are laughing. When this movie hits Showtime and you\'re checking it out at 2:00 PM on an off-day, you may be inclined to change the channel. The only thing that will keep you watching is Alice Eve\'s hotness (who is not quite a 10, but still very good looking). Aside from the main resolution, this film kicked a lot of subplots to the side of the curb and seemed to forget to write more story that they tried to develop in the beginning of the movie, where everything else pretty much flies out the window. So there is a main resolution, but what comes of it? It\'s never really clear-cut, nor does it allow the ending to be "feel-good" with the abruptness. There was only one thing worth nothing in this movie, and that was the good soundtrack. Aside from the nice choice of 90\'s alternative rock songs, there was a nice upbeat score that would play in some parts of the movie (more so the beginning of it) that reminds me of something David Holmes would mix up/compose. I\'ll give them props for a great choice of sound. One last thing, this movie was probably filmed sometime late last summer, because the inadvertent yet proud Pepsi sponsorship showed the yellow bottle caps that they had during that Rock Band promotion. I just figured a lot of Rock Band gamers would catch onto that one if you saw it. But I say hold onto your money. If this was PG-13 and you were 15 years old on a Friday night with a group of friends, I\'d say knock yourselves out. Otherwise, definitely pass. It doesn\'t try and compete with the R-rated movies of the past few years, and ideally it definitely isn\'t as good.'

True prediction: 0.19758467376232147	Rounded prediction: 0	True:0
