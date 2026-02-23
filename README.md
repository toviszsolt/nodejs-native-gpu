# Native GPU Computing in Node.js - A new era is dawning

> **BREAKING**: The first native GPU-accelerated computation addon for Node.js - _A new era is dawning - 2025.09.15_

## ⚠️  Project Status: Indefinitely Suspended

Effective immediately, active development of this project is suspended for an indefinite period.

While the technical milestones achieved here prove that native GPU computing in Node.js is not just possible but revolutionary, technology cannot exist in a vacuum.

Recent global events and the current trajectory of the AI industry have made it clear that the ecosystem—driven by world leaders and major investors—is failing to handle this power with the necessary maturity. Ethical considerations are being bypassed, and the concept of social responsibility is being eroded in favor of unrestrained acceleration.

As a Chief Software Architect, I have a responsibility not just for the code I write, but for the impact it generates. Until I see a tangible shift towards responsible governance and ethical stewardship in the AI sector, I cannot in good conscience continue to advance this technology under the current conditions.

This repository remains as a proof of concept and a testament to what is technically achievable. The future is still here, but it must be built on a foundation of responsibility, not just raw compute power.

February 23, 2026

## ⚠️ Project Status: Suspended until Q2 2026

**Effective immediately, development of this project is suspended.** 

As a business owner, I must prioritize my profitable ventures and clients over.

I am archiving the current state of the project to focus on my primary business. I will re-evaluate the market situation and potential sponsorship opportunities at the end of Q2 2026.

November 29, 2025

## What is this Repo

Hello World! My name is **Zsolt Tövis** and I officially announce that **on September 15, 2025, I successfully ran
computational tasks on the GPU in a Node.js environment** using a native addon. This is a milestone in the JavaScript
world, as developers can now directly access the power of the GPU without relying on Python or other external libraries.

This repo is not a project, but an **official statement to document this historic event** and lay the foundation for
future development. I will regularly update information about the development process, share challenges, and milestones.

## What I Have Achieved

I have solved the creation of a native GPU addon that enables computational tasks to run on the GPU in Node.js.
GPU-accelerated computations are already working, and the addon can handle multiple platforms and different GPU
backends. This is no longer just a plan, but reality.

- Native addon for Node.js that allows direct GPU access
- Multi-platform support (Windows, Linux, macOS)
- GPU backend support (Vulkan, DirectX, Metal, OpenGL, WebGL)
- GPU-accelerated computational tasks
- Asynchronous operations with async/await support

## Why This Matters

This development is a revolutionary step in the Node.js world, as it allows developers to harness the power of the GPU
without relying on Python or other external libraries. It unifies frontend and backend development in a single language,
simplifying development processes and reducing complexity.

## Thousands of Projects Await Native GPU Acceleration in Node.js

Instead of launching a project that simply provides GPU access, I will showcase various projects that leverage this
technology. These projects span different fields, including machine learning, image processing, and other
compute-intensive tasks.

## What's Next

- The Node.js world will never be the same
- Thousands of projects are waiting to leverage this paradigm shift
- Follow the updates, because the future is now

## Proof of Concept

The initial proof of concept has been successfully implemented, demonstrating the feasibility of GPU-accelerated
computations in Node.js. This includes basic tensor operations, neural network layers, and activation functions running
on the GPU. I publish proof of concept code in the [`proof-of-concept`](proof-of-concept) folder of this repository. In
addition, I will continuously upload comparisons and benchmarks for each completed function.

## Support the Development

If you want to support the development of this project, you can:

- Star the repository to show your interest
- Share your ideas and feedback
- Spread the word about this project
- Donate to support further development

## Enterprise — Invest, Partner, Innovate

Are you representing a company or large enterprise? You are welcome to invest in the future of native GPU computing for
Node.js. Corporate sponsors and organizations can make significant donations or contact me directly to discuss business
opportunities, partnerships, or custom enterprise solutions. For all business inquiries, please reach out via email or
GitHub.

## Donation channels

- [GitHub Sponsors](https://github.com/sponsors/toviszsolt)
- [PayPal](https://paypal.me/toviszsolt)
- **OpenCollective**: This repo needs 100 stars to enable this option.

## Follow the Updates

### October 1, 2025

- After intense low-level optimizations and deep engine work, the implementation now achieves performance that is competitive with established frameworks.
- Progress is slower than originally planned due to the custom engine development, which requires careful design to ensure future integration and maintainability.
- The engine is still not fully complete; key work remains to make it fully integrable with the PyTorch-compatible API and broader system.
- Focus remained on matrix multiplication and core engine improvements, testing on mid-range GPUs. Performance gains are evident across devices, though results vary depending on hardware.

### September 19, 2025

- Started creating benchmarks on different GPUs, comparing the implementation with PyTorch. Initial performance was noticeably lower than PyTorch, revealing clear areas for improvement.
- Today is less of a milestone and more of a realization: I’m temporarily putting some features aside to dive deep into optimization and achieve better performance.
- Also realized that starting with a TensorFlow-compatible API was not the best choice; a PyTorch-compatible API will be a more realistic goal for the first round.

### September 17-18, 2025

Another milestone: I have successfully implemented Autograd, Dense layers, and Optimizer for neural networks, enabling
backpropagation and learning on the GPU in Node.js. I have also implemented the complete neural network training
process, including forward and backward passes and optimizer steps.

- Autograd: automatic differentiation for neural networks
- Dense layer: fully connected layer for neural networks
- Optimizer: optimization algorithms for neural networks
- Complete neural network training pipeline: learning and inference on GPU
- Layers functions: `createDenseLayer`, `denseForward`, `denseForwardAutograd`, `denseParameters`, `denseParamCount`
- Autograd activations: `reluAutograd`, `sigmoidAutograd`, `tanhAutograd`, `reluBackward`, `sigmoidBackward`,
  `tanhBackward`
- Optimizers: `createSGDOptimizer`, `createAdamOptimizer`, `sgdStep`, `adamStep`, `sgdZeroGrad`, `adamZeroGrad`

### September 16, 2025

Another milestone: I have successfully implemented neural network activation functions, tensor manipulations, and loss
functions. This proves that native GPU acceleration is not just theory, but practical application.

- Neural network activations: `elu`, `hardSigmoid`, `leakyRelu`, `relu`, `selu`, `sigmoid`, `softmax`, `softplus`,
  `softsign`, `tanh`
- Tensor manipulations: `cast`, `concat`, `expandDims`, `gather`, `oneHot`, `reshape`, `slice`, `squeeze`, `stack`,
  `tile`
- Aggregation functions: `argmax`, `argmin`, `cumsum`, `max`, `mean`, `min`, `norm`, `prod`, `reduceMax`, `reduceMean`,
  `reduceMin`, `reduceProd`, `reduceSum`, `sum`
- Comparison functions: `equal`, `greater`, `greaterEqual`, `less`, `lessEqual`, `notEqual`
- Loss functions: `binaryCrossEntropy`, `binaryCrossEntropyAutograd`, `huberLoss`, `meanSquaredError`,
  `meanSquaredErrorAutograd`, `softmaxCrossEntropy`

### September 15, 2025

I have successfully run computational tasks on the GPU in Node.js using a native addon. This is no longer just a plan,
these are facts.

I decided that the first library to leverage native GPU acceleration in Node.js will be a TensorFlow.js-compatible API.
This will allow developers to easily switch to Node.js with native GPU acceleration without significant changes to their
code.

Tensor API development has started. What is already done and works on GPU in Node.js:

- Creations: `create`, `eye`, `fill`, `fromArray`, `linspace`, `ones`, `random`, `randomNormal`, `randomUniform`,
  `range`, `zeros`
- Core operations: `add`, `divide`, `minimum`, `maximum`, `modulo`, `multiply`, `power`, `subtract`
- Math functions: `abs`, `acos`, `asin`, `atan`, `atan2`, `ceil`, `cos`, `exp`, `floor`, `log`, `log1p`, `neg`, `round`,
  `sin`, `sqrt`, `tan`
- Logical operations: `logicalAnd`, `logicalNot`, `logicalOr`
- Linear algebra: `det`, `inverse`, `matmul`, `qr`, `svd`, `trace`, `transpose`
- Utilities: `dispose`, `getData`, `where`

## Be Part of History

⭐ **Star this repo** to witness the birth of native GPU computing in Node.js!
