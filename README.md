Files for our participation at [PyconFR, Lyon, oct 2014](http://www.pycon.fr/2014/schedule/presentation/37/).

To show the presentation:

* clone this repo
* cd in the repo, then run:
    ```
    git submodule init
    
    git submodule update
    ```
This will clone the reveal.js repo as a submodule
* Bootstrap
* jquery
* copy the videos in talk/vid
* From the repository root, run:
    ```
    python -m SimpleHTTPServer 8765
    ```
* open a browser at http://localhost:8765/talk
