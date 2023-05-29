# Ae_aegypti
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Not all black and white" 
       banner="https://iiif.juncture-digital.org/banner/?url=https://live.staticflickr.com/5049/5283441969_a17579aba8_b.jpg" 
              layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

Dengue, a mosquito-borne viral disease, is endemic and prevalent in Singapore. It is also known as break-bone fever, which points to the severe muscle and joint pains that one can get when contracting dengue[^1]. Such is the prominence of this disease that it has become a household name in Singapore, and decades of public health messaging has educated the public well that the culprit of this disease is a “black-and-white mosquito”, the *Aedes aegypti*[^2]. Many will be surprised to know that this species has a non-native origin, given its ubiquitous nature and ability to thrive in Singapore’s urban niches. Weaving together history with scientific evidence, this story traces the challenges of *Ae. aegypti* vector control in Singapore and explores why dengue is still around despite decades of intensive vector control efforts.

## A human-loving mosquito
*Ae. aegypti* is an anthropophilic species. Not only does it feed preferentially on human[^3], it almost exclusively breeds in specialised artificial container habitats such as flowerpots and bath tubs [^4]. They can breed in small amounts of water that are relatively low in organic matter and high in oxygen [^5,6]. Such adaptations have enabled this species to take easy advantage of stagnant water habitats.

The eggs of *Ae. aegypti* are laid just above the waterline of containers and are desiccant-resistant, which means they can survive without water for months at a time[^7]. This form is likely how it was introduced into Singapore, through trade routes carrying artificial containers with accumulated water. Though the first record of it in 1908 in Singapore was as *Stegomyia fasciata*[^8], the description of the mosquito’s distinctive lyre-shaped white scales on its thorax means identification as *Ae. aegypti* is unmistakeable. Despite its medical significance importance and far-reaching impacts on public health now, the first detection of this species on the shores of Singapore was met without much alarm and was merely treated as a new insect record.

<param ve-image 
       label="Stegomyia fasciata" 
       license="public domain" 
       url="https://blog.biodiversitylibrary.org/wp-content/uploads/sites/4/2021/06/Campbell_4-768x679.jpg">
       
<br>
<br>
<br>
<br>

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a visual essay.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References
[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
[^2]: 
