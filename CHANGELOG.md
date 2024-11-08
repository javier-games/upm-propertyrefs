## [1.0.2](https://github.com/javier-games/upm-propertyrefs/compare/1.0.1...1.0.2) (2024-11-07)

### :wrench: Fixed

* Samples Path. ([b438558](https://github.com/javier-games/upm-propertyrefs/commit/b438558733a781c41582585ca2e2451d18398277))

## [1.0.2-rc.1](https://github.com/javier-games/upm-propertyrefs/compare/1.0.1...1.0.2-rc.1) (2024-11-07)

### :wrench: Fixed

* Samples Path. ([b438558](https://github.com/javier-games/upm-propertyrefs/commit/b438558733a781c41582585ca2e2451d18398277))

## [1.0.1](https://github.com/javier-games/upm-propertyrefs/compare/1.0.0...1.0.1) (2024-11-07)

### :hammer: Changed

* Renamed CI files. ([ed063b2](https://github.com/javier-games/upm-propertyrefs/commit/ed063b2f0ea77b526bd868eb8158ae140609cc42))
* Replaced depreciated methods. ([5061f42](https://github.com/javier-games/upm-propertyrefs/commit/5061f42b8bc6233709c468651f53e3e78c8d3807))

### :tools: Changed

* GitHub actions versions. ([e5de073](https://github.com/javier-games/upm-propertyrefs/commit/e5de073b3ea7d24d2ddf0c89f83ade5c9b494f74))
* Package information. ([d96108c](https://github.com/javier-games/upm-propertyrefs/commit/d96108cf0770ece5774c4ed134e9fb0978e3cbf9))
* Readme images references. ([5d6e1e9](https://github.com/javier-games/upm-propertyrefs/commit/5d6e1e9bb2d7bd62366474a2931f327671ea7b01))
* Samples with assets. ([dde22bb](https://github.com/javier-games/upm-propertyrefs/commit/dde22bbcc1660d297aeb5fc10e940b8e28fea1b5))

### :wrench: Fixed

* CI pipeline. ([d7eb8c1](https://github.com/javier-games/upm-propertyrefs/commit/d7eb8c160ee4f040fe585e6425a507634c32a81f))
* naming semrelease con CI. ([02d8b62](https://github.com/javier-games/upm-propertyrefs/commit/02d8b6219a9d18d5988c300d00c564c840417975))

## [1.0.1-dev.3](https://github.com/javier-games/upm-propertyrefs/compare/1.0.1-dev.2...1.0.1-dev.3) (2024-11-07)

### :hammer: Changed

* Replaced depreciated methods. ([5061f42](https://github.com/javier-games/upm-propertyrefs/commit/5061f42b8bc6233709c468651f53e3e78c8d3807))

## [1.0.1-dev.2](https://github.com/javier-games/upm-propertyrefs/compare/1.0.1-dev.1...1.0.1-dev.2) (2024-11-07)

### :tools: Changed

* Package information. ([d96108c](https://github.com/javier-games/upm-propertyrefs/commit/d96108cf0770ece5774c4ed134e9fb0978e3cbf9))
* Readme images references. ([5d6e1e9](https://github.com/javier-games/upm-propertyrefs/commit/5d6e1e9bb2d7bd62366474a2931f327671ea7b01))
* Samples with assets. ([dde22bb](https://github.com/javier-games/upm-propertyrefs/commit/dde22bbcc1660d297aeb5fc10e940b8e28fea1b5))

## [1.0.1-dev.1](https://github.com/javier-games/upm-propertyrefs/compare/1.0.0...1.0.1-dev.1) (2024-11-07)

### :hammer: Changed

* Renamed CI files. ([ed063b2](https://github.com/javier-games/upm-propertyrefs/commit/ed063b2f0ea77b526bd868eb8158ae140609cc42))

### :tools: Changed

* GitHub actions versions. ([e5de073](https://github.com/javier-games/upm-propertyrefs/commit/e5de073b3ea7d24d2ddf0c89f83ade5c9b494f74))

### :wrench: Fixed

* CI pipeline. ([d7eb8c1](https://github.com/javier-games/upm-propertyrefs/commit/d7eb8c160ee4f040fe585e6425a507634c32a81f))
* naming semrelease con CI. ([02d8b62](https://github.com/javier-games/upm-propertyrefs/commit/02d8b6219a9d18d5988c300d00c564c840417975))

## [1.0.0](https://github.com/javier-games/property-refs/compare/0.0.0...1.0.0) (2023-06-16)


### ⚠ BREAKING CHANGES

* First Version Release!

Access from Editor

With a custom property drawer, PropertyRefs provides an intuitive interface for gathering all significant properties in one place. This not only eliminates the tedious search through countless properties but also promotes a cleaner, more organized codebase.

Access from Code

Developers have the flexibility to modify the values of the PropertyRefs programmatically. For more information on how to access and modify properties programmatically, please refer to the Property Access Methods section.

AOT Systems Support

PropertyRefs is equipped with a dual-mode functionality. Initially, it uses System Reflection to access the values of component properties. However, for AOT systems, where System Reflection is not applicable, PropertyRefs seamlessly switches to a Roslyn Source Generator. For more details on how AOT systems are supported, please see the AOT Systems Support and Code Generation section.

### :sparkles: Added

* Auto code generation directive. ([db35c32](https://github.com/javier-games/property-refs/commit/db35c321e59b5b6699ab87111301933f6c3b187f))
* Property drawer. ([ac88ece](https://github.com/javier-games/property-refs/commit/ac88ece9906fe0e8522ebf6cfe9b52e44d7a9057))
* Property refs and registry. ([815b378](https://github.com/javier-games/property-refs/commit/815b3783ddeb5872dc6cf5fefc61541403651390))
* Refs component for prefabs sample. ([8cf3be0](https://github.com/javier-games/property-refs/commit/8cf3be003057f0017ff48c99d320b88f731ebffa))
* Registry provider interface. ([5d3073c](https://github.com/javier-games/property-refs/commit/5d3073ca22148a9e3ee434a98f528568c4bacb06))
* Roslyn source generator. ([c5e1c52](https://github.com/javier-games/property-refs/commit/c5e1c525cdc17b380e0fd1df0155c356acf9fa43))
* Source generation sample. ([8ff4461](https://github.com/javier-games/property-refs/commit/8ff44617a326d55a033f712c926909d16620a75d))
* Source generator to CI workflow. ([7d69001](https://github.com/javier-games/property-refs/commit/7d6900150cbb8561d7d43ad225f1cd5f0dd1418b))


### :wrench: Fixed

* IDE Missing reference error. ([2ecd3e6](https://github.com/javier-games/property-refs/commit/2ecd3e60f1ca58cbfccfaa4814d9b9207bd9f46a))
* Property Ref Drawer and Registry file edition. ([36a9dc9](https://github.com/javier-games/property-refs/commit/36a9dc98f945503672251f666b4421d7b224c21a))


### :hammer: Changed

* Property references view. ([6245b94](https://github.com/javier-games/property-refs/commit/6245b94811042f7d87c301d2876e44869e8c526a))
* Samples to Samples~ ([59f05d0](https://github.com/javier-games/property-refs/commit/59f05d053615088c37de5051a996746b44d3dcdb))


* Merge pull request #22 from javier-games/release/1.0.0 ([12eb06c](https://github.com/javier-games/property-refs/commit/12eb06c4c9dd275d28e75f7eef541378bd4c4f64)), closes [#22](https://github.com/javier-games/property-refs/issues/22)

## [0.1.0-dev.3](https://github.com/javier-games/property-refs/compare/0.1.0-dev.2...0.1.0-dev.3) (2023-06-15)


### :hammer: Changed

* Property references view. ([6245b94](https://github.com/javier-games/property-refs/commit/6245b94811042f7d87c301d2876e44869e8c526a))
* Samples to Samples~ ([59f05d0](https://github.com/javier-games/property-refs/commit/59f05d053615088c37de5051a996746b44d3dcdb))

## [0.1.0-dev.2](https://github.com/javier-games/property-refs/compare/0.1.0-dev.1...0.1.0-dev.2) (2023-06-09)


### :sparkles: Added

* Auto code generation directive. ([db35c32](https://github.com/javier-games/property-refs/commit/db35c321e59b5b6699ab87111301933f6c3b187f))
* Registry provider interface. ([5d3073c](https://github.com/javier-games/property-refs/commit/5d3073ca22148a9e3ee434a98f528568c4bacb06))
* Roslyn source generator. ([c5e1c52](https://github.com/javier-games/property-refs/commit/c5e1c525cdc17b380e0fd1df0155c356acf9fa43))
* Source generation sample. ([8ff4461](https://github.com/javier-games/property-refs/commit/8ff44617a326d55a033f712c926909d16620a75d))
* Source generator to CI workflow. ([7d69001](https://github.com/javier-games/property-refs/commit/7d6900150cbb8561d7d43ad225f1cd5f0dd1418b))


### :wrench: Fixed

* IDE Missing reference error. ([2ecd3e6](https://github.com/javier-games/property-refs/commit/2ecd3e60f1ca58cbfccfaa4814d9b9207bd9f46a))
* Property Ref Drawer and Registry file edition. ([36a9dc9](https://github.com/javier-games/property-refs/commit/36a9dc98f945503672251f666b4421d7b224c21a))

## [0.1.0-dev.1](https://github.com/javier-games/property-refs/compare/0.0.0...0.1.0-dev.1) (2023-06-09)


### :sparkles: Added

* Property drawer. ([ac88ece](https://github.com/javier-games/property-refs/commit/ac88ece9906fe0e8522ebf6cfe9b52e44d7a9057))
* Property refs and registry. ([815b378](https://github.com/javier-games/property-refs/commit/815b3783ddeb5872dc6cf5fefc61541403651390))
* Refs component for prefabs sample. ([8cf3be0](https://github.com/javier-games/property-refs/commit/8cf3be003057f0017ff48c99d320b88f731ebffa))

## [0.0.0](https://github.com/javier-games/property-refs/commit/f8dbb939a8372587f2d8c1d76127afebef169e1e) (2023-05-28)

### :sparkles: Added 

* Initial commit. ([f8dbb93](https://github.com/javier-games/property-refs/commit/f8dbb939a8372587f2d8c1d76127afebef169e1e))
