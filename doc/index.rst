.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

RAIL: Resilient Analog Instance Language Enabled Mixed-Signal Circuits
======================================================================

It is an open source project for integrated circuits design. 
The project first releases a 65nm-based RAIL cell library and a tutorial to complete a simple RAIL design on September 2018.

The motivation of the RAIL project is,

- **to accelerate the analog/mixed-signal (AMS) designs**. Traditional analog/mixed-signal integrated circuit design exploits a fully custom flow. In other words, all works are done manually with huge time to markets.  RAIL ameliorates the methodology for design by introducing a verilog-like topology description language (TDL) and generates its behavior/schematic/layout automatically.

- **to enable process-portable design methodology**. Traditional AMS designs are highly process dependent, which makes it hard to transport across different technologies. This attribute seriously constraint the AMS to be an open source technology. Conventionally, even an IP is released, designers developing under other process still need to put similar efforts to reconstruct it. RAIL wants to change this status by the TDL and automatic flow. 

- **to exploit new methodolgy for digitiezed AMS design**. In the past decades, one big difference on analog circuits is a digitalized trend. Today's PLL contains digital filters and DCOs, rather than the charge-pump and analog filters. ADC are more and more SAR-based, rather than pipelined based. The basic cells of analog blocks are no longer amplifier now, because of it unfriendly on advanced tecnologies. The RAIL project decides to develop a new methodology to embrace the trend.



RAIL Project Repo link
----------------------
Release 0.1: https://github.com/rail-posh/rail65

Contents
--------

.. toctree::
   :maxdepth: 2
      
   railib/index
   bench
   compiler
   ip
   stack

