# Synopsis

The goal of this initiative is to create an informal incubator for data analytics projects. Undergraduate students can work on projects to develop data analysis, programming, and project management skills. Initially students can work on small research projects or with university data. These projects should prepare them to work as interns with industry partners and give them practical project tangible outcomes they can use as a portfolio. The long term reward for us would be that our students can take on programming tasks that we do not have to do and they are involved with the latest data analytics projects in industry. 

# Philosophy

I want to start this initiative from a couple of principles. The main one is that the projects should be easy to check and easy to communicate. This will help us and the students to show off their work and it will build a library of examples for future students. One consequence is that I want to focus on open source tools such as `R` and `python`. I personally have a fondness for the `R` ecosystem because it makes it easy to analyse data, visualise the results, and to put the output on a website or in an interactive dashboard. I am sure that `python` and tools like powerBI 

Another consequence is that I want easily readable documentation for the projects which we can put on a website. This helps with sharing the project with other people who work on the project. There are a number of tools such as [`markdown`][markdown], [`overleaf`][overleaf], [`rmarkdown`][rmarkdown], and [`jupyter`][jupyter] that provide opportunities to write up the process of the projects in non-traditional ways that are easy to share and collaborate on.

Over time, I want the projects to become meta-projects where they involve coming up with tools that helps us manage all the projects. They could be tools for data sharing or remote working together or for tracking performance of projects over time. A student could make an internal dashboard to track the overall progress of the projects.

I also want to make it as easy as possible for students to keep the intellectual property rights to their work. I need to figure this out but I know who I can contact to get this organised. 

A lot of the principles are coming from Melinda Hodkiewitz from the [UWA System Health Lab][SHL] who has set up a similar informal system partly funded by a number of big grants. The funding allowed her to actually pay the students as casual staff. To me this would be the ideal outcome in the long run. That is, to attract funding to pay students for their work. 

# Type of Projects

The initial projects that I have in mind are small things that can benefit the Business School or UWA but which is currently not done because of lack of time and immediate needs. On the other hand, I want to avoid that the students are just for our benefit and the students have nothing to show for. So, I would want to avoid pure data cleaning or data collection exercises. Especially, if we are not paying I see no real benefit for the students from working on data collection. That is more a research assistant job.

The following are a number of examples from my experience but by no means exhaustive.  If there is enough interest from students I would like to put a call out for more projects. The most important limitation is that there should be a clear outcome to the project and a short time frame.

## Data access and organisation

I have a paper with a bunch of simulation results. The paper necessarily only presents a small subset of all the possible results. An enterprising student could merge all the simulation data and make a website where subsets of the data can easily selected and downloaded. 
I personally think that this would be a good exercise for research groups or labs that collect a lot of similar datasets for instance repeated surveys with overlapping questions or lab experiment with the same task but different manipulations. 

## Research output and communication

An additional advantage of merging data and make it easily accessible is that we can visualise the data to communicate our research in a visual interesting way or through an interactive website. I would love to do this for my simulation study! There are already way too many results in that paper but we also left out a lot.

In addition, a student could also make a package or a code page with all the analyses and data cleaning for the results in a paper. The top economics journals already require this but in reality most of these code pages are actually hard to follow or replicate. 

## Administrative data

The university has a lot of administrative data, for instance from publications. A student could combine the publication information with the old and the updated ABDC list and build a dashboard to track the business schools publication track record. Raymond Da Silva Rosa also suggested that something like this could be interesting with some of the internal budgeting data as well. Now, I can see a host of potential complaints with this as well but I am open to building visualisation tools of internal data.

There might also be ways to automate some administrative tasks such as keeping track and inputting marks for a unit and upload it to blackboard.

# Outcomes for students

To make this initiative sustainable in the long term, there needs to be something in it for the students. This is the part that I think is very important to defend. It is easy for us to forget that the students need to find the projects useful as well. 

## Skills development

Most data analysis/programming for beginners advice boils down to look for a problem and try to solve it. Well chosen projects and the right support can help students to develop their programming horizons and skills. To that end, one important issue will be to match the students ^[if they are interested at all!] to the appropriate projects. Some students might have already more experience than others and might learn more from more challenging project.

Documenting and communicating the programming of each project is an important part of this initiative. This will create a living document with helpful advice and concrete examples that future students can use. Even students who are not part of this project.

## Recognition for their work

The student should also get some recognition that they can use to build a portfolio of completed work. This is why it is useful to have a clear outcome for the project and why it should be possible for the student to easily share the proto-type, database, or the visualisations they have made. Work on private or sensitive data is less interesting for this purpose. Nevertheless, as long as the code is shareable or screenshots of the visualisations can be shared, the students can use their work to show off their accomplishments. 

For more advanced projects, I want to investigate what the best Intellectual Property policy is that fits with the general university policy. This is on my Todo list.

## Outside opportunities at the end 

In the end, we should make it easy for students to find internships, placement, or jobs with the skills they have developed. I have already done some exploration but I would want to invest more in this.  

- I know for instance that [Landgate][landgate] has opportunities for internships. They even have a specific program for PhD students who want to transition to an industry job.
- I know that the [Western Power][western-power] innovation group is looking for students to work on keeping track of new technologies and internal trials on a number of dimensions.^[Last year, a Curtin student has worked with them.] These projects are not mission critical but they help the group to have better information and better manage their trials and prototypes.
- Within the business school, we could also exploit the placements in the [professional experience practicum unit][practicum]. I am planning on discussing this further with Peter Robinson. Another program that the university is already involved in is [CEEDWA][ceed]. This is another potential outside opportunity that I would like to pursue.

In summary, I would like this initiave to form a pathway for students with paid and unpaid internships as a potential outcome. 

# Timeline *or* Things to do 

My data analytics fellowship is meant to be two year. So, I have mapped out what I think should be done in each semester of the two years. The timeline is speculative.

## First semester 2020

- Sorting out Intellectual Property issues.
- Asking for projects from within the university. Not RA jobs.
- Attracting students for projects. First attempts for some projects.
- Fornightly progress meetings
- Thinking of funding opportunities

## Second semester 2020

- Evaluating the first semester and looking for funding
- Centralising internship and placement opportunities.
- Formalising the project proposal process. Especially how to define outcomes and deadlines.
- Formalising the reporting process. It would be cool to have a reporting format with the outcome of the project that is easy to share.
- Creating website to present and show off the projects.

## First semester 2021

If successfull:

- Develop a project management process. How to track and visualise the progress of different projects? Can we collect metrics to figure out what is holding up projects?
- Think about making the iniative sustainable and scalable by formalising some of the governance with student leaders. PhD students are more experienced. We should help with developing some team leader skills but it can also be part of the documentation of the process. 

## Second semester 2021

Basically preparing for handoff and sustaining the project when the fellowship ends.

[ceed]: http://ceed.wa.edu.au/ "CEED"
[jupyter]: https://jupyter.org/ "jupyter"
[landgate]: https://www0.landgate.wa.gov.au/ "landgate"
[markdown]: https://daringfireball.net/projects/markdown/ "markdown"
[overleaf]: https://www.overleaf.com/ "overleaf"
[rmarkdown]: https://rmarkdown.rstudio.com/ "rmarkdown"
[SHL]: https://systemhealthlab.com/ "UWA System Health Lab"
[western-power]: https://westernpower.com.au/energy-solutions/projects-and-trials/ "Western Power Innovation"

