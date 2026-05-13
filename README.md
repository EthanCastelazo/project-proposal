# Group project proposal

**Spring 2026**

Directions:

-   Use your work plan from class to fill in the information below.
-   Practice pulling, making changes, staging/committing/pulling/pushing to the same repo.
-   **Communicate about who is doing what throughout the entire process.**

What you will submit on Friday the 15th:

-   proposal: a link to your forked repository with the completed proposal in the README
-   work plan: your paper plan that you completed in class on Monday the 4th

Use your project proposal to:

-   refer back to the original plan while you are working
-   keep track of high-level changes in structure (e.g. role switching, elective modifications)

Note:

-   your project proposal is subject to change after you learn more about your datasets and what is possible - allow yourselves the flexibility to make adjustments as needed
-   the more detail you can provide in your proposal, the more thorough your feedback will be

## Group members

Ethan Castelazo, Zelda Reif, Alex Gonzales

## Group name (optional):

Abundant Birds

## Topic information and question

**Topic:**

Overall variation in bird species abundance by season based on water elevation, and variation in species abundance by season between taxonomic groups.

**Question(s):**

- How does water elevation effect bird species abundance within the Waterfowl and Shorebird
taxonomic groups?
- How do effects of water elevation on the species abundance of Waterfowl and Shorebird
taxonomic groups vary across seasons?
- How do species abundance results vary within the Shorebird taxonomic group across water years?

Focusing on Shorebirds because it is the largest taxonomic group with highest species abundance. Ecological significance in coastal wetland ecosystems.

Comparing to Waterfowl due to the  similar size (number of species) of the taxon group but with less of an ecological niche than Shorebirds.

**Response variable(s)**

-   species abundance (Shorebirds)
-   compared species abundance between taxonomic groups (Waterfowl and Shorebirds)

## Datasets

**Datasets used:**

-   birds
-   venoco_water

## Figures

**Potential figure 1:**

[ViewPDF](https://github.com/EthanCastelazo/project-proposal/blob/9f9f99e2ffd578247805febce461894d85dbb0df/Potential%20Figure%20pdfs/Potential%20Figure%201.pdf) 

**Potential figure 2:**

[ViewPDF](https://github.com/EthanCastelazo/project-proposal/blob/9f9f99e2ffd578247805febce461894d85dbb0df/Potential%20Figure%20pdfs/Potential%20Figure%202.pdf)

**Potential figure 3:**

[ViewPDF](https://github.com/EthanCastelazo/project-proposal/blob/9f9f99e2ffd578247805febce461894d85dbb0df/Potential%20Figure%20pdfs/Potential%20Figure%203.pdf)


## Data cleaning/wrangling/summarizing plan

-   Read in venoco-water data and birds_csv
-   Mutate each data set to create a shared column by date
-   Join these two data sets by date, left join into birds due to a smaller amount of dates available in the data set (exclude unnecessary data in water data)
-   group by e_bird_group (taxon) and filter to only include Shorebirds and Waterfowl
-   For figure that compares taxons, show compare by season through facet_wrap
- For figure that includes only Shorebird species, mutate a column to create a water year,
then compare species abundance effects by water year using facet_wrap


## Project roles

**Natural history/framing director:**

Zelda

**Stats and visualization director**

Alex

**GitHub/code director**

Ethan

## Elective (not required for all groups or group members)

**Group members completing elective:**

Ethan, Zelda, Alex

**Elective idea:**

Making an informational bird watching bird watching guide pamphlet for NCOS visitors that details what birds are most likely to be seen during each season

**Elective timeline (what you will have completed each week):**

Week 7: Full project proposal

Week 8 (timeline check in): Background write up of historical bird species profile of NCOS

Week 9: Layout design of pamphlet, with spaces designated for figures, illustrations, and background.

Week 10: illustrations completed

Finals week: Final pamphlet completed with illustrations and information on bird species abundance by season.
