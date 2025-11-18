# Architecture
For me thoughts of "architecture" has been present in my mind for as long as I can remember. Maybe it's personality trait, but I wouldn't be surprised if it has something to do with how my father always created smart tools and workarounds for when he worked on cars, boats and houses. For the most part it was as a hobby, but at times it was a sidle hustle that almost turned into a carrier. When I started working myself as a software developer the first thing I bought was a book about design patterns and things just progressed from there. 

When studying at a technical university I realised that what we were tought was not really math, physics, programming etc, but rather how to analyze, categorize and solve different types of problems. The key word here is "**types**" which relates to design patterns and architecture in general.

## The Why
So why is finding those patters and problem "types" so important? Some has to do with the **[DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)** principle in software development which stands for **"Don't repeat yourself"** and is stated as "*Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.*" and some has to do with using abstractions that makes things clear when you describe what parts of a codebase or parts of a solution actually does. A Swedish writer Esaias Tegnér (1782-1846) once said "*det dunkelt sagda är det dunkelt tänkta*" which roughly translates to "*if you can't articulate something clearly, you probably haven't thought it through properly either*".

So to summarize the two main points are
* Describe things clearly
* Don't repeat yourself

## The How
So how do you describe things clearly and avoid repetition?

### The traditional "old" method
The way things used to be done was that all planning (including architecture) was decided before the actual work/implementation was started. This approach works well when the information model, [functional requirements](https://en.wikipedia.org/wiki/Functional_requirement) and [non-functional requirements](https://en.wikipedia.org/wiki/Non-functional_requirement) are very well defined, but runs into problems if one of the prerequisites are not fullfilled or the change during the implementation faze. Examples of things that can severly impact the implementation faze are changed requirements and problems/bugs which are major and/or discovered late in the project development cycle.

#### Pros of the Waterfall Model
* **Clarity and structure**: The model provides a clear, phase-by-phase structure, making it easy to understand and manage.
* **Well-defined goals and milestones**: All requirements are gathered and documented at the outset, providing clear objectives and predictable outcomes from the start.
* **Thorough documentation**: The emphasis on detailed documentation at each stage ensures comprehensive records for maintenance and future development, and facilitates information transfer to new team members.
* **Predictable budget and timelines**: Due to extensive upfront planning, it's easier to estimate project timelines and costs accurately.
* **Suitable for specific projects**: It works best for small projects with stable, clearly defined requirements and minimal risk of changes, such as in construction or systems with stringent regulatory compliance needs.
* **Less client intervention**: After the initial requirements phase, clients have minimal involvement, allowing the internal team to focus on development without continuous feedback loops.

#### Cons of the Waterfall Model
* **Inflexibility**: It is very difficult to go back and make changes once a phase is completed. Revisions can be complex and costly if issues are discovered late in the process.
* **Delayed testing**: Testing occurs only after the development phase is complete, which means issues and flaws are discovered late, increasing the risk and effort required to fix them.
* **High risk**: If the initial requirements are misunderstood or incomplete, the project has a high risk of failure because the final product might not meet the client's actual needs, and a functional version isn't available until the very end.
* **Limited client feedback**: The lack of ongoing client involvement can lead to dissatisfaction with the final product, as there are no opportunities for the client to provide feedback and guide the development process.
* **Resource-intensive initial phase**: The requirements and design phases can be time-consuming and demand significant resources for documentation.
* **Not suitable for complex or evolving projects**: It is a poor model for long, complex projects or those where requirements are likely to change.


## Different types of architectures
- [API Architectural Styles](API_Architectural_Styles.md)
