# alda-laboratory

A place to make music with Alda and Clojure.

## Usage

1. Install OpenJDK
2. Install Alda (https://github.com/alda-lang/alda)
   * Quick version:
     ```bash
     wget https://github.com/alda-lang/alda/releases/download/1.3.3/alda -P /usr/local/bin
     chmod +x /usr/local/bin/alda
     ```
3. Fix JVM midi soundfont (https://github.com/alda-lang/alda#midi-soundfonts)
   * Quick version:
     ```bash
     wget https://raw.githubusercontent.com/alda-lang/alda/master/scripts/install-fluidr3
     chmod +x install-fluidr3
     ./install-fluidr3
     rm install-fluidr3
     ```
4. Install lein (https://leiningen.org/)
5. Install Emacs and Cider (https://github.com/clojure-emacs/cider)
6. Start the Alda server (`alda up`)
7. In Emacs: `M-x cider-jack-in`, open `src/alda-laboratory/core.clj`,
   and execute forms with `C-c C-c` or `C-x C-e`.
8. ???
9. Music?

## License

Copyright © 2019 Ben Denham

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
