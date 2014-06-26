FlexiblePower Application Infrastructure: Bundle Hub
====================================================

A set of OSGi bundles for the development and running of the FlexiblePower Application Infrastructure. This repo should not be checked out before use, but instead we can use the this repository directly. Just add the following line to your `repositories.bnd` file:

```
-plugin: aQute.bnd.deployer.repository.FixedIndexedRepo;\
            name=FPAI Bundle Hub;\
            locations=https://raw.githubusercontent.com/flexiblepower/bundle-hub/master/index.xml.gz;\
            cache=${workspace}/cnf/cache,\
         <other repositories>
```
