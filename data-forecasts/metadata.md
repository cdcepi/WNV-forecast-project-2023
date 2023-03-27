# Metadata File Structure

Each model is required to have metadata in [yaml format](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html), e.g. [see this metadata file](https://github.com/reichlab/covid19-forecast-hub/blob/master/data-processed/JHU_IDD-CovidSP/metadata-JHU_IDD-CovidSP.txt).

This file describes each of the variables (keys) that should be included in the submitted yaml document. Please order the variables in this order. Note that some of the required variables are not applicable to the format  of the Challenge, but are still required for the [validations](../Forecast-Submission.md#Forecast-validation) to run. We note what to include in these fields below.


## Required Variables

### team_name
The name of your team that is less than 50 characters.

### model_name
The name of your model that is less than 50 characters.

### model_abbr
An abbreviated name for your model that is less than 30 alphanumeric characters. The model abbreviation must be in the format of `[team_abbr]-[model_abbr]`. where each of the `[team_abbr]` and `[model_abbr]` are text strings that are each less than 15 alphanumeric characters that do not include a hyphen or whitespace  Note that this is a 
uniquely identifying field in our system, so please choose this name carefully, as it may not be changed once defined. An example of a valid `model_abbr` is `UMass-MechBayes` or `UCLA-SuEIR`. 

### model_contributors
A list of all individuals involved in the forecasting effort, affiliations, and email address. List the team lead first. At least one contributor needs to have a valid email address, ideally the team lead. All email addresses provided will be added to an email distribution list for model contributors.

The syntax of this field should be 

    leadname (affiliation) <user@address>, name2 (affiliation2) <user2@address2>

### website_url
A url to a website that has additional data about your model. If you also have a data repository where you store forecasts and other model code (like your forked version of this repo), please include that in the `repo_url` section below. If you only have a github repo, please include that link here. 

### license
One of these [licenses](https://github.com/reichlab/covid19-forecast-hub/blob/master/code/validation/accepted-licenses.csv).

We encourage teams to submit as a "cc-by-4.0" to allow the broadest possible uses. If the value is "LICENSE.txt", then a LICENSE.txt file must exist within the folder and provide a license.

### team_model_designation
This field should be "primary" (without the quotes). This is one of the variables required for validation, but not applicable to the structure of this Challenge.

### methods
A brief description of your forecasting methodology that is less than 200 characters.

### ensemble_of_hub_models
This field should be "false" (lowercase boolean value without the quotes). This is one of the variables required for validation, but not applicable to the structure of this Challenge.

### data_inputs
A description of the data sources used in the model and the temporal relationship of these variables to the forecast.

An example description of a set of variables could be 

> Spring (Jan-Mar, matching time to forecast) mean temperature and total precipitation were obtained on the
> county scale from PRISM.


## Optional

### institutional_affil
University or company names, if relevant. 

### team_funding 
Like an acknowledgement in a manuscript, you can acknowledge funding here.

### repo_url

A github (or similar) repository url. 

### citation
A url (doi link preferred) to an extended description of your model, e.g. blog post, website, preprint, or peer-reviewed manuscript. 

### methods_long
An extended description of the methods used in the model. If the model is modified, this field can be used to provide the date of the modification and a description of the change, mentioning things like additional data sources used, variables included, or model structure changes.