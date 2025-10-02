# Tech Radar

The Radar is a document that sets out the changes that we think are currently interesting in software development — things in motion that we think you should pay attention to and consider using in your projects. It reflects the idiosyncratic opinion of a bunch of senior technologists and is based on our day-to-day work and experiences. While we think this is interesting, it shouldn’t be taken as a deep market analysis.

## Who is the Technology Advisory Board (TAB)

Our TAB is made up from team members of the CCOE, SRE, Platform, Security and Product teams

## What's the structure of the Radar

The Radar is all about tracking interesting things, which we refer to as blips. We organize the blips onto the Radar using two categorizing elements: the quadrants and the rings. The quadrants represent different kinds of blips. The rings indicate what stage in the adoption lifecycle we think they should be in.

## What Counts as a Blip

A blip is a technology or technique that plays a role in software development. Blips are things that are ‘in motion’ — that is we find their position in the Radar is changing - usually indicating that we’re finding increasing confidence in them as they move through the rings.

## What are the quadrants

The quadrants are a categorization of the type of blips:

* Programming Languages and Frameworks. languages and frameworks that are used withing the business.
* Tools. These can be components, such as databases, software development tools, such as versions control systems; or more generic categories of tools, such as the notion of polyglot persistence.
* Platforms. Things that we build software on top of such as mobile technologies like Android, virtual platforms like the JVM, or generic kinds of platforms like hybrid clouds.
* Techniques. These include elements of a software development process, such as experience design; and ways of structuring software, such as microservices.
 

We don't make a big deal out of the quadrants — they’re really just a way to break up the Radar into topic areas. We don't think it's important which quadrant a blip goes into, unlike the rings - which generate a lot of discussion.

## What are the rings?

The metaphor of a radar says that the closer a blip is to you, the sooner it will be on top of you. Like most metaphors, you can't take it too seriously, but there's an essential sense to it.

Our Radar has four rings, which we'll describe starting from the middle:

* The <b>Adopt</b> ring represents blips that we think you should seriously consider using. We don't say that you should use these for every project; any tool should only be used in an appropriate context. However we do think that a blip in the Adopt ring represents something where there's no doubt that it's proven and mature for use.
* The <b>Trial</b> ring is for blips that we think are ready for use, but not as completely proven as those in the Adopt ring. So for most organizations we think you should use these on a trial basis, to decide whether they should be part of your toolkit. Typically we've used trial blips in production, but we realize that readers are more cautious than us.
* The <b>Assess</b> ring are things to look at closely, but not necessarily trial yet - unless you think they would be a particularly good fit for you. Typically, blips in the Assess ring are things that we think are interesting and worth keeping an eye on.
* The <b>Hold</b> ring is for things that, even though they are accepted in the industry, we haven't had a good experience with. Therefore we are calling them out to warn you that you may run into trouble with them as well. Sometimes it means we think they're irredeemably flawed; or just being misused. We do place things in the Hold ring that we wish the industry wouldn't use.

We can only put blips into the Trial ring when we have experience of that blip on a real project. This can mean we sometimes look behind the technology curve, because we may like the look of a technology but haven't yet persuaded a client to try it out - and until we do that blip cannot pass into Trial.

For the Adopt ring, we only include items when we think it would be a poor and potentially irresponsible choice not to use them given the appropriate project context.

## Whats the criteria for getting a blip?

Fundamentally, it boils down to one or more TAB members thinking it's important. 

## How to update and access the radar

The data that is used to generate the radar is in a TechRadar.csv file located in the following github repo.

* [TechRadar CSV](https://github.com/WarnerEngineering/tech-radar/blob/main/TechRadar.csv)

The CSV contains 5 columns:
* name
* ring     (Assess/Adopt/Trial)  
* quadrant (Platform/Tools/Techniques/languages-and-frameworks)
* isNew    (True/False)
* description (Supports HTML formatting)

NOTE: Do not Add or delete columns.

Adding a new blip involves populating a new entry on the csv file and commiting it to the main branch in github.

Once in github the radar can be visualised using hte following link:

* [TechRadar Visualisation](https://radar.thoughtworks.com/?documentId=https%3A%2F%2Fraw.githubusercontent.com%2FWarnerEngineering%2Ftech-radar%2Fmain%2FTechRadar.csv)



