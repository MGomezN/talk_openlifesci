<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->

<!-- .slide: class="slide-title" data-background-image="assets/title-slide.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h1 id="talk-title">
Good Coding Practices  
</h1>
<p id="talk-authors">
  <a href="https://www.leouieda.com" id="talk-speaker">Mariana Gómez-Nicolás</a>

</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
29 November 2023
<span style="margin: 0 20px"></span>
Open Life Science

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse this presentation
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

</div>
</div>


===============================================================================

# What is "good code"?

Depends on the scope, the context and the lifetime.

===============================================================================

>"In the interests of creating **employment opportunities** in the Java programming field(...), follow all these rules religiously, you will even guarantee yourself a lifetime of employment, since no one but you has a hope in hell of maintaining the code."

 [Unmaintainable code ©2000-2017 Roedy Green](https://www.mindprod.com/jgloss/unmain.html)

<div class="footnote-left dark">

⚠️ Content is intended to be humorous or satirical.

</div>

===============================================================================

> * **Names For Baby**. Buy a copy of a baby naming book and you’ll never be at a loss for variable names. Fred is a wonderful name and easy to type.
>* **Misleading names**. Make sure that every method does a little bit more (or less) than its name suggests.
>* **Single Letter Variable Names**. Nobody will be able to guess what they are for.
>* **CapiTaliSaTion**. Randomly capitalize the first letter of a syllable in the middle of a word.

 [Unmaintainable code ©2000-2017 Roedy Green](https://www.mindprod.com/jgloss/unmain.html)

<div class="footnote-left dark">

⚠️ Content is intended to be humorous or satirical.

</div>

===============================================================================

<!-- .slide: class="slide-transition" -->

# What
## The results of putting your WHY into action
# How
## Your values and strenghts in action
# Why 
## Your purpose cause or belief


<div class="footnote-left dark">

[Simon Sinek](https://simonsinek.com/)


</div>



===============================================================================

# What is "good code"?

Depends on the scope, the context and the lifetime.

Clean Code → Testeable → Maintainable → Extendable 

------- Refactoring ---------

</div>
</div>
<div class="footnote-left">

Detection of code smells play an important role
<br>
Check out this webinar on [Identifying code smells](https://www.youtube.com/watch?v=IzdpizfaVbU)

</div>

===============================================================================

<div class="r-stretch">

# Previous OLS talks

* Yanina Bellini ([What is "Good Code", "smells", "refactoring"](https://www.youtube.com/watch?v=hOiDzn4Iqp4&t=4248s))
* Olaitan Awe ([Writing reproducible code](https://youtu.be/hOiDzn4Iqp4?t=311))
* Leah Wasser ([From scripts to packages](https://youtu.be/hOiDzn4Iqp4?t=1582))
* Gemma Turon ([Code style and code testing](https://drive.google.com/file/d/1w8AUnsbwSpqfEK0YxKmSZGIeIlEbppSN/view))

===============================================================================

<!-- .slide: data-background-image="assets/geolatinas_coding_group.jpeg" data-background-size="contain" data-background-opacity="0.3" data-background-color="#000000" -->

<div class="quote">

<h1>
Come for the <strong>code</strong> <i class="fas fa-code"></i>
<br>
Stay for the <strong>community</strong> <i class="fas fa-users"></i>
</h1>

</div>

===============================================================================

<!-- .slide: data-background-image="assets/communities.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote-center dark">

https://www.cicese.edu.mx
<br>
https://www.geolatinas.org
<br>
https://www.fatiando.org 
<br>
https://carpentries.org
<br>
https://academy.climatematch.io

</div>

===============================================================================



# Good coding practices learned in community

* Scripts 
* Modular 
* Installable


===============================================================================

# Lessons learned in GeoLatinas community

* Coding accountability
* #StrongerTogether Mindset
* Positive Learning Atmosphere
* Diversity in Skills, Unity in Team


===============================================================================
# Lessons learned in CMA

* JupyterBook
* Think about the analysis that has to be done with the databasis
* Don't subestimate creativity of people
* Who is going to use your code? 
* Accesibility statement 

===============================================================================

# Educational materials
* Promote Generalization. Avoid being overly specific to enhance the potential for reuse in diverse educational contexts.

* Avoid Redundancy. No reinventing the wheel

===============================================================================
# Lessons learned in Fatiando a Terra

* Development started in 2010
* 2013 First Documentation generated on Sphinx
* Not designed for testeability 
* Difficult to mantain
* Foundation was unstable to keep growing
* Need to learn software engineer
* 2018 Stop Coding developing, major refactoring


===============================================================================
# Lessons learned in Fatiando a Terra

* Suplement the ecosystem
* Split into libraries
* Every piece of code is a stable foundation to develop the rest
* Use modern tools for testing and generate documentation
* Parallel computing so it can solve complex problems in small computers
* Deep understanding of the geophysics involve
* State of the art algorthms

===============================================================================

# Documentation

* Documentation is another form of communication within our projects. 
* FAQs section in documentation pages. 

===============================================================================

<!-- .slide: class="slide-transition" -->

# Once upon a time, 
# there was a major release on Zenodo
# October 13, 2023

<div class="footnote-left dark">

[Zenodo](https://zenodo.org/)

</div>

===============================================================================

# Pooch-Zenodo issue
* Zenodo migrated to InvenioRDM
* Their new API was not backward compatible 
* Pooch Zenodo downloader was not working anymore

> Dramatic music 

===============================================================================

<!-- .slide: data-background-image="assets/2.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote-center dark">

https://zenodo.org/
<br>
</div>


===============================================================================

<!-- .slide: data-background-image="assets/3.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote-center dark">

https://github.com/fatiando/pooch/issues/371
<br>
</div>

===============================================================================

<!-- .slide: data-background-image="assets/4.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote-center dark">

https://github.com/fatiando/pooch/pull/375
<br>
</div>

===============================================================================

<!-- .slide: data-background-image="assets/agu2019.svg" data-background-size="contain" data-background-opacity="0.3" data-background-color="#ffffff" -->

<div class="quote dark">

 "[Final lesson learned: Friday the 13th[**] might not have been a good day for a major release after all.](https://blog.zenodo.org/2023/10/19/2023-10-19-upgrade-issues/)" 

</div>

===============================================================================

<!-- .slide: data-background-video="assets/cicese.webm" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch">
</div>
<div class="footnote-center dark">

[Ensenada Center for Scientific Research and Higher Education]((https://www.cicese.edu.mx/)

</div>

===============================================================================

<!-- .slide: class="slide-contact" data-background-image="assets/contact-slide.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contact: mariana@cicese.edu

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[github.com/MGomezN/talk_openlifesci](https://github.com/MGomezN/talk_openlifesci)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>
<div class="footnote-left dark">

Thanks to [Leonardo Uieda](https://github.com/leouieda/talk-template) to provide original source code

</div>
