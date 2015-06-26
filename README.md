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


# Bundle-hub Questions?
[Ask your question here](https://github.com/flexiblepower/bundle-hub/issues/new?title=Question:My%20Title&body)

# Bugs
[See FAN-wiki](https://github.com/flexiblepower/FAN-wiki/wiki/Bug-tracking-process)
