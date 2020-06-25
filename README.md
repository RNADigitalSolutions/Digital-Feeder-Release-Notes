# Release Notes

## xx.xx.2020

### New features

- Set static object immaterial, in oder to remove its rigid body from simulation.
- Multi parameterization.
- Drag & Drop `stl` files.

### Improvements

### Bug fixes

- Crash when loading ASCII `stl` file.

## 16.06.2020

### New features:

- Shortcut: double click middle button on object: Move camera to current selected object and set it as the camera focus center.
- Motion flag (Dynamic/Static/Kinematic) for each object shown in object list.
- Stop simulation: before the first run of the simulation, the scenario will be saved as the start scenario. When clicking the stop button, the scenario will be reset to the start scenario:
![](/img/stop_button.gif) 

###  Improvements

- Import several `stl`-files at the same time. The selection count is shown in status bar.
- Rename the imported `stl` objects with their file name automatically.
- Object multiselection und deselection.
- Optimized the behavior of button state switching (enabled/disabled).
- After simulation paused/stopped, the object position and angle will be updated in the manipulator.
- Warning when create more than one source at the same time.
- The objects, which are cloned from the same part source, share the same bullet collision shape.


### Bug fixes

- Manipulator behavior.
- Stop button behavior.