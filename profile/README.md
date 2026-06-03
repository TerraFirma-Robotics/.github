# TerraFirma Robotics

TerraFirma Robotics builds software infrastructure for earth science robotics, simulation support, geospatial context pipelines, perception workflows, and the public web presence that supports the company.

This GitHub organization is the private engineering home for active TerraFirma Robotics codebases.

## Active repositories

### Public web

- `terrafirma-robotics-website` - exact recovered source for the live TerraFirma Robotics public website.
- `qc3e-website` - exact recovered source for the live QC3E Ventures website.

### Asset generation and simulation support

- `procedural-asset-factory` - Python-native procedural 3D asset worker scaffold for synthetic data workflows.
- `trellis2-batch-image-to-3d` - batch image-to-3D worker for TRELLIS.2 GLB asset generation.

### Edge context and autonomy support

- `drone-sentinel-rag` - Databricks edge RAG pipeline for environmental context packaging.

## Working standards

- Repositories are private by default.
- Secrets stay out of Git. Use environment variables, GitHub secrets, Databricks secrets, or approved vaults.
- Generated datasets, model outputs, run folders, and deployment artifacts stay out of source control unless they are deliberately tiny fixtures.
- Production deployments and Vercel wiring require explicit approval before changes.
- Public claims should stay grounded in approved TerraFirma Robotics positioning and current technical status.

## Useful links

- Website: https://www.terrafirma-robotics.com/
- Contact: contact@terrafirma-robotics.com
