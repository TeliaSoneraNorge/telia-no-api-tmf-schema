![](images/teliacompany.png)

> Disclaimer: This repository is in the proceess of being established, and does not yet have the right structure or content.

# Telia Open-API Schema Repository

> Important: This repository is initially based on the needs of ongoing development in Telia Norway. The long term goal, however, is to establish a uniform TMF Open API resource model for Telia Company. All TMF Open API work in Telia *should* collaborate  to establishing this repository as the source for this model.

[TMF630](https://www.tmforum.org/resources/standard/tmf630-api-design-guidelines-3-0-r17-5-0/) specifies REST API Design Guidelines for the development and use of the TMF Open APIs.

In part 2, the guidelines describe how the base SID resource model of the Open APIs can be extended to local needs by "sub typing" the resources. This is done by referring to resource schemas using @type and @schemaLocation attributes. JSON-schema is used to define the types.  

This repository contains the collection of JSON-schema files that define the extensions used by Telia.

The base types being extended are defined in the [TM Forum Open-API Schema Repository](https://github.com/tmforum-rand/schemas).

