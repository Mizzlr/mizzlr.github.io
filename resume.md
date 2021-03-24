# Résumé: Mushtaque Ahamed

This is Mushtaque Ahamed, a software engineer and tech enthusiast
hailing from Bangalore, India. He has earned degree in B.E.CSE
from PES University.

## Websites:
* [https://mizzlr.github.io](https://mizzlr.github.io)
* [https://mizzlrblog.wordpress.com/](https://mizzlrblog.wordpress.com/)


## Experience

July 2016 - Present

Senior Innovator at [CodeNation Innovation Labs (CNIL)](http://codenation.co.in/)

CNIL provides static code analysis and engineering services to
[Devfactory](https://devfactory.com/) and
[ESW Capital](http://www.eswcapital.com/wp-content/uploads/ESW-Capital-Overview.pdf) at large.

As a part of my work at CNIL, I had solved some of the toughest problems in static code analysis.

### My Projects at CodeNation

1. **Archex**: Automatic Software **Arch**itecture **Ex**pert, that analyzes feedback loops and cycles in Java package dependency, using [Dependency Structure Matrix](https://en.wikipedia.org/wiki/Design_structure_matrix) Layerization. Also, designed a novel approach to resolve cyclic dependency and feedback loops using an algorithm I call Spectral Layerization, that split large packages the right way based on coupling and cohesion between package.

2. **Devpersonality**: Automatic Developer Personality tester, that analyzes source code lines contributed by a developer in a codebase and predicts the personality of developer. This is similar to [Myers-Briggs Personality Test](https://en.wikipedia.org/wiki/Myers%E2%80%93Briggs_Type_Indicator), instead based on [Design Types](http://design-types.net/)

3. **Razer**: A tool automatically shred some size and build time of a docker image. Also reports 500+ coding issues in [Dockerfile](https://docs.docker.com/engine/reference/builder/). The image size reduction is based on dynamic runtime analysis of files being used, monitored using Inotify service in Linux, to retain only the relevant files in docker image.
The build time optimization is based on novel genetic algorithm applied to constrained topological sorting of layers in Dockerfile based of frequency of change and layer-wise build time.

4. **Codegraph**: A source code indexer, that produces rich [Neo4j](https://neo4j.com/) graph database, containing Parse Tree and Semantic information about the codebase. It is used at heart of all code analysis performed at Codenation, by quering the graph database using [Cypher query language](https://www.opencypher.org/).

5. **Duplicate Code Finder**: Automatic static code analyzes tool to find duplication in codebase of several million lines, extremely fast (typically couple of minutes) while being memory efficient. I designed a novel recursive sequence matcher algorithm that matches sequence of hashes computed at statement level using Parse tree from Codegraph.

6. **BRP Fixer**: Automatic code refactoring tool, like a text editor, that fixes bugs in source code. So called Beginners' Rule Pack, a set of about 20 basic issues that beginners face while coding in Java.

7. **Duplicate Code Fixer**: Automatic duplicate code fixer for java, that applied [Extract Method](https://refactoring.guru/extract-method) refactoring technique to eliminate duplicate copies of code and replace it with function calls.

8. **Sococo Blueprints**: automatically generate maps for [Sococo App](https://www.sococo.com/), given a simple Blueprint floorplan file. This cut down the end to end time to design a new Map for sococo by 50%. Novel tools like ipywidgets and voila was used to rapidly prototype and deliver the UI.  

9. **Quantum Retail 5k Rewrite**: [Quantum Retail](http://quantumretail.com/) is an intelligent supply chain optimization software. Currently at 800k lines of java code. Me at codenation, redesigned and rewrote the application under 5k lines leveraging Amazon Glue, Amazon Forecast, Amazon Athena services from AWS. Performed big data analysis of 10TB of customer inventory management data. Optimized supply chain for maximizing expected profit and service level, under warehouse distribution constraints using Non-linear optimization suite called GEKKO.

10. **Live DB Migration using DMS and Scalearc**: We at codenation have clients that want to move there 1600 Database from on-prem to cloud (Amazon RDS). While DMS by AWS provides lives change synchronization, leveraging [Scalearc](https://www.ignitetech.com/scalearc/) the Database load balanced, we execute live switching over of DB traffic from on-prem to cloud database. Also, adding to features of DMS, we automatically migrate remaining Schema objects that DMS did not migrate. (Currently this project is in progress, end date is April 16 2021).

## Education
Jan 2012 - July 2016
Bachelor in Computer Science and Engineering form PES University.
Read my [impressive résumé](/assets/resume.pdf) at the beginning of my career.

## Technical Skills

* Languages: Python, Java, Javascript, MySQL, Neo4j Cypher
* File formats: JSON, XML, SVG
* Frameworks: Django, Flask, Spring Boot
* OS: Linux/ Mac/ Docker
* Cloud: AWS/ GCP/ Kubernetes
