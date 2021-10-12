## Minispec Hardware Description Language 

Minispec is a simple but full-featured Hardware Description Language (HDL). It is inspired by Bluespec, and the current implementation heavily leverages the Bluespec compiler, e.g., for type checking and to produce Verilog code. However, Minispec has a minimalistic feature set that seeks to reduce its learning curve.

Minispec is open-source and available on [github](https://github.com/minispec-hdl/minispec). The toolchain provides a complete design environment, including an integrated compiler, synthesis tool, and Jupyter-based interactive notebooks. This makes Minispec useful for teaching purposes. However, Minispec can also be used with other synthesis tools.

Minispec was originally designed by Daniel Sanchez for use in MIT's [6.004](https://6004.mit.edu).

### Resources

* Minispec tutorials
  * Combinational logic [[interactive]](https://github.com/minispec-hdl/minispec-tutorials/Combinational.ipynb) [[pdf]](minispec_combinational.pdf) [[pdf, executed]](minispec_combinational_executed.pdf)
  * Sequential logic [[interactive]](https://github.com/minispec-hdl/minispec-tutorials/Sequential.ipynb) [[pdf]](minispec_sequential.pdf) [[pdf, executed]](minispec_sequential_executed.pdf)
  * These tutorials provide a first introduction to Minispec. They are interactive Jupyter notebooks, but we also provide PDF printouts for offline use.
* [Minispec reference](minispec_reference.pdf)
  * This is the primary reference for the Minispec language, covering its syntax and semantics in full. It is more more detailed than the Minispec tutorials, and is useful mainly to answer particular questions on syntax and to learn the language in depth.
