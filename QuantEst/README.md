## Structure of the folder

1. anomaly_detection: contains data from XPlane and an ipynb file that tries to build anomaly data according to the paper.

2. **sgd_est_experiment**: SGD quantile estimation experiment. It's currently very messy, I am trying to re-arrange everything so that we have:

    - new files (final files): 
         - `Experiment_final.ipynb` : all the codes for experiment
         - `Experiment_test.ipynb` : the test file to check `Experiemnt_final` is correct (hopefully)
         - `Experiment_results` : will store all the images of comparison results
    - old files (to be deleted): 
         - `comparison_image_generation.ipynb`: old experiment file
         - `q_sgd_procs.dat`: data file generated by `comparison_image_generation.ipynb`

3. Q_init: a bit of research that shows how a initial value of quantile estimate might help with the estimation acuracy.

4. thesis: the Latex draft files.

5. weekly_notes: the notes about weekly meeting notes or the records of my work. Basically nothing inside QAQ