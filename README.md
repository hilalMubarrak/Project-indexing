# Project-indexing

## Image-Search-Engine and Text-Indexing (swish-e)

1. Image-Search-Engine
   - Requirement:
      * `sudo apt-get python3`
      * `pip install flask`
      * `pip install opencv`
   - How to run program
       * go to engine directory
       * `cd image-search-engine-master`
       ![Selection_013](https://user-images.githubusercontent.com/46868237/66748775-39092200-eeb2-11e9-8a01-c5c696376dec.png)
       * `pip install -r requirement.txt`
       ![Selection_014](https://user-images.githubusercontent.com/46868237/66748844-65bd3980-eeb2-11e9-81b2-2d70d52791ec.png)
       * open index.csv to check output
       ![Selection_022](https://user-images.githubusercontent.com/46868237/66751120-7a043500-eeb8-11e9-89b2-f174bbb2e59e.png)
       * go to `/static/images` to modify your images
       * run `app.py` with python to start images indexing
       ![Selection_015](https://user-images.githubusercontent.com/46868237/66752751-68249100-eebc-11e9-9baa-fc3975f8e02d.png)
       ![Selection_016](https://user-images.githubusercontent.com/46868237/66752757-69ee5480-eebc-11e9-84eb-55d3ced28c1d.png)
       ![Selection_018](https://user-images.githubusercontent.com/46868237/66752761-6ce94500-eebc-11e9-896f-5ce549dcc386.png)
       * open link `http://0.0.0.0:5000/`
       
2.  Text-Indexing
    - Requirement
       * `sudo apt-get install swish-e`
    - How to run the program
       * `mkdir text-indexing`
       * `cd text-indexing`
       
       ![Selection_023](https://user-images.githubusercontent.com/46868237/66754190-a0799e80-eebf-11e9-8740-7f70de569c32.png)
       * make a directory `/file` to insert and modify data
       * type a syntax in `Main.conf`
       ![Selection_024](https://user-images.githubusercontent.com/46868237/66754612-90ae8a00-eec0-11e9-818d-ac2e4f918fa1.png)
       * type syntax `swish-e -c Main.conf` to start indexing
       ![Selection_025](https://user-images.githubusercontent.com/46868237/66754938-44177e80-eec1-11e9-933e-dd9d45412c99.png)
       * run indexing word `swish-e -w {word}`
       ![Selection_026](https://user-images.githubusercontent.com/46868237/66755360-08c97f80-eec2-11e9-8ab4-74fd8f0b009e.png)
       * indexing done
 ## Information : See the result of indexing on `/screenshot`
 ## Sources
   - Text indexing : Swish-e (packaged on ubuntu)
   - Image indexing : https://github.com/kudeh/image-search-engine
