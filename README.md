# GPU Kernel Lab

An interactive research walkthrough for matrix-free FEM, fused CUDA kernels, GPU memory traffic, SIMP topology optimization, BF16 WMMA, solver performance, and thesis experimentation.

## Website

The website is deployed with GitHub Pages when enabled for this repository:

https://roshanbajaj99.github.io/Kernel_Lab/

## Deployment

The workflow at `.github/workflows/pages.yml` publishes the root of the `main` branch on each push and supports manual deployment from the Actions tab.

To enable GitHub Pages for the first time, open **Settings → Pages → Build and deployment → Source**, select **GitHub Actions**, and save. The workflow will publish the static `index.html`; no backend or build step is required.
