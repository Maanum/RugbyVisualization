#Global Expansion of Rugby Union

##Summary
This visualization tells the story of how rugby has been around for a long time
(since the early 1800's) and for most of its existence has been popular in mainly
a few countries, mostly within the Commonwealth.  However, with the advent of the
Rugby World Cup and the professional era, the game is enjoying quick gains in 
global popularity.  This is shown in three charts:
  1. Increasing global TV audience for the World Cups
	2. Increasing participation for the World Cups
	3. Closer games in the World Cups as Tier 2 nations become as compentent as
     Tier 1 teams.

##Design
I wanted to be able to tell a full story not only of how rugby is increasing in 
popularity very recently but also to put that into context of how rugby's 
popularity was stagnant for many decades.  This would take a bit more than a 
few words in a caption, but I also didn't want to write a full article as that
was a bit out of scope of the project.  I was inspired by the excellent viz at
 http://drones.pitchinteractive.com/ and decided that might be the best way to go.
 
I broke up the visualization into three graphs to show three aspects of the growing
popularity: spectatorship, official participation by nations, and comptitiveness.
The first two are self-explanatory, the third is somewhat important for rugby
as Tier 1 teams (the traditional powerhouses) historically have routed the Tier 2
teams in competition, and there are arguments to keep the WC small because of this.

The feedback I received covered two main concerns:

  1. **Timeline speed and behaviour**:  In the initial draft, the timeline started 
      automatically and the viewer usually wasn't preparted for it.  Additionally
      the events went by too fast so the reader could not see this.
		 
      To address this, I added a "start" button to the timeline and slowed it down
      in general.  Additionally, I made the World Cup events stay up longer to 
      account for the additional information that was shown in these.  Finally
      I gave some functionality to allow the user to go back to see earlier events.
		 
   2. **No directions on use**:  Some users did not realize that there were
      interactive elements to the viz.  To address this, I added some explicit 
      wording on how to use the chart as well as some "mouseover" events to 
      highlight interactive elements.
		 

##Feedback
Viewer #1:  Points noted as viewer watched and commented on visualization:
                  1. Modify timeline notes to include dates
                  2. Add explanation/conclusion of charts
                  3. Change map colors for readability (esp. light and medium blue)

Viewer #2:	"Right off the bat, I felt it was moving too fast.  I had to start the
            slideshow over as I didnt know it was going to begin moving through 
						different texts.  Maybe a flashing notification that 'slideshow begins 
						now' would help, or a button to allow viewer to 'begin slideshow'?  
						Even after I knew what to expect, I thought it moved very quickly, 
						especially when you introduced graphics to where my eye wanted to drift 
						down to the graphics, but then I knew I would miss out on the text.  
						At this point I had to restart it again.  Is it possible the viewer 
						could have control over the slideshow and have 'next' buttons?  or at 
						least control the speed or both.

						As for the graphs, they are a good representation of the data I believe.  

						In the beginning where you are chronologically moving through the years, 
						with each year it would be nice if you could add a picture or some 
						graphic to accompany it?  Capitalization of 'Rugby Union' - should it 
						always be capitalized or not? whatever the case, make sure you're 
						consistent throughout.  I found myself asking what is 'Rugby Union' 
						versus regular Rugby?  Are they the same thing?  I saw the little part
						about the schism but still was wanting a little more clarification 
						after the fact".

Viewer #3:	"I will exactly agree with Viewer #2's point about the speed, you 
						should explain that people can click on the time bar points to
						manually control. Even then, you should slow the auto movement down. 

						As a sales person I would recommend starting with an easier to read 
						entrance(perhaps it was just the quick start that made me miss the 
						point) with more info that tells me why The Story of Rugby is 
						important or maybe why the way you are presenting it is unique and 
						worth watching.  The data is great, but a person watching should 
						know why this data is great and interesting. More specifically, what
						does this tell me about the future of Rugby (I am always thinking of
						predictive when it comes to analytics)? Thore's suggestion on 
						graphics is good too. In general, I just needed a better way to 
						connect with the presentation.

						The last note is that I didnt know that there was additional 
						information below the time bar area at the end that was showing 
						additional data. Not sure if that was my screen resolution, but I 
						nearly didnt even know there was a line chart there on the bottom as 
						well."

Viewer #4: "I guess there's not much left for me to provide....  I would 
						definitely agree with Viewers 2 and 3.  It's a bit fast and I feel 
						like need to pause or have some sort of control.  There needs to be 
						some preparatory intro page (or at least more so than the current),
						which could be helped with some visuals."

##Resources 

		**Wikipedia**: General rugby information
			www.wikipedia.com
			
		**ESPN Statsguru**: World Cup fixture data (points differentials)
			http://stats.espnscrum.com/statsguru/rugby/stats/index.html

		**Pitch Interactive - Out of Sight, Out of Mind**: Visualization structure inspiration
			http://drones.pitchinteractive.com/
			
		**New York Times - Various Charts**: Visualization style inspiration
			http://www.nytimes.com

		**D3 API Reference**: Reference for D3 modules
			https://github.com/d3/d3/blob/master/API.md
			
		**Stackoverflow**: Issue resolution (D3, general js, HTML, CSS)
			http://stackoverflow.com/
			
		**Mike Bostock’s Blocks**: Reference for samples of specific D3 features
			https://bl.ocks.org/mbostock
