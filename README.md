# reproducible R workflows for ecologists

## Aims:

Towards implementing reproducible workflows for computational Ecology projects in R.

WHY? Reproducibility is a buzz word in ecology, and science more broadly, at the moment -- but how does one actually go about implementing a fully-reproducible workflow in your computation projects with R?

### End-points:

- document / guide accessible to new and existing Qaecologists and Cebranalysts
- blog-post
- new knowledge / skills for attendees, if not able to walk away and impement, then knows where to look, who to ask in the lab, and how to start thinking about 

### Discussion Points

1. What do we want from today, why are people here? What did you think this was about.
2. What is reproducibility (touch on this briefly, people have covered this elsewhere) and do we do it?
3. Who actually implements reproducibility? Fully reproducible, some steps reproducible but not the whole product (e.g. report + data analysis)? Do you do this with every project? Some projects?
4. Why do you do this? More importantly, why DON'T you do this (hunch: don't know how, don't understand how, don't know where to look)
5. Towards a holistic conceptual model / workflow of data analysis -- Why: Even if parts of your workflow reproducible, is the whole thing reproducible? Understanding the separate steps / sequences of steps aids in achieving full reproducibility. What: example workflow from Hadley Wickham's forthcoming book [R for data science](http://r4ds.had.co.nz/diagrams/data-science.png)
6. Common sources of error in a computational ecology project at and between each step (e.g. hand-editing a csv file, hand-editing an image, copying and pasting an image into a document, different versions of the same code, many scripts working in a particular sequence, how to document what each script does?
7. Operationalising a reproducible workflow, what do we neeed from this process?
8. What collection of tools achieve these desirable attributes? (git + version control, e.g. R packages for documenting and porting your functions, vignettes for your reports, organising the structure of your project, Liz's approach of a `run-all.R` script, or what about a more ahem **sophisticated** approach, like the Remake package? GNU-Make for e.g.
9. Towards (a) reproducible workflow(s) in R: How do we mobilise this suite of tools collectively to achieve our main aim of reproducibility in computational ecology projects? 

## Format:

- wholly discussion-based
- guided, yet interactive, walk-through of a reproducible workflow tool for R (Remake) applied to an example problem
- hybrid (first part: discussion, second part: interactive walkthrough)

## Tentative agenda / outline for session:

1. rationale
2. Impediments to operationalising reproducibility
3. A hollistic model / generalisable workflow of tools and steps needed for computational projects
4. Example walk-through problem
