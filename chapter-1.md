---
layout: page
title: Designing Systems
chapterTitle: Chapter 1
permalink: /chapter-1/
---

A long, long time ago, there were these things called _books_. Remember them? These contraptions were heavy and bulky and made from the pulp of dead trees. Inside these books were things called _pages_. You turned them, and they cut your fingers.

Awful things. I’m so glad these book things with their razor-sharp pages aren’t around anymore.

Oh wait.

## Our paginated past
The _page_ has been with us for a long time now. A few millennia, actually. The first books were thick slabs of clay created about 2,000 years ago, which quickly replaced scrolls as the preferred way to consume the written word. *(note: footnote referring back to The Shallows)*. And while reading technology has come a long way – from parchment to paperback to pixels – the concept of the page holds strong to this day. 

The page metaphor has been baked into the lexicon of the Web since the very beginning. Tim Berners-Lee invented the World Wide Web so that he, his colleagues at CERN, and other academics could easily share and link together their world of *documents*. This document-based, academic genesis of the Web is why the concept of the *page* is so deeply ingrained in the vocabulary of the internet.

So what? 

As we’ll discuss throughout this book, the way things are named very much impact how they’re perceived and utilized. Thinking of the Web as *pages* has real ramifications on how people interact with web experiences, and influences how we as an industry go about creating Web interfaces.

From the beginning, the page metaphor provided users with a familiar language for which to navigate this brave new World Wide Web. Concepts like bookmarking, pagination, etc. helped new Web users explore and eventually master an entirely new medium using conventions they were already comfortable with.

{% include figure.html src="../images/content/chrome-webpage.png" caption="Chrome browser displaying ‘This webpage is not available’ message" %}

The page was–and continues to be–a very visible and helpful metaphor for the end users of the Web. It also has a profound influence on how Web experiences are created.

In the early days of the Web, companies looking to get online simply translated their printed materials onto their websites. But even though these brochure websites offered a very one-dimensional perspective of what the Web could offer, viewing websites as digital representations of the printed page was easy for creators to wrap their heads around. 

But we’re now 25 years into this new medium, and this once-necessary figure of speech has overstayed its welcome. Unfortunately, the page metaphor continues to run deep with respects to how we scope and execute our Web projects. Here are just a few examples I hear on a regular basis:

“We’re a startup looking to launch a 5-*page* website this October…”

“Brad, how long will the home *page* take to build?”

“How are we ever going to redesign this university website that contains over 30,000 *pages*?!”

All of the above statements make the fundamental mistake of assuming a *page* is a uniform, isolated, quantifiable thing. The reality is that the Web is a fluid, bi-directional, interdependent medium, and as soon as we come to terms with that fact the notion of the *page* quickly erodes as a useful means to scope and create Web experiences.

How long will a homepage take to build? Well, that sort of depends on what’s on it, right? Maybe the homepage simply consists of a  tagline and a background image, which means it could be done by lunch. Or maybe it’s chock full of carousels, dynamic forms, and third-party integrations. In that case, maybe the homepage will take several months to complete. 

As for the 30,000-page university website, it might be tempting to declare “Thousands of pages!? Wow, that sounds challenging!” But in reality, those 30,000 pages may consist of three content types and two over-arching layouts.

Ultimately, a project’s level of effort is much better determined by the functionality and [components](http://bradfrost.com/blog/post/scope-components-not-pages/) contained within those pages, rather than on the quantity of pages themselves.

The page metaphor served its purpose helping users familiarize themselves with the Web, and provided creators with a necessary transitional language for which to create for a brand new medium. But in order to create thoughtful interfaces meant to be served to a multitude of connected devices, the time has come for us to evolve beyond the page.

## Tearing up the page
Thankfully, the Web community is hard at work establishing principles and practices to help us effectively talk about and create for the Web. And there’s one concept the keeps popping up in every conversation about how to create successful Web experiences: **modularity**. 

The concept of modularity predates the Web by a long shot. The Industrial Revolution brought about interchangeable parts
and Henry Ford’s assembly line, which forever transformed the automobile-manufacturing process. Early cars and components were individually crafted, which led to many safety and maintainability nightmares. Ford broke the automobile down into its component parts, and modularized the assembly process. The results spoke for themselves: more uniform, reliable, safer cars rolled out of the factory, and in record time to boot.   

As the machine age transitioned into the computer age, the computer science field began practicing object-oriented programming and establishing important modular concepts like *separation of concerns* and the *single responsibility principle*. It is from this world that the World Wide Web was born, so it’s no surprise that [modular design](http://www.w3.org/DesignIssues/Principles.html#Modular) quickly became a design principle for the architecture of the Web. 

Slowly but surely these concepts found their way into web designers’ workflows. In the early 2000’s we saw the introduction of libraries like [YUI](http://yuilibrary.com/) and [jQuery UI](http://jqueryui.com/), which provided developers with a toolkit of widgets and patterns to better create interactive interfaces.

If modularity has been around for such a long time, why are we talking about it now?

The short answer is that modularity matters now more than ever. Right now, our entire industry is drowning in a sea of devices, viewport sizes, and online environments. And things aren’t slowing down anytime soon.

> Disruption will only accelerate. The quantity and diversity of connected devices—many of which we haven't imagined yet—will explode, as will the quantity and diversity of the people around the world who use them. Our existing standards, workflows, and infrastructure won't hold up. Today's onslaught of devices is already pushing them to the breaking point. They can't withstand what's ahead. <cite>[The Future-Friendly manifesto](http://futurefriendlyweb.com/)</cite>

{% include figure.html src="../images/content/devices.jpg" caption="These are just some of the connected devices we need to worry about." %}

Like it or not, this multi-device universe is now our reality. It was hard enough to get our Web pages to display consistently in a handful of desktop browsers, but we’re now tasked with ensuring our web experiences look and function beautifully on a plethora of smartphones, tablets, phablets, netbooks, notebooks, desktops, TVs, game consoles, and more. 

In order to address this reality while maintaining our sanity, it’s absolutely necessary for us to take a step back and break these giant responsibilities into smaller, more manageable  chunks.

And that’s exactly what folks are doing. The spirit of modularity is weaving its way into every aspect of the Web creation process, and is having profound effects on organizations’ strategy, process, content, design, and development.

### A manageable strategy
Every organization is finally realizing that bulldozing their entire website and replacing it with a New-And-Shiny™ website every three-to-eight years isn’t (and never was) an optimal solution.

Out with the old! In with the new! It’s certainly an attractive prospect. But even before the launch-party confetti is swept up, the calls start coming in. “You moved my cheese!” cry the users, who spent years learning the previous interface and functionality. 

When massive redesigns launch with significant changes to the experience, users get knocked down what Jared Spool calls the [“Magic Escalator of Acquired Knowledge”](http://www.uie.com/articles/magic_escalator/). Huge redesigns are a jolt to the system, and newly-frustrated users have to spend a great deal of time and energy relearning the experience in order to slowly climb back up that escalator of acquired knowledge. 

In addition to disorienting users, these monolithic redesigns don’t get to the the organizational root of the problem. Without a fundamental change in process, history is bound to repeat itself, and what’s New-And-Shiny™ today becomes Old-And-Crusty™ tomorrow. The cycle repeats itself as companies push off minor updates until the next Big Redesign, ultimately paralyzing themselves and frustrating users in the process.

Thankfully, even massive organizations are taking cues from the smaller, leaner startup world, and are striving to get things out the door quicker. By creating *minimum viable products* and shipping often to iteratively improve the experience, organizations are able to better address user feedback and keep up with the ever-shifting Web landscape.

Moving away from Ron-Popeil-esque, set-it-and-forget-it redesigns requires deliberate changes in organizational structure and workflow. Which is a heck of a lot easier said than done.

### An iterative process 
If I had a quarter for every time I heard some stakeholder declare “we’re trying to be more agile,” I’d be orbiting the earth in my private spacecraft instead of writing this book.

Wanting to be more agile is commendable. But “agile” is a loaded term, with big differences between capital-“A” Agile and lowercase-“a” agile. Capital-“A” Agile is a specific methodology for software development, equipped with a [manifesto](http://www.agilemanifesto.org/) and accompanying frameworks like [Scrum](http://en.wikipedia.org/wiki/Scrum_%28software_development%29) and [Lean](http://en.wikipedia.org/wiki/Lean_software_development). 

Lowercase-“a” agile is more of an informal desire to create an efficient process. This desire may certainly involve adopting general [principles](http://www.agilemanifesto.org/principles.html) from capital-“A” Agile, but it may not involve adopting the Agile process in its entirety. Project manager Brett Harned explains:

> We want to be more agile; we’re embracing change, continuing improvement, being as flexible as possible, and adapting as we see fit. The thing is, we won’t ever truly be Agile, as the Manifesto states. That’s okay, as long as we say what we will be. <cite>[Brett Harned](http://cognition.happycog.com/article/diy-process)</cite>

Organizational structure, client relations, personalities, etc all play major roles in determining a project’s process. The trick is to find the process that works best for you, your organizational constraints and opportunities.

Even though it may be impossible to adopt a truly Agile process, it’s still a sound idea to work in cross-disciplinary teams, get into the final environment faster, ship early and often, and break bigger tasks into smaller components. In Chapter 4, we’ll detail how to establish an effective pattern-based workflow.

### Modularizing content: I’m on Team Chunk 
> Get your content ready to go anywhere, because it’s going to go everywhere. <cite>[For A Future-Friendly Web](http://bradfrost.com/blog/web/for-a-future-friendly-web/)</cite>

Publishing content for the Web used to be a fairly straightforward endeavor, as the desktop Web was the only game in town. Oh, how things have changed. Today, our content is being consumed by a whole slew of  smartphones, dumb phones, netbooks, notebooks, tablets, e-readers, smart watches, TVs, game consoles, digital signage, car dashboards, and more.

In order to properly address this increasingly diverse and eclectic digital landscape, we need to dramatically overhaul our perception of content and the tools we use to manage it.

> In the future, what I believe is that we are going to have better content management and content publishing tools. We are going to have ways to take well-structured content, well-designed chunks of content that we can then figure out how we want to restructure and publish and display in a way that’s going to be right for the appropriate platform. <cite>[Karen McGrane](http://karenmcgrane.com/2012/09/04/adapting-ourselves-to-adaptive-content-video-slides-and-transcript-oh-my/)</cite>

Thankfully, this future is starting to take shape. Organizations are recognizing the need to create modularized content to better reach their audience wherever they may be. And content management systems are evolving beyond their Web publishing platform roots into tools that can elegantly create and maintain modular content. While sophisticated content management systems have existed for years now in the form of custom solutions like [NPR’s COPE (Create Once, Publish Everywhere) platform](http://www.programmableweb.com/news/cope-create-once-publish-everywhere/2009/10/13) , smart modular thinking is making its way into mainstream content management systems.

### Classy code
Modularity has long been a staple principle in the world of computer science, as we discussed earlier in the chapter. While this principle existed long before the Web was invented, it’s taken some time for modularity to become engrained in the minds and hearts of Web developers.

Despite it been around since 1995, JavaScript, the programming language of the Web, first had to endure some growing pains in order to mature into the capable, respected language it is today. Now that JavaScript has grown up and dust has settled, developers can now apply those tried-and-true computer science principles to their Web development workflows. As a result, we’re seeing folks develop sophisticated JavaScript [patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/) and architectures.

Applying modular programming principles to JavaScript is a bit of a no brainer, since JavaScript is itself a programming language. But  object-oriented thinking is weaving its way into other aspects of the Web as well, including CSS, the styling language of the Web. Methodologies like [OOCSS](http://oocss.org/), [SMACSS](https://smacss.com/), and [BEM](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax) have cropped up to help Web designers create and maintain modular CSS architectures.

### Visually repaired
Not only is modularity infiltrating the code side of style on the Web, it’s totally revolutionizing how visual designers approach modern Web design. 

As the number of viewports and environments proliferate, it’s quickly becoming untenable to produce static mockups of every page on a Web experience. As Stephen Hay quipped, presenting fully baked Photoshop comps “is the most effective way to show your clients what their website will never look like.” 

That’s not to say static design tools like Photoshop and Sketch aren’t important. Far from it! But it’s in the way we use these tools that has changed dramatically. While creating hundreds of full-on comps isn’t realistic, these static tools excel at providing a playground to establish what Andrew Clarke calls “design atmosphere”:

> Atmosphere describes the feelings we get that are evoked by colour, texture and typography. You might already think of atmosphere in different terms. You might call it “feel”, “mood” or even “visual identity.” Whatever words you choose, the atmosphere of a design doesn’t depend on layout. It’s independent of arrangement and visual placement. It will be seen, or felt, at every screen size and on every device. <cite>[Andrew Clarke](http://stuffandnonsense.co.uk/blog/about/an-extract-from-designing-atoms-and-elements)</cite>

Establishing design atmosphere early is critical to a project’s success, which is why designers have found ways to facilitate these important conversations without having to generate full mockups. Designer Samantha Warren developed design artifacts called [style tiles](http://styletil.es/), which demonstrate color, type, and texture explorations in a nice encapsulated one-pager. Designer Dan Mall built upon Samantha’s idea with a concept called [element collages](http://danielmall.com/articles/rif-element-collages/), which demonstrate design atmosphere explorations in an exploded collage of interface elements.

![Style Tiles and Element Collages]()

By breaking visual explorations into smaller chunks, designers save time and effort while saving themselves from presenting unrealistic, premature layouts to clients. More importantly, these approaches shift stakeholders away from simply reacting to a pretty picture, and instead facilitate crucial conversations about the overall design direction and how they relate to the project’s goals. We’ll discuss these concepts in more detail in Chapter 4, but suffice it to say the visual design workflow is changing in a big way!

### Systematic UI design
> We’re not designing pages, we’re designing systems of components. <cite>[Stephen Hay](http://bradfrost.com/blog/mobile/bdconf-stephen-hay-presents-responsive-design-workflow/)</cite>

What is an interface made of? What are our Lego bricks? What are our Subway sandwich pieces that we combine into millions of delicious combinations? It’s these questions that we’ve been asking ourselves more and more now that we’re sending our interfaces to more and more places. 

A few years ago Ethan Marcotte introduced us to the idea of [responsive web design](http://alistapart.com/article/responsive-web-design) and its three core tenets: fluid grids, flexible media, and CSS media queries. These three ingredients provided a much-needed foundation for designers to create flexible layouts that smartly adapt to any screen size. Perhaps more importantly, responsive design helped get designers excited about creating thoughtful, adaptable, multi-device Web experiences.

As designers quickly discovered, creating multi-device Web experiences involves a lot more than creating squishy pages.  Each individual piece of an interface contains its own unique challenges and opportunities in order for it to look and function beautifully across many screen sizes and environments. 

How can we present primary navigation-typically displayed as a horizontal list on large screens–in a thoughtful way on smaller screens? How do lightboxes, breadcrumbs, and carousels translate to smaller viewports and alternate input types? It’s these questions that led me to create [This Is Responsive](http://bradfrost.github.io/this-is-responsive/index.html), a showcase of responsive patterns that demonstrate the various ways a particular component could be executed in a responsive environment.

While This Is Responsive is successful at articulating how these interface patterns can scale across screen sizes and environments, it’s still up to designers and developers to put these patterns into action. And as it turns out, that’s a lot of work.

## UI frameworks, in theory and in practice
Designers and developers are already strapped for time and resources, and they’re now being tasked with making interfaces that look and function beautifully in any environment. It’s a tall order indeed.

This need to address growing device diversity while still sanely getting projects out the door has given rise to front-end frameworks like [Foundation by Zurb](http://foundation.zurb.com/) and [Bootstrap](http://getbootstrap.com/). 

These user interface frameworks provide designers with a collection of pre-assembled HTML patterns, CSS styles, and JavaScript to add functionality to interactive components like dropdowns and carousels. In essence, these frameworks are handy toolkits for quickly assembling interfaces.

{% include figure.html src="../images/content/bootstrap-components.png" caption="Bootstrap provides a collection of UI components to speed up development"  %}

And boy are these things popular. As I’m writing this, Bootstrap is the most popular repository on the code-sharing site [Github](https://github.com/), with over 77,000 stars and 30,000 forks. These frameworks’ popularity is a testament to the fact that designers and developers are seeking solid ground to stand on in this ever-complex Web landscape.

One of the most attractive aspects of these frameworks is *speed*. Frameworks like Bootstrap allow designers to get ideas off the ground quickly, rapidly create prototypes, and launch sites sooner. Because the toolkit’s provided patterns are already cross-browser tested, a developer can spend her time on more important tasks rather than beating her head against a table testing some archaic version of Internet Explorer. And in case designers do get stuck, these frameworks’ communities can provide helpful support and advice.

For a freelancer, this increase in speed might mean they can take on an extra project or three, yielding more financial stability for the year. And in the startup world–a place where Bootstrap is omnipresent–minimum viable products can launch sooner, leading to faster answers regarding the products’ viability.

So frameworks like Bootstrap are insanely popular design systems that provide well-tested components, resulting in consistent designs and faster launches. What’s not to love? Well, like most everything in life, there are cons right there alongside the pros. 

### Trouble in framework paradise
When I was a kid, I’d watch sci-fi movies and TV shows with a strange fascination. There was one question I could never quite shake: *why are they all dressed the same*? 

{% include figure.html src="../images/content/sci-fi.jpg" caption="In the future, everyone dresses the same." %}

I could only guess that given enough time, we *solve fashion*. “Say, these jumpsuits are pretty snazzy, and comfortable too! Let’s just all wear these from now on.” “Sounds good to me!” 

Of course that’s not how human beings work. We all have different tastes, goals, and desires. Variety, as they say, is the spice of life, and fashion, music, and design reflect our diverse nature.

Yet we on the Web tend to fall into the trap of wanting everyone to do things the same way. “Why don’t all browsers just standardize on Webkit?” “Why can’t device manufacturers just use the same screen sizes?” “Always use jQuery!” “Never use jQuery!” “Just use frameworks!” “Never use frameworks!” 

Just like the real world, the diverse needs, goals, and desires of Web projects lead to a myriad of different solutions. Of course there’s a time and place for everything, and designers and developers need the discernment to know which tools to use and when.

Front-end frameworks are tools that provide a specific solution and a particular look and feel. While those solutions help speed up development, the resulting experiences end up resembling those sci-fi jumpsuits. When everyone uses the same buttons, grids, dropdowns, and components, things naturally start to look the same. If Nike, Adidas, Puma, and Reebok were to redesign their respective sites using Bootstrap, they would look substantially similar. That’s certainly not what these brands are going for. Sure, each brand can modify and extend the default look and feel, but after a while customization means fighting the framework’s provided structure, style, and functionality.

In addition to lookalike issues, these frameworks can add unnecessary bloat to an experience. It’s fantastic that frameworks provide plenty of pre-built components and functionality, but a large percentage of designers and developers won’t utilize every aspect of the framework. Unfortunately end users still have to download the framework’s unused CSS and JavaScript, resulting in slower page loads and frustration.

On the flip side of that coin, frameworks might not go far enough, leading to developers needing to create a substantial amount of custom code in order to achieve their projects’ goals. At some point a threshold is crossed where the initial benefits of using a framework–namely development *speed*– are outweighed by the time spent modifying, extending, and fixing the framework.

And then there’s the issue with naming. Using a framework means subscribing to someone else’s structure, naming, and style conventions. Of course it’s important to establish a useful front-end lexicon, but what makes sense for an organization might not be what comes out of a framework’s box.  I, for one, would balk at the idea of using Bootstrap’s default featured-content area component they call a “jumbotron”. How a framework’s naming conventions jive with an existing codebase and workflow should be properly discussed before jumping on board the framework train.

Now that we’ve put frameworks through the wringer, it’s important to take a step back and recognize that conceptually these frameworks are very much on point. It’s an excellent idea to work with a design toolkit that promotes consistency and speeds up development time. While discussing the redesign of Microsoft’s homepage by Austin-based Web shop Paravel, developer Dave Rupert stressed the importance of creating and delivering a design system to their client. Dave wonderfully articulated that it’s not necessarily about using Bootstrap for every client, but rather creating “tiny Bootstraps for every client.”

> Responsive deliverables should look a lot like fully-functioning Twitter Bootstrap-style systems custom tailored for your clients’ needs. These living code samples are self-documenting style guides that extend to accommodate a client’s needs as well as the needs of the ever-evolving multi-device web. <cite>[Dave Rupert](http://daverupert.com/2013/04/responsive-deliverables/)<cite>

It’s not just about using a design system, it’s about creating *your* system.

## Design systems save the day
So what do a sound design systems look like? What form do they take? How do you create, maintain, and enforce them? 

The cornerstone of good design systems are *style guides*, which document and organize design materials while providing guidelines, usage, and guardrails.

As it happens, there are [many flavors of style guides](http://bradfrost.com/blog/post/style-guides/), including documentation for brand identity, writing, voice and tone, code, design language, and user interface patterns. This book won’t detail every category of style guide, but it’s important to take a look at each to better understand how each style guide influences the others, and how style guides for the Web fit into a larger ecosystem.

### Brand identity guidelines
{% include figure.html src="" caption="Caption" %}

Brand identity guidelines define the assets and materials that make a company unique. Logos, typography, color palettes, messaging (such as mission statements and taglines), collateral (such as business card and PowerPoint templates), and more are aggregated and described in brand identity guidelines.

Brand style guides provide an foundational center for a company. It’s essential for a brand to present itself in a cohesive manner across an increasing number of media, channels, and touchpoints. How can everyone within an organization speak with the same voice and feel part of a singular entity? How do third parties know which Pantone colors to use and how to correctly use the brand’s logo? Brand identity guidelines provide answers to these extremely fundamental questions.

Historically, brand identity guidelines were contained in hard-cover physical books (remember, those things with the pages?), but as with everything else brand style guides are making their way online.

### Design language
While brand identity guidelines are fairly tactile, design language guidelines are a bit harder to pin down. Design language style guides articulate a general design direction, philosophy, and approach to specific projects or products.

In order to present itself in a cohesive way across a growing range of products and mediums, Google developed a design language they call *material design*. The [material design style guide](http://www.google.com/design/spec/material-design/introduction.html) defines its overarching design philosophy, goals, and general principles, while also providing specific applications of the material design language.

{% include figure.html src="" caption="Google Material Design" %}

Design language style guides can (and usually do) incorporate aspects of other style guide categories in order to make high-level concepts a bit more tangible. 

Design language guidelines aren’t set in stone the same way brand guidelines are. For example, one day Google will likely develop a new design language to replace material design, so while Google’s overall brand will remain intact, the design vocabulary around its products will change.

### Voice and Tone
{% include figure.html src="" caption="Caption" %}

People are interacting with brands across a dizzying array of channels and mediums: Web, mobile, print, retail, outdoor, radio, TV, email, and much much more. Speaking in a cohesive, consistent manner across all of these touchpoints is critical to a brand’s success.  

Voice is an elemental aspect of brands’ identities, so typically brand identity guidelines include some reference to tone of voice. However, these overarching guidelines usually aren’t very nuanced, which is why voice and tone guidelines are so important. 

Voice and tone guidelines get into the weeds by articulating how the company’s voice and tone should shift across a variety of scenarios. [MailChimp’s brilliant voice and tone guidelines](http://voiceandtone.com/) define how the brand’s tone changes across content types, so that when a user’s credit card is declined, writers know to shift away from their generally-cheeky-and-playful tone of voice and instead adopt a more serious tone.

Voice and tone style guides provide much-needed guidelines for how to … establish deliberate 

### Writing
{% include figure.html src="" caption="Caption" %}

Creating a consistent writing style for an organization with many voices can be challenging. Now that the Web makes it easy for everyone in an organization to publish, it’s especially important to provide every author some guidelines and guardrails for contributing.

Writing style guides can be extremely granular, but they don’t always have to be. This writing style guide from the Web team at Dalhousie University is one of my favorite documents on the Web. Short, direct, and practices what it preaches.

### Code style guides
{% include figure.html src="" caption="Caption" %}

It’s absolutely essential for teams to write legible, scalable, maintainable code. But that all falls apart when Summer Intern #2 swoops in and writes things all sorts of terrible.
Code style guides provide conventions, patterns, and examples for how teams should approach their code. These guidelines and guardrails help reign in the madness so that teams can focus on producing great work rather than refactoring a bunch of sloppy, inconsistent code.

## Pattern Libraries
{% include figure.html src="" caption="Caption" %}

Pattern libraries, or front-end style guides, UI libraries, component libraries, or whatever you want to call them, are increasingly important. As Web designers, we’re now tasked with creating interfaces that look and function beautifully across a myriad of screen sizes, devices, browsers, and environments. That’s why it’s so essential to break our interfaces down into their atomic elements.


## Benefits of style guides
In her book [Front-end Style Guides](http://maban.co.uk/projects/front-end-style-guides/), Anna Debenham deftly explains the myriad benefits of establishing front-end style guides:

provide documentation 

- Promotes consistency and cohesion
- Easier to test
- Better workflow
- Creates a shared vocabulary
- Useful reference to keep coming back to.
- Maintainability
establish a system that can be modified and extended, future-friendly.
- Establish a consistent, shared vocabulary between everyone involved in a project.

[a](http://us5.campaign-archive1.com/?u=7e093c5cf4&id=ead8a72012&e=ecb25a3f93)

### Style guide challenges
By now the benefits of creating a design system should be abundantly clear, and hopefully exciting thoughts of making beautiful style guides are running through your head.

For all the benefits these benefits.

- Difficult to sell
- Time consuming to create
- Treated as a auxiliary project
- Often created after a project launches
- Often too abstract
- Seen only as a designer/developer tool
- Often incomplete/only serving present cases
- Maintenance
- Governance
- Lacking a clear methodology. Spray of modules

## In search of a methodology
- Evolving beyond the page metaphor
- Recap modularity as a trend. 
- Framework pros and cons
- Design systems benefits and challenges
- The need for a methodology

Lorem ipsum dolar yadda yadda yadda to be continued…


