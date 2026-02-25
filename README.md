Interactive Mohr Circle and Failure Envelope

This Google Colab notebook provides an interactive visualization tool for understanding stress states using Mohr's Circle, specifically focusing on total and effective stresses, and the Coulomb failure envelope. It also dynamically visualizes physical orientations of potential fault planes based on the failure criteria.

Features
Interactive Sliders: Adjust key parameters in real-time:
σ1 (Sigma 1): Maximum principal stress.
σ3 (Sigma 3): Minimum principal stress.
Pf (Pore Fluid Pressure): Fluid pressure within the rock.
μ (Friction): Coefficient of internal friction for the failure envelope.
Total and Effective Stress Circles: Displays both Mohr circles, illustrating the effect of pore fluid pressure on the stress state.
Simplified Failure Envelope: Visualizes a linear Coulomb failure envelope based on the provided friction coefficient.
Hydrofracture Detection: Automatically identifies and highlights conditions leading to hydrofracture (tensile failure).
Unstable Orientations: Highlights portions of the effective stress circle that intersect the failure envelope, indicating planes prone to shear failure. It also calculates and displays the minimum and maximum dip angles for these unstable orientations.
Physical Representation: A companion plot dynamically shows the physical orientation of the principal stresses and highlights unstable fault planes or tensile fractures in the rock block.
Optimal Fault Plane: Draws the theoretically optimal fault plane for frictional sliding based on the Coulomb criterion.

Getting Started
Prerequisites
This notebook is designed to run in Google Colab. The following Python libraries are required (and are typically pre-installed in Colab):
matplotlib
numpy
ipywidgets
IPython.display

How to Use
Open in Google Colab: Click the "Open in Colab" badge (if provided, or manually upload the .ipynb file to Colab).
Run the Code Cell: Execute the main code cell containing the plot_mohr_and_physical function and the ipywidgets.interact call.
Adjust Sliders: Once executed, interactive sliders will appear below the code cell. Drag these sliders to change the values of σ1, σ3, Pf, and μ.
Observe Changes: The Mohr Circle and physical orientation plots will update in real-time, showing how changes in stress and pore pressure affect rock stability and potential failure modes.
