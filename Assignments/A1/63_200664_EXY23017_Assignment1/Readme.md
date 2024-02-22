### Prerequisites

- **Python 3.x**: Ensure Python is installed.
- **VTK**: Install via pip with `pip install vtk`.
- **ParaView**: For visualization.

## 1. 2D Isocontour Extraction:

1. **Prepare Data**: Place `Isabel_2D.vti` in a `Data` folder alongside the script (Already done in the zip file).
2. **Run Script**: Execute `python task1.py` in your terminal, input the isovalue when prompted.
3. **Output**: The script outputs `task1.vtp` in the script's directory.

### Visualizing Output

1. Open `task1.vtp` in ParaView.
2. To adjust contour color: `Properties` > `Solid Color`.

## 2. VTK Volume Rendering and Transfer Function:

1. **Prepare Data**: Ensure `Isabel_3D.vti` is in a `Data` folder at the same level as the script `task2.py`.
2. **Run Script**: Execute `python task2.py` from the terminal or command prompt.
3. When prompted, enter 'y' to enable Phong shading or 'n' to disable it.
4. **Output**: The script will display a render window with the volume rendering of the data.

### Visualizing Output

- The render window will show the volume rendering output.
- Use the mouse controls in the render window to rotate and explore the volume.

## Troubleshooting

- If the `.py` files do not run as expected, you can run the scripts in a Python Jupyter Notebook environment, which may resolve any issues.
