# Azure-JSON-Solutions

JSON based templates for use in the Azure Pricing calculator.

Link to the online Pricing Calculator: http://azure.microsoft.com/en-us/pricing/calculator/

Must be used with this extention to be able to import and export templates: https://github.com/andhikanugraha/azurecalc-json

-Platform Support contains the base Rackspace platform solution components.  Please remove Traffic Manager if not needed and updte the configuration of other items (e.g. Backups).  Also, assure the region match the needs of your customer's solution.

-Platform Support SQLAOAG-AD is the same as above, but contains SQL AlwaysOn and a pair of AD Domain Controllers.  The SQL AOAG can be converted to a SQL mirror by changing the SQL Servers to Standard Edition and making the witness server a SQL Express Witness.
