# Accurate quantitative estimation of energy performance of buildings using statistical models

## Introduction
The global requirement for energy is growing every year. It was declared by [World Energy Outlook 2020](https://www.iea.org/reports/world-energy-outlook-2020) that prior to the pandemic, energy demand was projected to grow by 12% between 2019 and 2030. Growth over this period is now 9% in the Stated Policies Scenario. Moreover, buildings in some countries are legally bound to conform to appropriate minimum requirements regarding energy efficiency. One way to alleviate the everincreasing demand for additional energy supply is to have more energy-efficient building designs with improved energy conservation properties.

Furthermore, the demand for air conditioning is set to increase over the next few decades, with many developing countries with large populations having homes yet to purchase their first air conditioner. Accompanying a demand for air conditioners in these countries will be an increased demand on the energy supplies of the world. Being able to design homes in developing countries being built now can help curb the demand placed on energy supplies by air conditioning in the future.

Accompanying an increase in demand for air conditioners will be an increased use in refrigerants. Currently, the most common refrigerant used in cooling technologies such as air conditioners and refrigerators are the hydrofluorocarbon (HFC) R-134A, used in the vast majority of refrigeration and air conditioning. Once released HFCs act as greenhouse gases which last in the atmosphere longer than carbon dioxide. In order to help reduce the number of refrigerants used in the future, structural decisions can be made in the design of buildings in order to reduce the cooling load, and therefore the amount of refrigerant used in cooling buildings in the future. Being able to reduce the amount of refrigerant used will in turn reduce the amount of HFCs introduced in the atmosphere to combat climate change.

Regarding efficient designs of buildings, calculation of the heating load (HL) and the cooling load (CL) is necessary to determine the specifications of the air-conditioning equipment required to maintain comfortable indoor thermal environments. Information about the characteristics of the building and the conditioned space is necessary to estimate the required heating and cooling capacities.

Different statistical approaches have been used to predict energy demand for the building in various studies. The vast number of machine learning techniques in regression and classification problems have been conducted to estimate the heating load and cooling load, and many methods have been used to improve the model accuracy.

In this study, CL would be estimated with respect to Mean Squared Error. Essential feature transform and feature selection steps on the model is applied to find the best fitted model.

## Dataset
The data set was gained through the [UCI Machine Learning Repository](). The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2).

Specifically:
X1 Relative Compactness
X2 Surface Area
X3 Wall Area
X4 Roof Area
X5 Overall Height
X6 Orientation
X7 Glazing Area
X8 Glazing Area Distribution
y1 Heating Load
y2 Cooling Load
