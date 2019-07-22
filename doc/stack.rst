==========
RAIL Stack
==========

Step 1: Clone repo to local and prepare for the execution

.. code-block:: tcl


  git clone railstack
  alias rail source <railstack>/rail.run
  cd <railstack>
  ln -s ./rail_src1/rail.run .


Step 2: Checklist

  cds.lib: include proper lib path to tsmcN65, analogLib, basic, rail65
  
  

Step 3: Run command

.. code-block:: tcl


  rail -libname <dest_library> -v <verilog netlist>
  
where:

  <dest_library> is the name of library where rail saves the new design and the library is named as "demo" by default.
  
  <verilog netlist> is the analog netlist of new design. The file path is set to ~/simulation/icc/netlist by default
  

For example:

.. code-block:: tcl


  rail -libname demo -v /home/cxchen2/workspace/VTS_T65_RAIL/import_netlist/bench_test.v




This command will do the following:

  create new library to demo.
  
  create option.xil config file. The config file saved as ~/simulation/icc/option.xil
  
  run verilog_in to create schematic for cell "tench"
  
  

  
  
  
  
