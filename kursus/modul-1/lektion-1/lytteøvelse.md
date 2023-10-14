---
layout: exercise
forLesson: 1
onPageTitle: Lytteøvelse (vokaler)
onPageDescription: Du får lyden til 20 forskellige ord, vælg den rigtige stavemåde.
---
<div>
{% include display/form-start.html %}
{% include display/picture.html
    src="color/colors.jpg"
%}
{% include display/audio.html
    src="color/colors_01.mp3"
%}

Textblok.

{% include inputs/radio.html
    id="iu7ye4stvluodvgr"
    label="Qanoq allattarpaat?"
    options="nisa, niisa"
    randomize="true"
    validation="1"
%}
{% include inputs/checkbox.html
    id="iu7ye4stvluofdsdr"
    label="Qanoq allattarpaat?"
    options="nisa, niisa"
    randomize="true"
    validation="1"
%}
{% include inputs/pairs.html
    array1="biili, illu"
    array2="bil, hus"
%}
{% include inputs/multiinput.html
    id="ouhfe"
    radio=true
    labels="ental, flertal"
    validations="hus, huse"
%}
{% include display/form-end.html %}
{% include display/feedback.html
    message="Godt forsøgt."
%}
</div>