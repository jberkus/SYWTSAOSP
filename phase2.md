# Awareness Phase

## Goal

Making sure that your target audience is sufficiently aware of your project's existence, benefits, and status.

## Pyramid Levels

Silent Users, Involved Users

## Key Metrics

## Parts

* Defining your users
* Website
* Graphics
* Documentation
* Communications Channels
* Finding awareness opportunities
  * Online meetings
  * Blogs
  * In-person events, large and small
  * Video
  * Media and Podcasters
  * Social media
  * Project cross-pollination
* Surveys
* Measuring Awareness

## Defining Your Users

Before you can reach your users, you need to figure out who your users are.

Some lucky folks will be reading this part for a project which already has a bunch of users and can simply get them to fill out a survey (but see the Surveys section).  Most project owners will be trying to create that user base from zero, though, which means figuring out who your potential users are.

This sounds very difficult, but fortunately it's well-trodden ground by the folks in Marketing.  They call it "defining your target audience" and the principles are the same whether you're talking about open source users or factory customers.

You can start by asking the following questions:

1. What problem does my project solve or capability does it add?
2. Who has that problem or that need?
3. Of those people, who is in a position to adopt your project?

For example, if your project was a network monitoring tool, you might have something like this, with even more detail:

1. Project allows scalable collection of network events across a large cluster without sacrificing detail.
2. Network administrators and network security staff who are responsible for large clusters and would like more clarity on exactly what's happening on their networks, plus vendors who make tools for those staff.
3. Staff who work at startups and very OSS-friendly companies, particularly new cloud stack companies.  Open source vendors who sell to those markets.

Once you've identified the types of users and their needs, you can move to creating a few personas of your "typical" users.  This is where you make up a story around who those users are and how they would use your project.  If you have the time and resources to actually do some interviews, you can ground these personas in the experiences of real users, but even if you need to completely make up a story it's still valuable.

A persona story walks through who the user is, how they do their jobs, what their needs are (in relation to your project), and how they would adopt and use your project.  Based on the hypothetical network monitoring project, here's an example:

Terry is a network administrator for ...

After you figure out how they would use your software, you need to figure out what the best ways to reach those personas would be.  What publications do they read?  What events do they go to?  Do they prefer blog posts or videos?  Do they use Slack, or prefer email?  Again, some actual user research in the form of surveys or engaging industry analysts can help you here, but if you lack resources you can rely on the familiarity that your existing contributors already have with your target users.

While this kind of exercise may seem artificial, it's absolutely necessary for you to make a plan around building awareness.  You're not going to make the entire planet aware of your project; even if you wanted to, you couldn't afford it.  Instead, you need to target likely prospective users, reaching them on the channels they use, addressing their needs and problems, participating in the events they go to.

Also, in the process of writing these persona stories you're going to find some gaps in your project functionality, documentation, or deployment.  That gives you a very useful list of things to fix.

Over the life of your project, this target user profile and personas will change.  As your project grows you will be able to add new use-cases and new groups of users.  Folks will also show up with uses for your software that you didn't anticipate, and you'll need to redefine.  But at least you have someplace to start.

## Website

Your website is your project's home, and it is the location that all your other awareness-building should link back to. Your website also needs enough information about your project that potential users can quickly decide whether or not they're interested in knowing more.  It serves as both a promotional tool and as a landing page and directory for your community.

### Creating Your Website

If you have access to a professional web designer, a graphically well-designed site will help give users more interest and confidence in your project.  However, it's not essential if you don't have access.  For early stage projects, it's completely appropriate for your website to look a bit clunky and unfinished, as long as it has the essential information.  An unfinished website can even be a contributor recruitment tool, and some potential contributors will have the skills to improve the website but not your software itself.

In general, it is more important for information on your website to be up-to-date than for it to be extremely detailed. When building out your website, consider not just what you have time to write, but what you will have time to maintain.  Below we'll have a long list of useful things to have in your website, but projects generally only get all of those things when they are very mature and have a website contributor team.  So start with the essential information, maybe a couple other things, and gradually build out from there.

As you create your website, you also want to think about community contribution and hosting.  Eventually, you'll want to get to a stage where a team can maintain the site.  This is easiest if you use a static site builder with the website source code stored in GitHub or Gitlab. GitHub-hosted Jeckyll or Hugo sites are very popular for this reason, but there are other options such as Ghost or Eleventy.  While dynamic platforms like Wordpress and Wix have quite sophisticated templating and design, they aren't really compatible with team maintenance or having a formal change approval process.  Plus they can cost a lot for hosting.

It's relatively common for projects to combine their documentation and website into a single site, effectively documentation with a cover page.  Platforms for this include Hugo/Docsy, AsciiDoc, and ReadTheDocs.  The advantage of this approach is that it gives you fewer things to manage and need contributors for.  The disadvantage is that documentation plaforms often aren't great for building attractive sites.

### Website Essentials

Here's a checklist of the essential things you website absolutely needs to have to reach users:

* Project name and logo
* Project tagline
* Project pitch
* Documentation or links to documentation
* Links or details on how to download the project
* Links to your source code
* Links to most or all of your communications channels

**Project name and logo** should be self-explanatory.

**Project tagline**: a one sentence top-level summary of what your project is for, and why the target audience would be interested in it.  The purpose of the tagline is to identify the project for first-time visitors, particularly if your project name isn't self-explanatory.  It should explain, as succinctly as possible, what your project does. A little bit of marketing here isn't a bad idea. Examples:

"Kubernetes is an open source system for automating deployment, scaling, and management of containerized applications."

"Camel is an Open Source integration framework that empowers you to quickly and easily integrate various systems consuming or producing data."

"A Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards."

**Project Pitch**: a longer, 1-2 paragraph, full elevator pitch for your project.  This pitch should address who the project is for, why and how they'd use it, and how it fulfills their needs.  This pitch is to your potential users; by the end of it, they should be able to make an informed decision as to whether it's something they might care about.  Example:

"KubeVirt technology addresses the needs of development teams that have adopted or want to adopt Kubernetes but possess existing Virtual Machine-based workloads that cannot be easily containerized. It provides a unified development platform where developers can build, modify, and deploy applications residing in both Application Containers as well as Virtual Machines in a common, shared environment."


### More Useful Website Features

Other things it's good for your website to have, with the understanding that you won't be able to include/maintain all of them:

* Project slogan
* List and summary of key features
* Information about the latest release
* Full information page about your community and how to join it
* Project blog
* Upcoming or recurring events, including community meetings and conferences
* An intro video
* Links to additional videos
* Information around any affiliations you might have, like foundation membership or sponsors
* Quotes from users
* Trademark policy and downloadable graphics
* Code of conduct

## Graphics and Logo
