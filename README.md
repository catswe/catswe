I also like to document my open-sourced work, many of which are rather random. It reminds me of the good work I have done, no matter how trivial

<!--
## Pending:

https://github.com/vllm-project/tpu-inference/pull/1929 [Kernel][GMM] Fix truncation bias during LHS quantization

https://github.com/vllm-project/tpu-inference/pull/1911 [Kernel][GMM] Support zero point asymmetric quantization

https://github.com/vllm-project/tpu-inference/pull/1656 Pass dequantization dtype to match comments (approved)

https://github.com/vllm-project/tpu-inference/pull/1504 [Doc] Update benchmarking README

https://github.com/jax-ml/jax/pull/34623 [Doc] Update jnp.argmin/argmax doc for Pallas TPU)
-->

## Merged:

https://github.com/vllm-project/tpu-inference/pull/1644 [AWQ][MoE] Support AWQ MoE

https://github.com/vllm-project/tpu-inference/pull/1729 Support DeepSeek-V2-Lite-Chat-FP8

https://github.com/vllm-project/tpu-inference/pull/1388 Support FP8 quantization

https://github.com/vllm-project/tpu-inference/pull/1440 Handle unaligned FP8 block quantization edge case

https://github.com/vllm-project/tpu-inference/pull/1659 Properly register quantization configs

https://github.com/vllm-project/tpu-inference/pull/1472 Support MoE sigmoid scoring

https://github.com/vllm-project/tpu-inference/pull/1656 Update dequantization dtype to match comments

https://github.com/vllm-project/tpu-inference/pull/1454 Remove dead code after upstream removal

https://github.com/vllm-project/vllm/pull/33501 Fix DeepSeek RoPE initialization error

https://github.com/stanford-crfm/levanter/pull/974 Initial implementation of power scheduler

https://github.com/llvm/torch-mlir/pull/4228 [OnnxToTorch] Casting float to integer should round to nearest for pow with int result type

https://github.com/pytorch/pytorch/pull/163616 Update doc for torch.index_select, which can accept IntTensor as a parameter

https://github.com/mintisan/awesome-kan/pull/139 Add LinearKAN

https://github.com/AlphaGPU/leetgpu-challenges/pull/90 Script to generate starter code for GPU challenges

https://github.com/TheOdinProject/javascript-exercises/pull/370 Update fibonacci-solution.js

https://github.com/TheOdinProject/javascript-exercises/pull/368 Update sumAll-solution.js swap algorithm to standard method

https://github.com/TheOdinProject/javascript-exercises/pull/369 Reformat test parameters for consistency

https://github.com/PolicyEngine/policyengine-app/pull/1283 Render p in markdown as `<p>` instead of `<div>` for blogs

https://github.com/PolicyEngine/policyengine-app/pull/1269 Rename title in PolicyBreakdown component

https://github.com/fullstack-hy2020/fullstack-hy2020.github.io/pull/2981 Update part3b.md (add note on fly.io deployment error)

https://github.com/fullstack-hy2020/fullstack-hy2020.github.io/pull/2980 Update part9f.md (fix incorrect link)

https://github.com/fullstack-hy2020/fullstack-hy2020.github.io/pull/2979 Update part3d.md (fix incorrect links)

# Bug Reports:

https://github.com/jax-ml/jax/issues/34620 [Pallas TPU] jnp.argmax returns last index instead of first index on ties

https://github.com/jax-ml/jax/issues/35492 [Pallas TPU] Incorrect result for jnp.dot with uint4 rhs and bfloat16 lhs

https://github.com/jax-ml/jax/pull/34674 [Mosaic] Update logistic lowering to correctly handle BF16 inputs

# Guide:

[A Guide on Overcoming Nerd Snipe, Info Junk, and FOMO](https://docs.google.com/document/d/1XJcfWStffLsu96w6jwWeFmY1sPXLS3boArlbipsk3JE/edit?tab=t.0)
