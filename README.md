# README

This is the README for the XML Prague 2020 presentation by Geert Bormans and Ari Nordström.


## Installing

1. Clone the presentation Git repository from `https://github.com/sgmlguru/xmlprague2020-presentation.git` to somewhere nice (`git clone https://github.com/sgmlguru/xmlprague2020-presentation.git`).
2. Change the working directory to your newly cloned `xmlprague2020-presentation` directory.
3. Do `git clone https://github.com/hakimel/reveal.js.git`.
4. Do `cd reveal.js/`.
5. Run `npm install`.
6. Replace `index.html` with a symbolic link to `../index.html`: `ln -s ../index.html index.html`.
7. Add a symbolic link to `../img/`: `ln -s ../img/ img`.


## Running

1. Run `npm start` in `xmlprague2020-presentation/reveal.js/`.
2. The presentation should open in your default browser.