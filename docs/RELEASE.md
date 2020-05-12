# motorScriptMotor Releases

## __R1-1 (2020-05-12)__
R1-1 is a release based on the master branch.  

### Changes since R1-0

#### New features
* Commit [194348c](https://github.com/epics-motor/motorScriptMotor/commit/194348c646e1b93cf37c8b58dbeb30dfa25d810b): User displays can now be autoconverted at build time

#### Modifications to existing features
* Commit [79ab30e](https://github.com/epics-motor/motorScriptMotor/commit/79ab30e5babb448e84db1134c15639f9a491ea96): ``CONFIG_SITE`` now includes ``$(SUPPORT)/configure/CONFIG_SITE``, if it exists
* Commit [8d0de84](https://github.com/epics-motor/motorScriptMotor/commit/8d0de8449e0aba7c54c5737fb377eac7d9a1ab09): ``SUPPORT`` is now defined in ``RELEASE``, which is needed for autoconvert
* Commit [61581d0](https://github.com/epics-motor/motorScriptMotor/commit/61581d0cd61be05c34f6ed0c02a179e018fd4bd9): User displays have been autoconverted using the latest converter

#### Bug fixes
* Commit [5517d7d](https://github.com/epics-motor/motorScriptMotor/commit/5517d7deaf04bab1a6057c64a82cd00381ce480e): Include ``$(MOTOR)/modules/RELEASE.$(EPICS_HOST_ARCH).local`` instead of ``$(MOTOR)/configure/RELEASE``

## __R1-0 (2019-04-18)__
R1-0 is a release based on the master branch.  

### Changes since motor-6-11

motorScriptMotor is now a standalone module, as well as a submodule of [motor](https://github.com/epics-modules/motor)

#### New features
* motorScriptMotor can be built outside of the motor directory
* motorScriptMotor has a dedicated example IOC that can be built outside of motorScriptMotor

#### Modifications to existing features
* None

#### Bug fixes
* None
