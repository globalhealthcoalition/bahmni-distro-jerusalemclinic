![alt tag](readme/ghc-logo-200x205.png)

-----

# Global Health Coalition Haiti distribution

A lightweight, ready-to-use Bahmni distribution for Haiti outpatient clinics to support standardized terminology, work processes, and reporting analytics. 

This repository maintains the 'distro POM' for the _Global Health Coalition Haiti distribution_.
It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `bahmniapps/`
<br/>The target version of Bahmni Apps or 'Bahmni EMR', the client-side EMR of Bahmni.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/globalhealthcoalition/bahmni-config-haiti)) to be consumed by Bahmni Apps.
* `modules/`
<br/>The required set of OpenMRS modules.
* `war/`
The target version of OpenMRS Core.