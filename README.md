# OpenFOAM simulation in a nutshell

## Introductory case

A repo for the introductory OpenFOAM case in the course
"Reservoir Engineering with OpenFAOM", Part 1, unit: "OpenFOAM solution to the
example transport problem".

### Objectives of this OpenFOAM case

- Introduce basic OpenFOAM concepts.
- Introduce PyFOAM *as a library* to run cases in a scriptable way.
- Compare OpenFOAM's way of doing things with the manual approach.
- Discover numerical schemes accuracy effects

The repo holds tagged commits to different stages of preparing and
running the simulation:

###  Stage 01, Git Tag: meshingStage

- The case is a copy of a standard tutorial
- Only the *mesh* has been modified to suit the problem's requirements

### Stage 02, Git Tag: ICsBCsConfigured

- All fields in `0` directory are configured to match initial and boundary
  conditions of the problem

### Stage 03, Git Tag: EndOfPreprocessing

- The case is "run-ready"
- Numerical schemes, linear solvers and simulation controls are all chosen

### Stage 04, Git Tag: IntroNotebook

- A sample (but complete) Jupyter Notebook to run and investigate the case.
