
OpenMC has a [plot_xs](https://docs.openmc.org/en/stable/pythonapi/generated/openmc.plot_xs.html) which is ideal for creating Matplolib plots and recommened for the vast majoirt of use cases.

This package provides portable interaction cross section plots using [Plotly](https://plotly.com) which is useful for some use cases.

:point_right: Allows multiple isotopes / elements / materials on one axis
:point_right: Allows interactive hover text providing cross section values
:point_right: Allows axis scale changing (log / linear)
:point_right: Allows exporting the image in interactive html format

# Install

```
pip install openmc_cross_section_plotter
```

# Usage

See the [neutronics-workshop](https://github.com/fusion-energy/neutronics-workshop/tree/main/tasks/task_01_cross_sections) for examples
