# 2016 Tite-seq inference
This is code used to infer binding affinities from my paper
```
Adams, Rhys M., Thierry Mora, Aleksandra M. Walczak, and Justin B. Kinney. "Measuring the sequence-affinity landscape of antibodies with massively parallel titration curves." Elife 5 (2016): e23156.
```
If you use this code please cite this paper.

I'm creating a separate repository since python has changed and people
may want to use the algorithm I've written. I'll update this repository when I
become aware of issues with changes in Python.

To run the code in python 3, for test simulations under non-ideal measurements
```
python KD_fit_log_poiss.py
```
for description
```
python KD_fit_log_poiss.py help
```
for actual usage on an individual sequence (amongst many in an NGS run):
```
python KD_fit_log_poiss.py input_pickle.dat output_pickle.dat
```
