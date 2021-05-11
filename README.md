# Marina's Portfolio

# [Project 6: Dog Breed Classification (on construction)](https://github.com/oliveirampo/dog_breed_classification)

Convolutional Neural Network (CNN) is a powerful tool commonly applied to image analysis that is capable to outperform humans on some computer vision tasks.

Here an image classification pipeline for dog breed is presented.

The steps of this notebook are:

1. Clone the github repository with all the data to Google Drive (an authorization is required).
2. Visualization of the training set.
3. Training of CNN model using transfer learning.
4. Classification of new data.



# [Project 5: Recommendations with IBM Watson Studio](https://github.com/oliveirampo/ibm_engine_recommendation)

In this repository the following recommendation systems were applied on a dataset with interactions that users have with articles on the IBM Watson Studio:

* Rank-based recommendations.
* User-user based collaborative filtering.
* Matrix factorization.
* Content-based recommendations (ongoing).

The main results are presented [here](https://oliveirampo.github.io/ibm_engine_recommendation/)
and the main analyses in the
[jupyter notebook](https://nbviewer.jupyter.org/github/oliveirampo/ibm_engine_recommendation/blob/main/scr/recommendations_with_IBM.ipynb).

# [Project 4: Disaster Response Pipeline](https://github.com/oliveirampo/disaster_response_pipeline)

This project uses machine learning to categorize messages that were sent during disaster events.

It also contains a webapp where a user can send messages and have them classified.

![](/images/webapp_screen_shot.png)

# [Project 3: Analyzing Airbnb Dataset: The Seattle Case](https://github.com/oliveirampo/airbnb_seatle/blob/main/README.md)

This project analyses the Seattle AirBnb Open Data on Kaggle using python.
It covers the following three questions:

  1. What are the distribution of listing prices by neighborhoods?
  2. How does the property type impact listing price on a neighborhood?
  3. How well can we predict listing price?
  
 ![](/images/property_type_per_neighborhood.png)

# [Project 2: Search for experimental data in database of organic molecules](https://github.com/oliveirampo/combiff)

* Search for identifier (name, InChIKey, CAS registry number) in [Pubchem](https://pubchem.ncbi.nlm.nih.gov/) given smiles strings.
* Search for themodynamic, dielectric, transport and solvation data of organic molecules in database of experimental data of organic compounds.
* For every molecule, plot all available data and let the user select the reference data points.
* Write selected data to csv file.


![](/images/chap_1_vic.png)

[J. Chem. Theory Comput., 16, 7525-​7555 (2020).](https://pubs.acs.org/doi/10.1021/acs.jctc.0c00683)


# [Project 1: Force-field optimization](https://github.com/oliveirampo/opt)

* This project is part of an integrated scheme for the automated refinement of force-field parameters 
against experimental condensed-phase data,
considering entire classes of organic molecules
constructed using a fragment library via combinatorial isomer enumeration.

* The main steps of the scheme, referred to as CombiFF, are:

  1. definition of a molecule family;
  2. combinatorial enumeration of all isomers;
  3. [query for experimental data](https://github.com/oliveirampo/combiff);
  4. automatic construction of the molecular topologies by fragment assembly;
  5. iterative refinement of the force-field parameters considering the entire family.
  
![](/images/TOC.png)

[J. Chem. Theory Comput., 16, 7525-​7555 (2020).](https://pubs.acs.org/doi/10.1021/acs.jctc.0c00683)

* This project is only concerned about topic (iv).

* There are two key aspects in this scheme:

  1. The force-field design relies on an [electronegativity-equalization scheme](https://github.com/oliveirampo/opt/blob/master/scr/EEM.py)
for the atomic partial charges [(J. Chem. Phys. 131, 044127 (2009))](https://aip.scitation.org/doi/10.1063/1.3187034).
  2. The optimization procedure uses statistical-mechanical expressions.
