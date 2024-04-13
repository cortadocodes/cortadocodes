### Hi there, I'm cortadocodes 👋

![Cortadocodes' GitHub stats](https://github-readme-stats.vercel.app/api?username=cortadocodes&show_icons=true&theme=transparent&rank_icon=percentile&hide=stars&include_all_commits=true&number_format=long&show=prs_merged&custom_title=GitHub%20stats)

### About me
I'm a Senior Software Engineer at [Octue](https://octue.com) where I build data and cloud solutions for scientists. My work focuses
on automating various parts of the wind industry (and sometimes other renewable energy tech) and, as a big fan of FOSS, 
I'm happy that the majority is open-source.

### What I've been up to

- Dockerising [OpenFAST](https://github.com/OpenFAST/openfast/pull/2121) (NREL's wind turbine and wind farm simulation software) to aid its deployment as part of a serverless cloud analysis pipeline, making analyses highly parallelisable, automatable and highly scalable - all without the need for costly permanent infrastructure     
- Building the [Twined framework](https://github.com/octue/octue-sdk-python) - an event-driven digital twin / microservices framework for easily running serverless digital twins and data services for renewable energy research and engineering
  - Powers @WindPioneers' [WindQuest](https://www.wind-pioneers.com/services/windquest-smarter-tools/) wind farm design software
  - Runs our OpenFAST and TurbSim docker containers serverlessly as data services
  - Populates our global Elevations API (see below)
- Improving [WindQuest's](https://www.wind-pioneers.com/services/windquest-smarter-tools/) staff admin app, leading to a speed-up of regular repetitive staff workflows of 6x and a significantly nicer UI for staff to use
- Creating a global [Elevations Service](https://github.com/octue/windeurope72hours-elevations-populator), [API](https://github.com/octue/windeurope72hours-elevations-api) and [python client](https://github.com/octue/windeurope72hours-elevations-client-python) that uses the [NASA Copernicus dataset](https://dataspace.copernicus.eu/) and the [H3 hexagonal hierarchical coordinate system](https://h3geo.org/) to provide the elevation of any coordinate on the planet
- Creating GraphQL APIs for our JSON schema version control and publishing system [Strands](https://strands.octue.com/) and some exciting upcoming apps...
- Working on our [other tools](https://www.octue.com/tools)

### Skills
- Cloud computing and communication with a focus on event-driven serverless microservices  
- Containerisation/dockerisation
- Writing REST and GraphQL django APIs
- Writing and publishing python libraries
- Writing data services to automate and scale previously manual data processing
- Automating devops with GitHub Actions, pre-commit, and others

### My approach
- Test-driven
- Modular
- Automated CI/CD
- [Conventional Commits](https://github.com/octue/conventional-commits) for automated semantic releases and release notes
- Clean coding
- DRY, YAGNI
