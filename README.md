# !!! Archived -- this repository is currently not actively maintained!

# cumulocity-client-reactive-spring-boot
Cumulocity client using spring boot reactive stack (WebFlux) https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html

## State

Current Cumulocity Java SDK are synchrone. To build a non blocking and even a reactive application a reactive client is needed! Currently i finished InventoryService with following support:

**InventoryService:**
- create ManagedObject (create)
- update ManagedObject (update)
- delete ManagedObject (delete)
- get specific ManagedObject by id (detail)
- get complete list of ManagedObject (list)
- get list of ManagedObject by query parameters (listQuery)
- get childDevices, childAssets and childAdditions 
- add childDevices, childAssets and childAdditions
- remove childDevices, childAssets and childAdditions

next step:

**MeasurementService:**
- create Measurement
- create Measurement series
...

**I am looking also for contributors, please let me know!** 

## Vision

- Reflecting complete Cumulocity API as java reactive client, aligned to @c8y/client (http://resources.cumulocity.com/documentation/websdk/client/)
- Reflecting complete Cumulocity API as kotlin reactive client, aligned to @c8y/client (http://resources.cumulocity.com/documentation/websdk/client/)
- Easy integration in spring boot application as starter
- Java/Kotlin client should be isomorphic (can be used for microservice and agent)


## Authors 

[Alexander Pester](mailto:alexander.pester@softwareag.com)

## Disclaimer

These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.

## Contact

For more information you can Ask a Question in the [TECHcommunity Forums](https://tech.forums.softwareag.com/tags/c/forum/1/Cumulocity-IoT).

You can find additional information in the [Software AG TECHcommunity](https://tech.forums.softwareag.com/tag/Cumulocity-IoT).

_________________
Contact us at [TECHcommunity](mailto:technologycommunity@softwareag.com?subject=Github/SoftwareAG) if you have any questions.
