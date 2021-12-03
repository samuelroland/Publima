# Publima
### A publication management tool designed for collectives.

## This project is dead...
In October 2021, after about 2 months of slow research in my collective at a national level (14 users interviews,  some brainstormings, ...), I have to give up this project (that's sad), mostly due to lack of time and other projects running in parallel. If you find it interesting anyway, or you are building something similar, I would love to know your project. Ping me in the fediverse or by email.
Don't look for code, there is none, the project was only at the starting phase (research), the development strategy at the bottom is obsolete. There is LDM for the database, but it's maybe too extensive for a first version.

-----
**DISCLAIMER**: The first versions of this app is built only for my collective. I don't want to maintain it for a large public and collectives because I have other projects. That's why, I don't accept external contributions for the moment. If you're interested in the project or to use it for your own collective, let me know: star the repos or contact me on [Mastodon](https://fosstodon.org/@samuelroland).

## Introduction
In brief, **Publima** is free software (used as a web application) **to manage publications in a collective**. The aim is to *collaborate efficiently*, be able to *plan* intelligently, have a *global overview*, increase *transparency and collaboration*, help to *apply the internal process and rules* and *involve members*, at each step.

Collectives usually use multiple plateforms (Facebook, Twitter, Instagram, blog, website, newsletter, ... no one know them all) to communicate with their audience. Sometimes they are multiple accounts per plateform because different geographical levels and 2-3 different languages.

Here by `publication`, we mean every public/followers-only/private creations released. By `collective`, we mean every group that communicates publicly and where several people manage the communication. Obviously, it includes social networks, blogs, newsletters, podcasts, ... but it concerns any kind of publishing plateforms with text and/or multimedia content. The plateform (at least the first versions) will not send automatically the publications, when publications are ready to be published, the publications on each choosen plateform must be sent manually.

The platform should help **to reduce complexity** with challenges around publications. A publication is usually not only a text, often some visuals, or files are attached. In addition, they are a bunch of things that make collaboration harder: publishing platforms constraints, translations, feedbacks and fixes management, validation processes, diversity of formatting options, members' skills and access to the collective accounts, ...

**Status**: This project is **currently to the starting point.** Nothing is implemented yet. Some points/ideas/feature priority will change over time and enhance depending on user feedback.

-----
## Development Strategy
The aim of the strategy is to maximize the chances to make a useful app, validate the idea before to start coding, implement the most needed features not the others, ...
### Steps
- [ ] Read existing documents of discussions around collaboration.
- [ ] Interview 15 persons by written or oral.
- [ ] Write down the most important problems. Decide which features can resolve/help them.
- [ ] Search for existing solutions and compare them. Write down good ideas and common points.
- [ ] Define the MVP
- [ ] Build a little logo
- [ ] Define little models
- [ ] Implement users and groups management
- [ ] Deploy on personal domain
- [ ] Ask for 2 feedbacks
- [ ] Implement publications management
- [ ] Ask for 2 feedbacks
- [ ] Release v1.0-beta
- [ ] Ask for feedbacks, bugs report and tests
- [ ] Implement security
- [ ] Fix latest bugs
- [ ] Organise a presentation meeting. Continue if accepted. If not, change the strategy.
- [ ] Do a training video and/or a presentation video in english
- [ ] Release v1.0 versions
- [ ] Deploy on the collective's subdomain.
- [ ] Create first admins account and give access. Setup base data (accounts, plateforms, ...)
- [ ] Break of 3 days
- [ ] Fix last bugs found and make sure everyone is able to use the app
- [ ] Deploy bug fixes
- [ ] Setup contact mean for security and questions.

#### Which parts are pain points in publication management ?
-> See complete
- To Be Defined with user feedbacks

#### MVP (Minimum Viable Product)
- To be defined

-----
### Time allocated
**1 month**. Between 23.08.2021 and 19.09.2021. The goal is to develop fast and to not spend more than 1 month and a half on it.
Reflection work has already been done. A [logical data model (LDM)](docs/MLD.png) is already done. Here is the estimated program for the month:
1. 1 week of research and user interviews/talks
1. 2.5 weeks of development (with very frequent feedback loops)
1. 0.5 Week to test security, fix last bugs, deploy, and teach users how to use it (make a video or a document to explain).

## Personal goals
1. Use only free software to build the app
1. Validate a project idea with user interviews to really understand their problems and needs.
1. Understand deeply pain points to be able to offer the most useful features
1. Provide a tool that resolves or help these problems
1. Try to work with an extremely short feedback loop (1-2 days) with different future users
1. Learn technically about the TALL stack, deployment and web app updates
1. Enhance my responsive design skills
1. Learn to write unit and features tests for Laravel and Livewire
1. Try to produce software in a short period, by implementing the most useful features and what really matters
1. Experimenting with production and maintenance of a web app, used by about 20 users
