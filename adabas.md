One example of a database that follows a model that we haven't discussed yet is Software AG’s ADABAS Database management system.
It's been around since the 70s, is still supported, and its website can be found [here](https://cdt.ca.gov/services/database-adabas/).
It uses an inverted file model. In this model, data isn't stored in a table like in a relational database, it's not centered around classes and objects,
and there aren't unique keys that correspond directly with specified values. Instead, data is indexed as a series of keys in a lookup table.
Those keys are then connected to pointers to the locations of associated files. This allows for near-instantaneous reporting, even where Big Data is concerned.



# Sources
### https://cdt.ca.gov/services/database-adabas/
### https://hevodata.com/learn/types-of-database-models/#t27
### https://link.springer.com/referenceworkentry/10.1007/978-0-387-39940-9_1136
