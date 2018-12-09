---
layout: gallery
title: Loudness Subtraction
no_menu_item: true # required only for this example website because of menu construction
support: [jquery, gallery]
---

Loudness Extraction using [libxtract][vamp] in [sonic-annotator][sonic].
Plotted in python using sonic-annotator vamp extraction features and spectrogram visualisation by [Frank Zalkow][frank].
You can find code and instructions [here][code].

{% include gallery-layout.html gallery=site.data.galleries.loudness-subtraction %}

All images licensed under [CC-BY-NC-SA license][license].
Image gallery implemented in jekyll based on [opieters][repo].

[frank]: http://www.frank-zalkow.de/en/code-snippets/create-audio-spectrograms-with-python.html
[code]: https://github.com/amilo/audio-analysis
[sonic]: https://www.vamp-plugins.org/sonic-annotator/
[vamp]: https://code.soundsoftware.ac.uk/projects/vamp-libxtract-plugins
[license]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[repo]: https://github.com/opieters/jekyll-gallery-example
