# FlashAttention Pre-built Wheels

!pip install build wheel
!git clone -b v1.0.9 https://github.com/Dao-AILab/flash-attention
!cd flash-attention && MAX_JOBS=1 TORCH_CUDA_ARCH_LIST=7.5 pip wheel . --no-deps --verbose
