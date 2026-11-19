# Activation Functions, Study Notes

Written answers about neural-network activation functions. This is a theory assignment, not a trained neural network or a benchmark project.

## Contents

`Assignment  Activation functions.ipynb` contains five question/answer sections in one code cell, followed by an empty code cell:

1. The role of activation functions and linear versus nonlinear layers.
2. Sigmoid, ReLU and tanh, with common benefits and limitations.
3. Nonlinearity in hidden layers.
4. Output-layer choices for classification and regression.
5. A proposed comparison of activation functions in a simple network.

The fifth section is an experiment plan only. There is no training implementation, dataset, loss curve, measured convergence comparison or validation metric. Statements in the notes are study explanations, not experimental findings from this repository. Choice of activation depends on the task, architecture, loss and optimization setup; broad speed/performance claims should not be treated as universal results.

## Read locally

Open the notebook with Jupyter or a notebook-capable editor. The non-empty code cell stores answers as comments and string literals; executing it does not train a model. No dataset or external service is required to read the notes.

No dependency environment is supplied because no numerical experiment is implemented. If adding one later, keep data/split/initialization/optimizer/budget fixed across comparisons and report actual held-out results, rather than copying expected behavior into a result claim.

## Preservation and verification

The original notebook, spelling, cells and git history are preserved. This update adds only an entrypoint README. The notebook JSON structure and five numbered sections were inspected; the content has not been converted into a new implementation or certified as a complete technical reference.
