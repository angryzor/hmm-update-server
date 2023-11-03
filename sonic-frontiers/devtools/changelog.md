# v0.0.2
* Added the beginnings of a GameService inspector
* Added basic inspector for the NeedleFXParameter, FxLODParameter and StageCommonTimeProgressParameter reflections in the service FxParamManager.
  Many of these parameters do not yet have an immediate effect because they need additional update steps to be implemented.
  Others are controlled by other services and will immediately revert.
* Fixed some controls with same name being "linked together" (opening and closing together, value changed together).

# v0.0.1
* Added rudimentary manipulation of the GOCTransform component.
* Fixed an issue where inputs given while the DevTools are closed would build up and be processed all at once when bringing them up.
