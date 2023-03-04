
# GeoDatabase-Design-with-ArcGis

Development of a geodatabase design tool with arcgis which takes into account the notion of domains and subtypes




## Introduction


With the notion of domains and subtypes, this tool allows us to design geodatabases automatically.

The algorithm takes as input an excel file which contains the various categories for each entity and the sub-categories and even the sub-sub-category as well as other fields which characterize each category of entities.

In such a way that we finally obtain a feature class with the various fields and that we need to fill in all the fields, it is just with a drop-down list that we choose the values ​​of attributes.

The various levels of categories are linked together, so that when you change the specific category of an entity, all the other fields will be filled in automatically.

Our algorithm takes into consideration exactly 3 category levels and as much as other fileds .


## Exemple 

### Excel file

This is an exemple of Excel file that contines 4 columns.

![Annotation 2023-03-0qss3 15z02175xsc22](https://user-images.githubusercontent.com/75672532/222885187-11892682-3fe6-4f8e-96c5-f3a0d0854155.png)

The first column represent some eras names of on the geological time scale .

The second column represent the geological time series for each era .

The third column represent the subdivisions of the various series of periods .

The fourth one is a code assigned for each sub-sub category .

Here is a figure that illustrate the Giological Time Scale 

![vignette_echelle_temps_geologiques_simplifiee](https://user-images.githubusercontent.com/75672532/222885614-aad50d01-e54d-4a3f-988e-e90bf9bdd6df.jpg)


### Toolbox 

We have three Toolboxs :

![Annotation 2023-03-03 150217](https://user-images.githubusercontent.com/75672532/222886042-00df5c89-195e-4676-ad12-1deb16bdcc6f.png)


Here is the first Toolbox that allows us to create a Feature Class inside a new Geodatabase

![Annotation 2023-03-03 1502175xsc22](https://user-images.githubusercontent.com/75672532/222885751-bd5e1207-6c8b-478b-896f-22ef60a91997.png)


The second is a Toolbox that allows us to Create a Feature Class inside an existing Geodatabase

![Annotation 2023-03-03 150217522](https://user-images.githubusercontent.com/75672532/222885818-cc7f943b-cad1-419b-bd9c-34b3e777697f.png)


The third and last Toolbox allows us to Design an existing Feature Class

![Annotation 2023-03-0qss3 1502175xsc22](https://user-images.githubusercontent.com/75672532/222885856-cd01f113-6acf-4f87-b1f2-60f20ee4b051.png)


### Starting Design of new Feature Class inside a new Geodatabase

To make it , we should fill all the blanks :

![Annotation sdsd-03-0qss3 15z02175xsc22](https://user-images.githubusercontent.com/75672532/222885945-97f65e92-482d-45c4-b2f7-f064f53c2391.png)

#### Subtype field :

the subtype field is a type of attribute field that allows you to categorize features within a feature class.

It is used to organize data and provide a way to group similar features together based on a common set of characteristics



Then we run the tool :

![sddsd](https://user-images.githubusercontent.com/75672532/222885977-59e1f2ad-319d-4c2c-a87a-67838124b9e7.png)

### Results

Finally , we obtain a Designed Feature Class as we want 

![qsssssqss](https://user-images.githubusercontent.com/75672532/222886241-04f2d7cf-aa93-47ee-a8be-02612de5c8d5.png)


### Adding new entity

We only need to choose the feature type to create and digitize it , then , all the fields will be filled automatically .

![azdad](https://user-images.githubusercontent.com/75672532/222886301-c996e5a1-1679-4fe4-974a-7372a3857219.png)

### Editing an entity

If we want to change the type of an entity , we only need to change the last specifique level (Subtype) and the rest fileds we be changed automatically

![Capture d’écran (7)](https://user-images.githubusercontent.com/75672532/222886432-10b46b00-b16e-4c7c-b741-01455acaab2a.png)

![zadazd](https://user-images.githubusercontent.com/75672532/222886444-c154e50d-7d4d-4bd0-a707-b068c7942a22.png)


We can also use the two other Toolboxs in relation to our needs 

# Thanks for your Attention !!! 


