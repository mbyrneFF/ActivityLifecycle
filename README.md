# Activity Lifecycle

Turn change history on Salesforce records into easily digestible insights

App with a tiny footprint and immediately beneficial to every existing Salesforce customer

Wealth of information hidden in Salesforce Change History
Standard salesforce view difficult to review changes to records in an easy to digest manner.
Single intelligent dashboard app which can be embeddable in as a sidebar to multiple page layouts and then filters based on the Parent Id
Non-Invasive design means minimum impact to existing workflows
Clear visibility into how long a record has been in current status
Provides potential outcomes based upon historic results (saql not Einstein AI), where applicable.
Extendable to other records and applications on the Salesforce Platform.
Recognizes Parent Id of records and multiple sources are brought together


# Package Installation Link

https://login.salesforce.com/packaging/installPackage.apexp?p0=04tB0000000QVBm

# Package Requirements

This dashboard is based on the field history tracking and so this should be turned on for the following fields
Account
  Type field
Case
  Status 
  Priorty
Opportunity
  Stage
  ForecastCategoryName

  This is all done via Setup > Object Manager > Field & Relationships > Set History Tracking.

# Embedding the Dashboard

This dashboard can be embedded into the Case, Account and Opportunity layouts and should be filtered that the Parent_id from the dataset is the same as the record id, either Case ID, Account Id or Opportunity ID.
