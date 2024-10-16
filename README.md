# GPT2 Sensitivity to Western Time Metaphor Violations

## Project Overview

This project aims to test whether or not GPT2 is sensitive to violations of Western time metaphors, seeking to test an LLM from a perspective of embodied cognition. 

All languages have the capability to deal with the concept and issue of time, including duration, deictic time, and sequence time. Most commonly, languages use the metaphor "time as space" in order to effectively communicate about the topic. In particular, Western languages most commonly use a front (future) - back (past) orientation with a much less left (past) - right (future) orientation. Rarer still is an up (future) - down (past) orientation. This is reflected in phrases such as "the weeks **ahead** of us," "the worst is **behind** us," "**next** week," "stories passed **down** from generation to generation." These metaphors even extend beyond language into our embodied cognition. Studies involving time and gesture showed congruency with these metaphors - words like "tomorrow" were accompanied by gestures forwards or to the right while words like "yesterday" were accompanied by gestures behind or to the left. Thus, for a native speaker of English, a sentence such as "That was way back in 1900" fits with the metaphors we use for time far better than a sentence such as "That was way forward in 1900", or "That was way down in 1900". The later two sentences would be what I am considering a violation of Western time metaphors for this project. 
## Installation and Setup
### Codes and Resources Used

- **Editor Used:**  Anaconda
- **Python Version:** Python 3.11.5

### Python Packages Used

- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib.pyplot`, `pyplot`, `seaborn`, 
- **Others:** `torch`, `transformers`, `scipy.stats`,`tqdm`
## Data

The data for the stimulus pairs used in this project are created in the "Stimulus Pairs" section of the notebook, stored in the variable `stimuli`. 
## Results and evaluation

GPT-2 in particular is not sensitive to violations of Western time metaphors, indicating that it lacks the same capacities that humans do for this part of language. It is important to note however, that this does not mean that LLMs as a whole are entirely insensitive. Using these stimuli with newer and more powerful LLMs might yield significant results as the field of LLMs continue to improve. Additionally, follow up using stimuli with the time metaphor embedded or even perhaps at the beginning of sentences would provide a more well rounded understanding of LLMs sensitivity to violations of time-metaphors.

Additionally, the insensitivity to time metaphor violations demonstrates human cognition's capacity and sensitivity to them. A violation of them in a sentence is confusing and incongruous to our embodied perspective and understanding of time. Time and its metaphors are not only constantly talked about in day-to-day conversation, but we also "feel" time through its simultaneity, its duration, remembered events, and predicted events to name a few. We incorporate these metaphors into our gestures and cannot ignore spatial cues when asked to make time judgments. Thus, perhaps due to this consistent exposure to time metaphors and our embodied perspective of it, humans have access to and a fluidity in information that an LLM cannot necessarily get in its training data.

## Future work
- Use GIS software to produce better and more accurate maps that would better reflect a metro-area that isn't forced into a particular state boundary.
- Pair this demographic data with HOLC grades with other issues such as food insecurity, social vulnerability, life expectancy, etc. 
- Map across time using census data from other years to examine how segregation patterns have changed across time.

## References
- Parts of code adopted from [Sean Trott's](https://seantrott.github.io/) COGS 150 course - sttrott@ucsd.edu
- Radden, G. (2003). The metaphor TIME AS SPACE across languages. Zeitschrift für interkulturellen Fremdsprachenunterricht, 8(2).
- Walker, E., & Cooperrider, K. (2016). The Continuity of Metaphor: Evidence From Temporal Gestures. Cognitive Science, 40(2), 481-495. [https://doi.org/10.1111/cogs.12254](https://doi.org/10.1111/cogs.12254)
- Duffy, S. E., & Feist, M. I. (2023). Time in Space: Cross-Linguistic Variation and Metaphor. In Time, Metaphor, and Language: A Cognitive Science Perspective (pp. 50– 81). chapter, Cambridge: Cambridge University Press.
- Cooperridder, K., & Núñez, R.(2016). How We Make Sense of Time. Scientific American.
## License
[MIT License](https://opensource.org/license/mit/)
