FlexiblePower Bundle Hub
========================

A set of OSGi bundles for the development and running of the FlexiblePower Application Infrastructure. This repo should not be checked out before use, but instead we can use the this repository directly. Just add the following line to your `repositories.bnd` file:

```
-plugin: \
         aQute.bnd.deployer.repository.FixedIndexedRepo;\
            name=FlexiblePower Bundle Hub - Build;\
            locations=https://raw.githubusercontent.com/flexiblepower/bundle-hub/split-repos/build/index.xml;\
            cache=${workspace}/cnf/cache,\
         aQute.bnd.deployer.repository.FixedIndexedRepo;\
            name=FlexiblePower Bundle Hub - Run;\
            locations=https://raw.githubusercontent.com/flexiblepower/bundle-hub/split-repos/run/index.xml;\
            cache=${workspace}/cnf/cache,\
         aQute.bnd.deployer.repository.FixedIndexedRepo;\
            name=FlexiblePower Bundle Hub - Test;\
            locations=https://raw.githubusercontent.com/flexiblepower/bundle-hub/split-repos/test/index.xml;\
            cache=${workspace}/cnf/cache,\
         #other repositories
```
