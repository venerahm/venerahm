# Hi, I'm Hanna Venera!

<img align='right' src="https://media.giphy.com/media/tkEaYA3Kd5WtyXtLqu/giphy.gif" width="230">

### PhD Candidate at <a href="https://sph.umich.edu/biostat/">University of Michigan</a> <img src="https://media.giphy.com/media/Cz6xnJ5sutPDWVDUGj/giphy.gif" width="30">

[![Linkedin: venerahm](https://img.shields.io/badge/-venerahm-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/venerahm/)](https://www.linkedin.com/in/hanna-venera-197720196/)
[![GitHub venerahm](https://img.shields.io/github/followers/venerahm?label=follow&style=social)](https://github.com/venerahm)
[![Website](https://img.shields.io/badge/Website-venerahm.github.io-blue?logo=google-chrome&style=social)](https://venerahm.github.io/)

#### A little more about me... 

```r
biostat_candidate <- list(
  name = "Hanna",
  pronouns = "she/her",
  role = "PhD Candidate, Biostatistics",
  degrees = c("MS Biostatistics (UMich)", "BA/BS (Pacific Lutheran Univ)"),
  interests = c("dog lover", "foodie"),
  code = "R"
)

say_hi <- function(person) {
  cat(
    "Hi! I'm", person$name, "-", person$role, "\n",
    "Pronouns:", person$pronouns, "\n",
    "Degrees:", paste(person$degrees, collapse = " | "), "\n",
    "Interests:", paste(person$interests, collapse = ", "), "\n",
    "Code:", person$code, "\n"
  )
}

say_hi(biostat_candidate)
``` r
