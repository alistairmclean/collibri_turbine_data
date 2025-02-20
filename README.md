Repo is set up for DAB deployment with databricks.yml, src and resources in the databricks/ingest_turbine_data folder.

There are two notebooks:
* wt_data_eda_and_development is the notebook I started with. Here I did a small amount of EDA, developed the pipeline code iteratively and then extracted it into a function, before testing imputing missing power values.
* wt_data_ingestion is the pipeline task notebook, extracted and tidied up a bit from the above development notebook.