## GSoC '22 Phase 1.1 continued...

### How long can a PR take anyway?

Well, let me tell you, it can take awhile! At the end of my last blog post I had submitted my PR for the LSCP-B implementation and was fairly confident I'd quickly tie up a few loose ends and be moving on to the P-Dispersion problem in no time. Ha!

## Coding - Week 4

This week was my designated week off, but I still worked a small amount and attended our weekly meeting with Qunshan, Levi, and James. We focused on the tests that I would need to implement for the new LSCPB class and the [Real World Facility Backup Coverage Location Problem notebook](https://github.com/pysal/spopt/blob/main/notebooks/facloc-lscpb-real-world.ipynb) I needed to implement. I prioritized implementing the tests first since I wasn't familiar with the testing environment the spopt package uses and I hadn't written tests before. It took a bit of effort to get the tests to execute but, as always, my mentors were responsive to my questions and helped me get going quickly. After executing the tests for the first time, before making any changes to them, I knew something was amiss. I was receiving errors on established spopt classes, and on files that I never made changes to. I proceeded anyway and was able to get quite a few tests outlined for my new class. In order to write my tests I learned about [pickle](https://docs.python.org/3/library/pickle.html), a clever module for serializing and de-serializing Python objects. This is useful for the testing workflow because you can save an object created on a known working process and compare that object to the object instance that is created when a test is run. Object attributes should remain consistent and a deviation in attribute values will produce an error.

## Coding - Week 5

Back from my time off I was ready to jump in and polish off the PR - enter the environment issues. I think anyone who has spent time programming has probably run up against environment / package dependecy / version issues - this seems to be compounded when dealing with the geospatial stack. Suffice to say I lost a good bit of time troubleshooting, testing, comparing, and eventually rebuilding my environment (probably more than once). A lot of the pain I've experienced in getting my environment set up is no doubt realated to my lack of experience with the packages needed, expectations for instal times, etc., but also, sometimes packages don't install properly! `conda install --channel conda-forge` use it. And if that doesn't work, go straight to the package's github repo. Lesson learned.

## Coding - Week 6


