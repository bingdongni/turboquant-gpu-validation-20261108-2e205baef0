# TurboQuant mixed cache validation

The [GitHub Actions run](https://github.com/bingdongni/turboquant-gpu-validation-20261108-2e205baef0/actions/runs/42452793125) checked out commit `965845934694fc70f5b14c70f7f581507e488a69` and ran the complete `src/test_turboquant.py` suite: 39 passed, including 3 CUDA regression cases. The [redacted job log](gpu-validation.log) records the result.

The ephemeral self-hosted runner used Windows, an NVIDIA GeForce RTX 4060 Laptop GPU, PyTorch 2.6.0+cu124 and CUDA 12.4. This is a correctness test; it does not measure throughput or validate other GPU architectures or a live vLLM deployment.
