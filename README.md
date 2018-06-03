# opportunity-analysis-sample

This is a Doku for opportunity analysis sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-opportunity-analysis from http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1NEG0cBf2OoiN8JsomimEi1m-j9T8ntMh/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 5 entity (table) and every table has attribute.

1. sales stage
* Attibute: Probability,	Sales Stage, Sales Stage ID

2. product
* Attibute: Product Code,	Product ID

3. partner
* Attibute: Partner,	Partner ID,	Partner Driven

4. opportunity
* Attibute: Name,	Opportunity ID,	Rank,	SizeID,	Opportunity Size

5. fact
* Attibute: EstimatedCloseDate,	Opportunity ID,	Sales Stage ID,	Account ID,	Partner ID,	Product ID,	ProductRevenue,	FactoredProductRevenue,	Create Date,	Opportunity Days,	Year,	Month_Number,	Month


### Let's make the data model from the 8 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model

![opportunity-data-model](https://user-images.githubusercontent.com/27078712/40886090-3cdaef2a-6732-11e8-85dc-c863e786ac1a.PNG)


### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!






