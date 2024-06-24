# Argo CD App-of-Apps Pattern Example

This repository demonstrates the "app-of-apps" pattern using Argo CD with both Kustomize and Helm examples.

## Structure

- `applications/`: Contains the Argo CD applications definitions.
- `apps/`: Contains the actual applications to be deployed, using Kustomize and Helm.

## Applications

- **Kustomize App**: A simple app configured with Kustomize.
- **Helm App**: A simple app configured with Helm.

## Overlays

Overlays are provided for both development and production environments.
