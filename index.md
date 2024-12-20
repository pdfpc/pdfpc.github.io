---
layout: default
title: pdfpc
---

### About

pdfpc is a GTK-based presentation viewer which uses Keynote-like multi-monitor
output to provide meta information to the speaker during the presentation. It
is able to show a normal presentation window on one screen while showing a more
sophisticated overview on the other one, providing information like a picture
of the next slide, as well as the time left in the presentation. pdfpc
processes PDF documents, which can be created using nearly all modern
presentation software.

### Screenshots

<center>
<figure>
  <a href="{{ site.url }}/screenshots/pdfpc-presenter.png">
  <img src="{{ site.url }}/screenshots/pdfpc-presenter-small.png" alt="Presenter view of pdfpc"/>
  </a>
  <figcaption>Presenter view, showing the current and next slides, remaining time, notes and some additional information.</figcaption>
</figure>
</center>

<center>
<figure>
  <a href="{{ site.url }}/screenshots/pdfpc-overview.png">
  <img src="{{ site.url }}/screenshots/pdfpc-overview-small.png" alt="Overview of pdfpc"/>
  </a>
  <figcaption>Overview mode showing all the slides in the presentation</figcaption>
</figure>
</center>


### News

* December 2024: pdfpc 4.7.0 release
* December 2022: pdfpc 4.6.0 release
* December 2020: pdfpc 4.5.0 release
* November 2020: pdfpc 4.4.1 release
* February 2020: pdfpc 4.4.0 release
* June 2019: pdfpc 4.3.4 release
* June 2019: pdfpc 4.3.3 release
* February 2019: pdfpc 4.3.2 release
* January 2019: pdfpc 4.3.1 release
* December 2018: pdfpc 4.3.0 release
* October 2018: pdfpc 4.2.1 release
* October 2018: pdfpc 4.2 release
* May 2018: pdfpc 4.1.2 release
* May 2018: pdfpc 4.1.1 release
* October 2017: pdfpc 4.1 release
* August 2017: pdfpc 4.0.8 release
* June 2017: pdfpc 4.0.7 release
* February 2017: pdfpc 4.0.6 release
* January 2017: pdfpc 4.0.5 release
* November 2016: pdfpc 4.0.4 release
* October 2016: pdfpc 4.0.3 release
* February 2016: pdfpc 4.0.2 release
* November 2015: pdfpc 4.0.1 release
* June 2015: pdfpc 4.0 release
* February 2015: continued work on davvil's pdfpc
* July 2012: pdfpc 3.1.1 released (bugfix release)
* June 2012: pdfpc 3.1 released
* May 2012: pdfpc 3.0 released

### Features

The most relevant features of pdfpc are:

* Shows current and next slide
* Support for notes, both as text and on slides (as generated by LaTeX beamer)
* Support for overlays (e.g. as generated by the beamer LaTeX package)
* Timer or countdown showing remaining time in the presentation
* Overview mode for quick switching between slides
* Freezing and turning off the presentation view
* Customizable keybindings, enabling support for different presenter devices
* Video playback support

To get a better feeling of pdfpc, install it, download the [demo
presentation](https://github.com/pdfpc/pdfpc/releases/latest/download/pdfpc-demo.pdf) and start it with

{% highlight bash %}
$ pdfpc pdfpc-demo.pdf
{% endhighlight %}

or try [an example with movies](https://github.com/pdfpc/pdfpc/releases/latest/download/pdfpc-video-example.zip) and start it with

{% highlight bash %}
$ pdfpc video-example.pdf
{% endhighlight %}

### Getting pdfpc

At our [GitHub Page](https://github.com/pdfpc/pdfpc). there is an extensive description on how to get pdfpc.

### Acknowledgements

pdfpc is a fork of [pdf presenter
console](https://github.com/jakobwesthoff/Pdf-Presenter-Console) by Jakob
Westhoff. pdfpc 4.0 is the continued work on pdfpc mainly developed by David
Vilar's [pdfpc](https://github.com/davvil/pdfpc).
