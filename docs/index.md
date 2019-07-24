# OPERA: Open source Power Efficient SoCs with RISC-V and AI accelerators
# 面向RISC-V和智能加速器的高效开源SoC

## Why Open Source ?

过去，所有的成功的商业化芯片，销量都在10KK这个数量级以上，由此，单一芯片设计导致的NRE（一次性工程费用）往往会以极小的量分摊到每颗芯片上。
而未来，随着市场细分，碎片化的使得未来的芯片可能只有100K的销量，这这个数量级上，NRE成为芯片的重要成本。此时，降低NRE的手段是非常重要的。在这一愿景下，开源设计成为了未来芯片设计场景的重要基石。过去几年，以RISC-V为代表的开源处理器不断涌现。同时，我们也认为以AI加速器为代表的非“标准件”是更值得关注的开源项目。

因此，OPERA 项目，即面向RISC-V和智能加速器的高效开源SoC项目，成为了我们瞄准的一大趋势。本项目努力通过开源与完整datasheet的方式，让初入门的电路工程师了解AIoT芯片的设计流程，描述AIoT系统中设计要点，并提供源码。希望大家在OPERA项目的基础上，构造不同场景的高性能SoC。

## Project Goals

其实，在规划Opera Project的时候已经非常多开源的AI加速器，以及SoC了。最有名的例子是NVIDIA的[NVDLA](nvdla.org)和美国华盛顿大学的[TVM-VTA](https://docs.tvm.ai/vta/index.html)。这两个项目致胜的关键在于他们完整的编译器/工具链，对于通用的NN加速器而言，是非常不错的选择。
但是ASIC SoC的核心竞争力是PPA，特别是对于高度专用的加速器，通用加速器的PPA很可能毫无竞争力。以TVM-VTA为例，其支持的主要算法为矩阵乘模块，采用类TPU的Systolic Array架构，但是该架构在实现3x3 CNN上的优化显然是不足的。

Opera Project 是

## What's the difference ?
