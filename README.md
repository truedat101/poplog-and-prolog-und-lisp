# poplog-and-prolog-und-lisp

Unfortunately there are a lot of dead links in the world of languages that had their run between 1960-1990.  This Repo will just keep some things in the repo itself so it isn't possible for the links to go dead since nothing that goes in here will get removed without reason.  Machine learning that can make adjustments on the fly in behavior is something that needs to be revisited ... i.e. ability to learn on the fly, without using months of expensive compute.  How can we introduce GPU support into an older language that has been on the shelf?  How does the approach change when we can say we have near infinite cheap RAM and disk to throw at the problem.  Why were these systems abandoned?  Is there still life?

## Why poplog (pop11)

- It was designed as a learning tool
- It has been used to write 3 languages: Prolog, ML, and Common Lisp.
- It is incrementally compiled, and quite fast in terms of start up time
- It can load files on the fly, edit on the fly, modify itself

## Disclaimer

I have no association with the project.  I once studied prolog in college along with lisp, however, I was focused on procedural programming and this didn't fit in my world view.  I am revisiting this topic.  I am a bit frustrated that the university of burmingham removed a lot of the links and let link rot prevail.  Everything is still up however, many links are broken.  A warning to profs and researchers.  Mirror your stuff.  As soon as you are gone, someone will take it down, move it, etc.  Hypertext works when people think about the impact of not wrecking internet history.

It isn't industrial grade, and doesn't currently stack up well against other prologs in terms of modern features.  And yet ... just a quick tinkering around with this, it is extremely flexible.   This needs a second look.

The other thing is because of all of the broken links, and personal websites hostings stuff, I am concerned about the curation of this content.  The personal websites are the first to go if they are hosted on a personal domain, and the person happens to pass on or just decides to stop maintaining the site.  Wayback is fantastic for recovery, but better to keep it hosted publicly on a site that isn't taking down content, like Github.

## Start Here

- https://github.com/GetPoplog/Seed
- Number one problem is figuring out VED/XVED: https://www.cs.bham.ac.uk/research/projects/poplog/ved-docs/
- Number two problem is exiting VED: https://www.cs.bham.ac.uk/research/projects/poplog/junk/linux15.6/current-poplog/pop/help/exit
- Or here ...

## Books

TODO

## Preserved Source

- [ ] TODO: checkin and link locally from Eliza Source: http://hakank.org/poplog/poprulebase_toy_eliza.p
- [ ] GOSPL: https://github.com/sfkleach/GOSPL (TODO: Verify if this is the latest ... it is about 12 years old)

## Eliza, many implementations

- A great prolog rewrite with a walk through of the implementaiton: https://www.like-a-boss.net/2018/08/24/eliza-a-tutorial-reconstruction-in-prolog.html

## Other Prolog Resources

- TODO

## Projects

- [ ] TODO: Fork poplog for pull request to fix Ubuntu build issues on 22.04
- [ ] TODO: Add a Mac port of the poplog system.  Minimally, this just needs the console app.
- [ ] TOOD: Add a new Graphics UI based on BGFX / IMGUI / SDL
- [ ] TODO: CUDA support?
