# Project Stage 1 Checklist

``` txt
- [ ] **to get started**
  - [ ] Create a tag according to the [semantic versioning](https://semver.org/) compliant with the following syntax 1.a.n where: a: approach number [1..3], n: any number you like
  - [ ] program text is in C#
  - [ ] build succeeded
  - [ ] all UTs are green
- [ ] program has layered architecture and contains at least `presentation`, `logic`, and `data` layers
- [ ] **Data Layer**
  - [ ] responsibility of this layer is to represent balls
  - [ ] the layer is clearly stated using language terms only
  - [ ] the layer doesn't depend on external data, for example, a database, or file.
  - [ ] the API is clearly stated
  - [ ] the API is abstract
- [ ] **Logic Layer**
  - [ ] `Logic` layer is clearly stated using language terms only
  - [ ] `Logic` API is clearly stated and abstract
  - [ ] `Logic` uses only the abstract `Data` layer API
- [ ] **Presentation Layer**
  - [ ] `Presentation` layer is clearly stated using language terms only
  - [ ] `Presentation` uses only the abstract `Logic` layer API
  - [ ] MVVM and XAML are applied to implement GUI
  - [ ] reactive and interactive user interaction for user (operator) communication
  - [ ] the graphical user interface (GUI) must be scaled appropriately
- [ ] Fulfill functional requirements of the task
- [ ] **Testing**
  - [ ] Unit Test - layers are tested independently using abstract API and Dependency injection (external package is not allowed)
  - [ ] Mock (external package) must not be used for testing purposes
```