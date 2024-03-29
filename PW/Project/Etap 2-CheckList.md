# Project Stage 2 Checklist

```txt

- [ ] **Starting point**
  - [ ] text is in C#
  - [ ] all UT are green
  - [ ] the program behaves as expected (intermediate approval test)
- [ ] **Data Layer**
  - [ ] responsibility of this layer is to represent boundaries of the movement rectangle and balls
  - [ ] balls representation are independent and self-contained (no timer required)
  - [ ] balls implementation uses concurrent programming
- [ ] **Logic Layer**
  - [ ] responsibility of this layer is to manage movement rectangle boundaries and balls interaction (collisions)
  - [ ] prove that the protection  of data integration is implemented
  - [ ] `Logic` uses only the abstract `Data` layer API
- [ ] **Presentation Layer (MVVM)**
  - [ ] responsibility of this layer is to manage the graphical user interface (GUI)
  - [ ] user => GUI interoperability must be implemented using interactive programming only
  - [ ] GUI => the user interoperability must be implemented using reactive programming only (timer is not allowed)
  - [ ] interoperability of the GUI and underlying layers must be synchronized
- [ ] Fulfill functional requirements of the task
- [ ] **Testing**
  - [ ] Unit Test - layers are tested independently using dependency injection (additional framework is not required)
  - [ ] Mock may be used for testing purposes (expected but not required)

```
