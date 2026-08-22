# Repressilator: Simulating a Gene Regulatory Circuit

A simple Jupyter notebook that walks through the simulation of the **repressilator**, [a synthetic gene regulatory circuit consisting of three mutually repressing genes](https://www.nature.com/articles/35002125).

The notebook introduces how to:

- Set up a basic ODE solver (Euler's method) in numpy
- Define the ordinary differential equations (ODEs) describing the repressilator
- Choose initial conditions and model parameters
- Visualize the resulting gene-expression dynamics
- Explore how changing parameters affects oscillatory behavior

The goal is to provide a compact, hands-on introduction to using ODE models to understand dynamical systems in gene regulation.

## Run the notebook

You can run the notebook locally with Jupyter, or open it directly in **Google Colab**:

**[Open in Google Colab](https://tinyurl.com/repressilator-notebook)**

### Local installation

Clone the repository and launch the notebook:

```bash
git clone https://github.com/your-username/repressilator.git
cd repressilator
jupyter notebook
