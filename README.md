# User Stories for Solid

This repository is meant for gathering user stories. User Stories are short descriptions of a need written from the
perspective of a user, see [this article for an example](https://www.mountaingoatsoftware.com/agile/user-stories). They
are generally of the form:

> As a *type-of-user*, I want to *some-goal* so that *some-reason*.

To submit such a story, [open an issue](https://github.com/solid/user-stories/issues/new), and put the user story itself as the title. You may elaborate on it in the text, but strive to make the idea succinct enough to fit in that single line. 
Ideas that aren't fitting very well in this short format or need discussing first can be submitted [to the forum](https://forum.solidproject.org/c/1-about-solid/app-communities).

The idea is that developers and architects can use these stories in their development efforts. 

Obviously, Solid presents a wide open space of opportunity, and so, some things are relevant to different parts of the system. 
Most will be uses of Solid, as it is defined by
[the specs](https://github.com/solid/solid-spec), for example,
the story

> As a pretty distracted person, I want to record my tasks in a TODO
> list so that I won't forget them.

Other things may require new functionality from the server, for example:

> As a father, I want to set up a server for my family and only them,
> retaining some control of my children's accounts, to keep them safe
> on the Web. 

This would require something new from the registration system, in
terms of limits on who can register and what default Access Control
Lists they will be given.

They are all welcome in this repository.

# Solid User Signup 

### As a Solid user I want an explanation of what Solid is so that I understand why I need to signup for a webid and Pod 
### As a Solid user I want to be able to sign up for an online identification with webid so that I can identify myself online 
### As a Solid user I want to view the criteria to consider when choosing a Pod provider (e.g. physical location of the storage, legal location of the provider, type of legal entity, if storage is at home or at a provider)  so that I can conveniently find a Pod provider that matches my preferences
### As a Solid user I want to be presented with the Pod providers that match my criteria so that I can decide where to store my data
### As a Solid user I want to select the Pod provider and this be the default location of my data storage so that I have a minimum standard of where my data is

## Solid Identity Users 
### As a Solid user I want to be able to identify myself online so that others can trust me in online interactions 
### As a Solid user I want to use an identity verified by my government so that I can we can trust each other's identity in my country
### As a Solid user I want to be able to identify myself without association to the identifier so that I am not overdependent on an entity that I cannot control  

## Solid Pod Users 
### As a Solid user I want to choose where to store my data so that I can judge if I trust the storage provider to respect my interests 
### As a Solid user I want to be able to revoke access that an app has to my data so that I can change my mind or revise my decision when I have access to new information 
### As a Solid user I want to choose which app to use with my data so that I can use services online freely
### As a Solid user I want to know which apps are available for me to use so that I can have access to online services 
### As a Solid user I want to know when an app is using my data so that I am consciously sharing information
### As a Solid user I want to be able to share my data with other Solid users so that I can live and work efficiently 
### As a Solid user I want to be able to revoke sharing my data with other Solid users so that I can live and work efficiently 
### As a Solid user I want to be able to restore my Pod when it gets messed up so that I can always use my Pods for what I want 
### As a Solid user I want to be able to delete my data so that I can limit access to data that I am not comfortable being available 
### As a Solid user I want to update my data so that I have an accurate record 
### As a Solid user I want to know which Pods are available for me to use so that I can know what options are available to me 
### As a Solid user I want to be automatically notified of fraudulent access to my data so that I can take measures to protect myself when needed
### As a Solid user I want to access data that is shared with me so that I can live and work efficiently 
### As a Solid user I want to know that nobody else has accessed my data so that I have a clear overview of the information shared with my relationships 
### As a Solid user I want autocorrect for my data for when a shoddy app doesn’t store my data properly so that my data is clean and functional and ready for use in the apps of my choice
### As a Solid user I want to be notified when an app is shoddy and who made the shoddy app so I can avoid shoddy apps
### As a Solid user with motor problems I want to be able to navigate by data by keyboard so that I can have access to the same tools as Solid users without motor problems
### As a Solid user I want to read and navigate with voice control so that I can have access to the same tools as Solid users without read and navigations restrictions
### As a colour blind Solid user I want to use Solid normally e.g. have a monochrome interface with a highlight colour if essential so that I can use the same tools as other Solid users 
### As a Solid user I want to be able to record my wishes around what would happen to my data after my death  
### As a Solid user I want my data to be safe 
### As a Solid user with visual impairments I want to be able to increase the font size so that I can continue using Solid functionality in the same way as other Solid users 
### As a Solid user who is not computer savvy I want my data wishes to be respected so that my wishes are not compromised by my knowledge 
### As a Solid user I want suggestions for things I might like or want to know about so that I can be up to date on what is available 
### As a Solid user I want to know when a suggestion is a suggestion based on an algorithm rather than a random suggestion so that I know how information is being tailored and if I am in a bubble 
### As a Solid user I want to know the algorithm generating suggestions for me so that I know how I am being influenced and by which criteria 
### As a Solid user who is a child I want to be protected from my parent or guardians’ decisions about my data until I am of the age of consent so that I can have appropriate self determination throughout my life in a way that protects my future self  
### As a Solid user who is a child I want to be able to gain access and control of my data from my parents or guardians when I turn the age of consent so that I can self determine when I am at an age that I can take responsibility for my actions 
### As a Solid user who is a child I want to be able to delete photos of me that my parents have published so that I can protect my personal image so that 
### As a Solid user who is not compus mentus I want my interests to be protected so that I am not taken advantage of when I am in a vulnerable position 
### As a parent of a Solid user who is a child I want to protect my child from data threats
### As a Solid User I want to be able to merge data from multple Pod and visualise it together so that I have can control my data from a single log in point 
### As a Solid User I want to change my mind about what data I store on which Pod so that when a Pod goes rogue I have escape route 
### As a Solid User I want to be able to share my data with non Solid Users so that I am not dependent on other peoples use of Solid 
### As a Solid User I want be able to live in society without Solid so that it is an active choice rather than an obligation
### As a Solid User I want to be able to get an offline copy of the data on all my Pods for my own physical records and delete all my online data so that I can avoid persecution online while still having a copy of my data assets 
### As a Solid user I would like to see a public repository of access policy templates for groups that choose to use them. The templates would describe access and procedures for how public or semi public pods operate and the rules for access and denial of access. There would presumably be many different templates for different kinds of groups and their pods, from scout troops to condo boards or neighborhood associations to private clubs to local, state or national government data pods. If a template is used by an organization, there should be some assurance that the template rules are followed, and the assurance would hopefully come from a trusted source separate from the group that owns the pod.
### As a Solid user, I would like some fallback mechanism for control, so that I don't need to be afraid that I loose total control of my Pod if I mess up my permissions
### As a Solid user I want to collect all the photos from my group of friends that went to Spain for Tom's stag party, so that our group has a single shared album.
### As a Solid user I want to see the collection of my photos from Spain, for 2019, that were from work trips so I can create an album for the company blog.
### As a user I'd like to see a detailed history of access attempts to any resource within my pod so that I can see who or what is accessing which parts of my pod.
### As a user and developer, I would like to automatically generate a user interface from a data shape
### As a Solid user, I would like to participate in civic initiatives and have my views counted
As a Solid user on my mobile phone , I would like to overlay points of personal interest on a map.
### As a Solid user I want to have a tool that crawls acl files on the pod and makes suggestions based on best practices
### As a Solid user I want to be able to subscribe to a stream of pod events
### As a Solid user I want to view an interesting comment on a friends page, I would like to visit the page of the “Friend of a Friend” who made the comment.”
### As a Solid user, I need to see, review, and manage consent given to web-based services 
### As a Solid user, I want the system to ask me for confirmation across a different channel for certain operations done on my Pod to prevent accidental execution of high impact operations.
### As a Solid user with no connectivity (e.g. no phone, or an earthquake victim) I want to have an offline form factor (e.g. smart card, NFC pendant) with my ID and secure basic personal data so that I can receive services quickly and easily (e.g. food, shelter, medical aid).
### As a Solid user, I want to use my own domain name for my Pod to achieve greater independence from Pod providers.
### As a pod owner, I would like a tool that crawls acl files on the pod and makes suggestions based on best practices
### As a news reader, I need to manage my different filter bubbles.
### As a Solid user I want to be able to have an audit log of what happened to my data
### As a Solid father who is a parent I want to set up a server for my family and only them, retaining some control of my children's accounts, to keep them safe on the Web.
### As a Solid user I want to easily migrate my data from one pod to another without breaking outside links to my data so that ...
### As a Solid user I want to easily upload files into my pod so that ... 
### As a Solid user I want to be able to restore previous data so that ...
### As a Solid user I want to be able to easily review and manage who has access to my data so that ... 
### As a Solid user I want to use my WebID to register/authenticate everywhere on the Web, in and out of my pod 
### As a Solid user who is a website operator I want to manage read access to groups so that ...
### As a Solid user, I want to be able to send a copy of my data to a specific recipient so that they can see it without having access to future data
### As a Solid user, I want to be able to group people/organisations with potential access to my data together, so I can easily provide the same level of access to people that deserve it
### As a Solid user, I want to be able to give/restrict access based on usage patterns (e.g. give access to all photos with this property, even if I upload them later), so I can set up fine-grained access control once and be set for the future
### As a person, I’d like to see all data generated about me in one dashboard even if they’re not on my Pod, so I have one place to get an overview of everything relevant to me
### As a Solid user, I’d like to be able to publish my name and contact details, etc. so I have one single place to point people to who want to contact me
### As a Solid user, I’d like to public my professional credentials on my Pod, so I can use it as a CV
### As a Solid user, I’d like a sync app to automatically upload my contacts and pictures to my Pod, so I don’t have to enter them manually
### As a Solid user, I’d like to get a notification when any of my contacts have a Pod, so I can quickly get rid of the “empty desert” feeling when I get started
### As a Solid user, I want to publish huge data set, so it is easy to be accessed and can be explored using SPARQL.
### As a Solid user I want to know when I am a Solid user and how so that I am able to be in control and actively consent 
### As a Solid user I want to know when software services stop being Solid compliant so that I can be in control of leaving software services when they change from their original intentions. 
### As a Solid user I want to know who is responsible for which software service so that I can hold parites resonsible when the services go wrong. 
### As a Solid user I want to know under which jurisdiction sofware services fall so that I can be in control and actively consent 
### As a Solid user I want to know which sofware services are provided to me under jurisdictions where I can vote directly or which have have binding relevant agreements with a jurisdiction where I can vote so that I can opt for services that I can hold accountable more easily. 
### As a Solid user I want to be able to use Solid independently of any single legal entity that I do not have influence over so that I can be in control 
### As a Solid user I want to know what my options are and how they change over time so that I can be in control  

## Solid App Users 
### As a Solid user I want to chat with other Solid users so that I can communicate when not being physically in the same place
### As a Solid user who is a donor organisation (e.g. the Irish Government) I want to see a high-level aggregated report, broken down by NGO, of all the service disbursements made by those NGO's from funds I provided them so that I can report to my shareholders (e.g. the public!)
### As a Solid user who is a project manager I want to restrict participation to video meetings that use existing video conference solutions so that ... 

# Solid Provider

## Identity Provider
### As an Identity provider I want to...so that... 

## Pod Provider 
### As a Pod provider I want to run different components on different hosts so that I have a simple division of labor
### As a Pod provider I want to easily deploy on Docker so that ...
### As a Pod provider I want to see aggregated histories of access attempts to Pods I host so that I can manage hotspots, charge per usage, prevent DoS attacks, etc so that ...
### As a Pod provider who is a query engine writer I want Pods to expose cardinality estimates so that I can write a query planner that can optimize query answering over Solid data 
### As a Solid provider I want to easily find and use data shapes so that I can store data in a way that it is interoperable

## App Provider
### As an App provider I want to use an API to request access to a specific data set in a Solid users' Pod so that ...
### As an App provider who is a frontend developer I want to add end-to-end tests to ensure the interoperability and quality of our applications so that .. 
### As a App provider who is an operator of wifi for restaurants, hotels, etc I would like to allow clients to use their WebID to log in so that we don't need to manage passwords or have a captive portal. 
### As a App provider I want to easily find and use data shapes so that I can store data in a way that it is interoperable

# Unknown
### As a Solid user who is a developer I want to store and retrieve RDF resources preserving serialization-specific details (e.g. Turtle comments or prefixes) so that...
### As a Solid provider who is sells IoT devices I want my IoT devices to identify themselves so that ... 
### As a operator of Internet services for a large non-profit, I want to maintain a stable Solid server for our community so that we can interact with them safely.
### As a developer I want to set up WebRTC using a Pod
