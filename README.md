# Fruit Infection Disease Classification

![end](https://github.com/JavierdiazS/Fruit-Infection-Disease/assets/75210642/c3bb334b-5a72-436a-993f-cadc964281d3)

Final result:

![gif](https://github.com/JavierdiazS/Fruit-Infection-Disease/assets/75210642/fa3c9599-7188-4856-a54c-09fcf7571d0c)

- [Summary](#summary)
- [Repo structure](#repo-structure)

## Summary

Classifying diseases in fruit-bearing plants such as strawberries and tomatoes, and in legumes such as beans, enables the precise identification of causative agents, such as bacteria, fungi, or viruses. This is essential for developing specific control and management strategies. Each pathogenic agent may require different prevention and treatment methods.

Accurate classification is crucial for international trade of agricultural products, and precise disease identification helps prevent the introduction of pathogens into new regions.

With the assistance of Deep Learning, we can automate this process.

This project was carried out using the crop disease dataset collected by Nikit Kashyap (2022) on the Kaggle platform. The dataset comprises **5500 images**: **1166 for testing**, **2907 for training**, and **1427 for validation**. This diverse collection of images represents various types of diseases affecting crops like strawberries, tomatoes, and beans [here](https://www.kaggle.com/datasets/nikitkashyap/fruit-infection-disease-dataset).

To conduct tests on the local Web server (testing the index.html), a dataset called "data_image" was created on Kaggle, containing **3 images** created by me [here](https://www.kaggle.com/datasets/emrysds/data-image).

Six different neural architectures were tested, yielding varied results, with the best performance achieved by the fourth and final neural architecture:

* 1st neural network: **loss**: 2.7913 - **accuracy**: 0.7770
* 2nd neural network: **loss**: 4.8144 - **accuracy**: 0.6732
* 3rd neural network: **loss**: 3.5195 - **accuracy**: 0.5763
* 4th neural network: **loss**: 1.6255 - **accuracy**: 0.7890 ✅
* 5th neural network: **loss**: 4.2998 - **accuracy**: 0.6604
* 6th neural network: **loss**: 1.1829 - **accuracy**: 0.8139 ✅


## Repo structure

The project has the following structure:
- `notebook/`: `.ipynb` notebooks for data eploration, training models and ensembling.
- `webapp/`: Contains the `.html` and the command to run the web from the local server. Along with the `.json` of the latest model.

## Contributing

Feel free to use it if you want to contribute directly to the code base.

## License

It is released under the MIT license. See the [LICENSE](/LICENSE) file for details.

