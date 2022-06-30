## GSoC '22 Phase 1.1

### What is Google Summer of Code (GSoC) anyway?

[GSoC](https://summerofcode.withgoogle.com/) is a program, sponsored by Google, to generate interest in and further the development of open-source software packages. Google provides a modest stipend to 'Contributors' who are selected by mentor organizations to contibute to their packages over the summer. Summer 2022 is the first time GSoC has been open to everyone, not just enrolled students!

### How did I get here?

Honestly, twitter. Sometime in February 2022 I had become interested in the open-source geospatial stack. I found [this](https://spatial-analytics.readthedocs.io/en/latest/course-info/introduction.html) spatial analytics with python course by Henrikki Tenkanen and started working through the lessons. This introduced me to geopandas; I was quckly impressed with the package and started following Martin Fleischmann on [twitter](https://twitter.com/martinfleis). Luckily for me he posted about the PySAL GSoC projects and I found one that seemed to be an excellent fit! Despite being a serial internet-lurker and having strong feelings of technical inadequacy, I decided to engage with the community (the horror!) and express my intrest in the spatial optimization library enhancements. After chatting a bit with [Germano Barcelos](https://gegen07.github.io/#/), the GSoC 21' `spopt` student, and receiving encouragement and feedback from the `spopt` mentors my proposal was submitted! 

### Accepted! Now the pre-coding Community Bonding Period

After the initial shock of being accepted wore off all of the PySAL students were encouraged to introduce themselves to the community on the PySAL gitter, I also reached out to my mentors [James Gaboardi](https://github.com/jGaboardi), [Levi Wolf](https://github.com/ljwolf), and [Qunshan Zhao](https://github.com/qszhao) to clear up some environment configuration questions I had and to see how/where they wanted to communicate for the summer. There are four GSoC students this year working on PySAL and two of us are non-student 'freelance' types, awesome! The community bonding period technically runs from May 20 - June 12, 3 weeks! I spent most of my time setting up my development environment, tracing through the spopt library, [studying](https://link.springer.com/book/10.1007/978-3-319-99846-6), [studying](https://www.wiley.com/en-us/Business+Site+Selection%2C+Location+Analysis+and+GIS-p-9780470191064), [studying](https://link.springer.com/chapter/10.1007/978-3-030-58232-6_7), and attending my first PySAL Dev meeting! The week before the coding period began I met with Levi and James for our weekly meeting. It was very productive, they walked me through how the `spopt` library is organized and helped me understand how to begin approaching the problem. They suggested building a script that solves the LSCPB problem and once I had a solution, then it would be time to implement that into the library!

### Coding begins! Phase 1.1 - Implement LSCPB 

My first task was to implement LSCPB in the `spopt` library. Though I had been studying a great deal leading up to the coding period I was still very nervous about the implementation; there is a lot to learn when you're new to optimization, pulp solvers, github, git, object-oriented programming, and probably other things I'm forgetting! The thing is, I have enough experience stretching myself and working through challenging tasks that I was confident I wouldn't fail, it may be hard, but I wouldn't fail, knowing that certainly helped! 


I use Anaconda to setup my python environment. I use VS Code to edit the `spopt` package. I like Jupyter notebooks for deving my code.
Holy shit `pip install -e` both life changing and frustrating! Don't forget __init__.py file!!!
