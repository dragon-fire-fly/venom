# Love Venom Testing

Click [here](README.md) to return back to the README.md

# Contents

# Browser Compatibility



# Code Validation
## HTML
### Home page
![Home](documentation/testing/html-home.png)

### Intermediate pages
- Vertebrates

![Vertebrates](documentation/testing/html-vertebrates.png)

- Invertebrates

![Invertebrates](documentation/testing/html-invertebrates.png)

### Information pages
- Reptiles

![Reptiles](documentation/testing/html-reptiles.png)

- Amphibians

![Amphibians](documentation/testing/html-amphibians.png)

- Fish

![Fish](documentation/testing/html-fish.png)

- Mammals and Birds

![Mammals-and-birds](documentation/testing/html-m-and-b.png)

<!-- spiders
scorpions
insects
marine -->


### Contact page
<!-- contact ![](documentation/testing/html-) -->
![Confirmation](documentation/testing/html-confirmation.png)


## CSS validation


## Lighthouse Tests
### Home page


### Intermediate pages

### Information page

### Contact page

# Accessibility
The [Eightshapes](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FFFFFF%2C%20White%0D%0A%23000000%2C%20Black%0D%0A%23dde7c7%0D%0A%2382a89c%0D%0A%2373b8cc%0D%0A%2302789e%0D%0A%23003859%0D%0A%23126100%0D%0A&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) contrast grid generator was used to assess suitability of chosen colour scheme to ensure good accessibility scores were achieved. The scores for all colour combinations used were at least 5.5 (pass, AA), and the combinations used for smaller texts scored at least 9 (pass, AAA)

![eightshapes-grid](documentation/testing/contrast-grid-annotated.jpg)

# Responsiveness




# Bug Fixes
## Overflow-x problem
Whilst testing the website, an x-overflow was discovered (a scrollbar appeared along the x-axis). 

![overflow-x](documentation/testing/overflow-x.png)


This bug was created when attempting to centre the "Back to top" element. The margin-left: -60px seemed to be causing the width of the footer to be larger than the width of the main body, as seen below:

![back-to-top](documentation/testing/overflow-x-issue.jpg)


This issue was fixed by removing the marign-left and using the code above to properly centre the "Back to top" element, using "fit content" and "margin: 0, auto" properties instead. This fixed the overflow-x issue.


## Unfixed Bugs

<!-- iPad landscape issue? -->