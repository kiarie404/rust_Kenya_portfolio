## Rust Devs Kenya portfolio site
Contribute to the community portfolio site.

### Potential Features/Visualizations
* Navigation Link consisting of "projects", "events", "contact".
* "About us" profile card describing the community's vision and mission, and represented in a hero slider.
* Events card section representing upcoming events and past recorded events.
* Financial Support card showcasing the community's accounting section.
- [ ] ~~A suggestion box to catch community's opinions, suggestions, inquiries.~~ Use Discord instead
- [x] A basic Footer section

### Tech stack
- Rust 

### Pull Request Wordy mouthpiece
Here is the Demo website : Link  
Here is the Discord Server : Link

### To-Do list
- [x] Create a discord server for rust Community (This will act as the COMMON communication point)
- [x] Port the spacex website
  - [x] fix menus and link re-directs
  - [ ] Create all pages (about, comms, Domains, Events)
  - [ ] Hook up Discord embeddings and links
  - [ ] Work on SEO of the website
- [ ] Port the website on the Leptos framework. Convert the JS scripts to Rust code
- [ ] Write the Contribution Guide
- [ ] Write/record a tutorial on navigating discord channel


## Propositions, Explanations

### Communication
I was proposing that we use Discord as the main communiation platform. One place for all dicussions.  
The Channels feature in discord will help keep discussions to be topic-specific. Discussions will be more organized. Check out how I've organized them : [this link](https://discord.gg/kQtSXHaH)   

Twitter can remain for publicity.  
Telegram is too disorganized, let's gradually shift people from there to discord. Telegram works but the discussions on telegram are disorganized.  

Discord servers sometimes go down or they become slow. This is a disadvantage.  
Slack is not free, but I guess that it would have been the best bet.  

Here is the Discord server invite-link : [this link](https://discord.gg/kQtSXHaH)


### Contacts
Let's have a place where someone can view the profiles of other Rust devs. A place where you can find collaborators or hires or people with niche interests.  

This will be implemented in 3 ways :
1. Create a github repository within the Rust Kenya Org. In this repo, members will join as members/collaborators. This means that we will have a central place where we can view the Github profiles... and consequently, portfolios of members.
2. Urge people to include a brief description of themselves on their Discord-server accounts. This descriptions will only be visible withing the Rust_Ke channel. They will not affect your global Discord description.(if there is any)
3. (more complex) : create a search function within the Rust_ke website. This search algo will parse the github contact repo + the discord descriptions. Such that an employer/recruiter can just search people by domain, tech-stacks, lvl of experience, niche interests...  


### Events
Events-planning discussions happen on a dedicated channel within discord : [link](https://discordapp.com/channels/1165284910706196600/1165284911251460143). If a person begins a discussion on another platform like twitter/telegram, we can subtly suggest that there is a more dedicated channel on discord. The reason being that we need a common communication point.  

Events get announced on twitter, Discord, telegram and Rust_Ke website.  


The main website has 3 kinds of boards :
1. Past Events
2. Coming Events
3. Participation Guide (sponsorship stuff : 'cash, rooms, knowledge')


### Using the Leptos Framework
Leptos framework is great.  

But for now, can we just do the website using html,css and vanilla javascript. After most of the website is done, we can port it to be leptos-compliant and cancel out all the js with Rust.  

Also, the website does not currently implement server-side rendering... because... well, everything in it is static... we currently have no need for server functions.  
This hurts SEO, but we will improve with time.  

