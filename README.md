# Master-Thesis
Data Cleaning and Transformation of Structured Data to Standard Format

I have uploaded all the files of my thesis work starting from the initial point.
Bascially, from 1st prototype folder till 4th prototype you I have traced all the modifications of my project.

Guide:
In each folder there is a notebook file to create the initial dataset which I named them noisy set , in this part I simulated
the most common noise(mistakes) that usually can be found in datasets. These noise could be :
 -- Replacing letters : User types the wrong letter
 -- Cutting letters : Letter is not typed 
 -- Additional letter : extra lettrers is added 
 -- Combined case: Combination of all above noises

Then the result is saved into a csv file to be used later for calculating edit distances.

The algorithms used here are : Leveneshteine/Hamming/Jaro  Distance and modifications of levenshtein and jaro distance 
which can be quite useful for specific cases like considering the swapping letters case (ab to ba gives edit distance=1 instead of 2)

At the end of each notebook of computing the edit distances , I calculated the accuracy of the algorithm and plotted them.

Please Note that , I am at the last stage of this project and the last prototype is not over yet.I need to apply some changes and extend 
it to all edit distance algorithms.

Please let me know in case of any suggestion and also in case of need for more explanation

Regards,
Hassan Abbasi
h.abbasi72@gmail.com


