# ml-base

Docker images for running PyTorch and Cuda-based workloads. These can be run locally or in the cloud on something like GKE.

- `Dockerfile.base` - Inherits from `gcr.io/deeplearning-platform-release/pytorch-gpu` and installs further dependencies
- `Dockerfile.runtime` - Intended as a lighter weight inference-only image. To be used for APIs, etc.
- `Dockerfile.training-base` - Use for training new embeddings or models based on the huggingface transformer architecture.
