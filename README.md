# CATegorization_task_jspsych
A jspsych version of a visual categorization task with two difficulty manipulations (choice difficulty, perceptual difficulty). In each trial, participants are shown a visual image that is either a cat, a dog, or a moprhed image that is partly cat and partly dog. The task is to classify the images as either cat or dog. Choice difficulty is maniplated via the morph level, a 100% cat image is easier to classify than a 40% cat / 60% dog image. Perceptual difficulty is manipulated by adding more or less random gaussian noise to the images. In this version of the experiment, choice difficulty is randomly intermixed, while perceptual difficulty is blocked. 
 
David Freedman was kind to share the original stimuli with me, so all credit regarding the stimuli belongs to him and his team (see e.g. McKee, Riesenhuber, Miller, Freedman, 2014, JNeuro).   

## Procedure 
1) Consent and demographic information
2) Practice on template stimuli (i.e. 100% cat, 100% dog)
3) Staircase procedure to calibrate the noise level for perceptually difficult stimuli. Set so that the error rate will be about 20% in perceptually difficult trials. 
4) Practice on morphed stimuli. The complete morph space is presented once to each participant. 
5) 6 Experimental blocks (3 perceptually easy, 3 perceptually difficult, choice dificulty randomly intermixed)
Duration: about 25 minutes. 
 
## How to run
For this experiment to work, you need to copy all the files of the repository onto a web server. Then open categorization_task.html in Chrome, and the experiment should start.

## Requirements
This experiment will not run locally on your computer, it needs to be placed on a web server.
 
## Bugs / Improvements
If you find bugs in this script or have suggestions for improvement, please report both here https://github.com/davidwisniewski/CATegorization_task_jspsych/issues

## Contact
david.wisniewski@ugent.be
