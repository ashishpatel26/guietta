# Changelog


## [0.3.3] - 

### Changed
  - Support for older PySide versions (v5.9+)
  - Fixed bug in ValueSlider layout
  - Internal refactor adding the new Rows class.

### Added
  - 'clicked' signal for Matplotlib widgets


## [0.3.2] - 2019-05-26

### Changed
  - Fixing incompatibilites between GitHub's and PyPI's README format.

## [0.3.1] - 2019-05-26

### Added
 - Support for ComboBoxes (using QComboBox)
 - Splash Screen (using QSplashScreen)
 - @auto decorator syntax
 - "with" context manager syntax
 - removed all widget-generating functions, all widgets are now classes
 - widgets can be specified with just the class, a widget with a default name
   will be allocated.
 
### Changed
 - "dropped" signal for list boxes (QListBox) renamed to "drop"


## [0.3.0] - 2019-05-18

### Changed
 - Using PySide2 bindings instead of PyQt5
