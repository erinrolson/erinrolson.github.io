## GSoC '22 Phase 1.1 continued...

### How long can a PR take anyway?

Well, let me tell you, it can take awhile! At the end of my last blog post I had submitted my PR for the LSCP-B implementation and was fairly confident I'd quickly tie up a few loose ends and be moving on to the P-Dispersion problem in no time. Ha! Let me tell you about my last 4 weeks...

## Coding - Week 4

This week (July 3 - 10) was my designated week off, but I still worked a small amount and attended our weekly meeting (Qunshan, Levi, James). During the meeting we focused on the tests that I would need to implement for the LSCPB class and the [Real World Facility Backup Coverage Location Problem notebook](https://github.com/pysal/spopt/blob/main/notebooks/facloc-lscpb-real-world.ipynb) I needed to implement. I prioritized implementing the tests first since I wasn't familiar with the testing environment the spopt package uses and I hadn't written tests before. It took a bit of effort to get the tests to execute but, as always, my mentors were responsive to my questions and helped me get going quickly. After executing the tests for the first time, before making any changes to them, I knew something was amiss. I was receiving errors on established spopt classes, and on files that I never made changes to. I proceeded anyway and was I was able to get quite a few tests outlined for my new class and learned about pickle files since they are necessary for the testing workflow. 

