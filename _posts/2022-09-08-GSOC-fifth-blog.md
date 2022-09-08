## GSoC '22 Final Report

My GSoC ‘22 project was focused on contributing enhancements to [PySAL’s spopt](https://pysal.org/spopt/) package. My goal was to implement new models to further extend the capabilities of the package as well as add additional parameters that would extend the practical application of existing models for users.

### What did I accomplish?
I made three significant pull requests over the course of the GSoC program. My [first pull request](https://github.com/pysal/spopt/pull/259) implemented the LSCP-B model, via the LSCPB class, which is commonly used in planning for emergency services. This class builds off of the spopt LSCP class which was implemented by [Germano Barcelos](https://github.com/gegen07) (GSoC student ‘21) and adds additional constraints to ensure demand nodes have a backup facility assigned to them.

My [second pull request](https://github.com/pysal/spopt/pull/268) implemented the P-Dispersion model via the PDispersion class. This model is an anti-covering location problem which selects facilities that maximize the minimum distance between facilities. It is typically used in the siting of undesirable, but necessary, facilities such as waste sites, incinerators, or nuclear power plants.

My [third pull request](https://github.com/pysal/spopt/pull/273), which will be merged after the official GSoC ‘22 timeline, adds capacity constraints as a parameter to the existing LSCP class. The addition of the capacity constraints will allow for the class to solve more realistically for real world location allocation situations and fill an enhancement gap that users have expressed interest in. Though this implementation may present as a simple enhancement to an existing class, it was a bit tricky and required input from my mentor [Levi Wolf](https://github.com/ljwolf) on both implementation strategy and properly building what amounts to, essentially, a new PuLP model to represent the problem properly. 

### What's left?
Merging my third pull request for the capacity constraints is a top priority for me. I’d like the pull request to mirror my previous implementations. This will include writing tests and creating a full set of rnotebooks and documentation for the LSCP capacity parameters.


