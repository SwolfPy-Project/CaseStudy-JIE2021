
========================
Case Study with SwolfPy
========================

This case study was implemented to illustrate the functionality of SwolfPy for SWM system analysis.
The case study first evaluated the global warming potential (GWP) of the SWM system in a hypothetical
but realistic city and then used the optimization functionality to minimize the GWP and meet a landfill
diversion target of 40%. Monte Carlo simulation was used to explore the robustness of the results to
the uncertainty in input data.

.. list-table:: Requirements
   :widths: auto
   :header-rows: 1

   * - Module 
     - Version
	 - Installation
   * - swolfpy-inputdata 
     - 0.2.0
	 - ``pip install swolfpy-inputdata==0.2.0``
	 - ``pip install swolfpy-processmodels``
   * - swolfpy-processmodels
     - 0.1.5
	 -``pip install swolfpy-processmodels==0.1.5``
   * - swolfpy
     - 0.2.1
	 - ``pip install swolfpy==0.2.1``