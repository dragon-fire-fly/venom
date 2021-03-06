# Love Venom Testing

Click [here](README.md) to return back to the README.md

# Contents

# Browser Compatibility
The website was tested on [Google Chrome](https://www.google.com/chrome/) and [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)

All screenshots in the [README.md file](README.md) were taken using the [Google Chrome](https://www.google.com/chrome/) browser and below are a few screenshots from [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/):

Home page:
![Home](documentation/testing/index-firefox.png)

Vertebrates page:
![Vertebrates](documentation/testing/vertebrates-firefox.png)

Contact page:
![Contact](documentation/testing/contact-firefox.png)


# Code Validation
## HTML
The HTML code for each page was checked using the [W3 HTML validator](https://validator.w3.org/)
All pages passed validation with no errors.
### Home page
![Home](documentation/testing/html-w3-validation-tests/index-w3.png)

### Intermediate pages
- Vertebrates
![Vertebrates](documentation/testing/html-w3-validation-tests/vertebrates-w3.png)

- Invertebrates
![Invertebrates](documentation/testing/html-w3-validation-tests/invertebrates-w3.png)

### Information pages
- Reptiles
![Reptiles](documentation/testing/html-w3-validation-tests/reptiles-w3.png)

- Amphibians
![Amphibians](documentation/testing/html-w3-validation-tests/amphibians-w3.png)

- Fish
![Fish](documentation/testing/html-w3-validation-tests/fish-w3.png)

- Mammals and Birds
![Mammals-and-birds](documentation/testing/html-w3-validation-tests/mammals-birds-w3.png)

- Spiders
![Spiders](documentation/testing/html-w3-validation-tests/spiders-w3.png)

- Scorpions
![Scorpions](documentation/testing/html-w3-validation-tests/scorpions-w3.png)

- Insects and Other Arthropods
![Insects](documentation/testing/html-w3-validation-tests/insects-w3.png)

- Marine Invertebrates
![Marine-invertebrates](documentation/testing/html-w3-validation-tests//marine-inverts-w3.png)


### Contact page
- Contact Page
![Contact](documentation/testing/html-w3-validation-tests/contact-w3.png)
- Confirmation Page
![Confirmation](documentation/testing/html-w3-validation-tests/confirmation-w3.png)

## CSS validation
The CSS code was passed through the [W3C Validation Service](https://jigsaw.w3.org/css-validator/) and passed with no errors.

![CSS-validation](documentation/testing/css-validation.png)
<p>
    <a href="https://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

## Lighthouse Tests
<!-- The SEO score is highly affected by the java menu using a fontawesome icon making the link "uncrawlable". Most of the page at or aroun 90% so deemed ok.-->
<!-- Could improve Performance scores by reducing size of image and/or changing file format to a next-gen format such as WebP or AVIF. Given the performance scores were still over 90% and the purpose of the website to serve high quality images that users may wish to download, these changes were not made. -->
For each Lighthouse Test, the page was tested in both mobile and desktop versions. Both scores are displayed below with the mobile scores followed by desktop:
### Home page
![Home-page-mobile](documentation/testing/lighthouse-tests/index-mobile.png)
![Home-page-web](documentation/testing/lighthouse-tests/index-web.png)

### Intermediate pages
- Vertebrates
![Vertebrates-mobile](documentation/testing/lighthouse-tests/vertebrates-mobile.png)
![Vertebrates-web](documentation/testing/lighthouse-tests/vertebrates-web.png)

- Invertebrates
![Invertebrates-mobile](documentation/testing/lighthouse-tests/invertebrates-mobile.png)
![Invertebrates-web](documentation/testing/lighthouse-tests/invertebrates-web.png)

### Information page
- Reptiles
![Reptiles-mobile](documentation/testing/lighthouse-tests/reptiles-mobile.png)
![Reptiles-web](documentation/testing/lighthouse-tests/reptiles-web.png)

- Amphibians
(Bad SEO score)
![Amphibians-mobile](documentation/testing/lighthouse-tests/amphibians-mobile-1.png)
![Amphibians-web](documentation/testing/lighthouse-tests/amphibians-web.png)

- Fish
(Bad SEO score)
![Fish-mobile](documentation/testing/lighthouse-tests/fish-mobile-1.png)
![Fish-web](documentation/testing/lighthouse-tests/fish-web.png)

- Mammals and Birds
![Mammals-and-birds-mobile](documentation/testing/lighthouse-tests/mammals-birds-mobile.png)
![Mammals-and-birds-web](documentation/testing/lighthouse-tests/mammals-birds-web.png)

- Spiders
![Spiders-mobile](documentation/testing/lighthouse-tests/spiders-mobile.png)
![Spiders-web](documentation/testing/lighthouse-tests/spiders-web.png)

- Scorpions
![Scorpions-mobile](documentation/testing/lighthouse-tests/scorpions-mobile.png)
![Scorpions-web](documentation/testing/lighthouse-tests/scorpions-web.png)

- Insects and Other Arthropods
![Insects-Arthropods-mobile](documentation/testing/lighthouse-tests/insects-mobile.png)
![Insects-Arthropods-web](documentation/testing/lighthouse-tests/insects-web.png)

- Marine Invertebrates
![Marine-Invertebrates-mobile](documentation/testing/lighthouse-tests/marine-mobile.png)
![Marine-Invertebrates-web](documentation/testing/lighthouse-tests/marine-web.png)

### Contact page
- Contact Page
(bad score)
![Contact-mobile](documentation/testing/lighthouse-tests/contact-mobile-1.png)
![Contact-web](documentation/testing/lighthouse-tests/contact-web.png)

- Confirmation Page
(bad score)
![Confirmation-mobile](documentation/testing/lighthouse-tests/confirmation-mobile-1.png)
![Confirmation-web](documentation/testing/lighthouse-tests/confirmation-web.png)

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