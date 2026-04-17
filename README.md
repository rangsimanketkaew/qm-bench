## Performance Test of Quantum Chemistry Software

1. [Gaussian: G16 and Nvidia Tesla P100 GPU Acceleration](gaussian-g16-testla-p100/gaussian-benchmark-g16-testla-p100.md)
   Compares Gaussian 16 GPU-enabled runs on Tesla P100 against CPU-only execution and discusses practical GPU input setup.
2. [Gaussian: G16 on Intel Xeon Gold 6148](gaussian-g16-gold-6148/gaussian-benchmark-g16-gold-6148.md)
   Benchmarks G16 B.01 vs G09 E.01 for DFT optimization/frequency workloads on Xeon Gold 6148.
3. [LAMMPS: DPD Simulation on CentOS](lammps-dpd/lammps-benchmark-dpd.md)
   Reports DPD simulation performance of LAMMPS on a CentOS workstation for a 100,000-particle polymeric system.
4. [NWChem: DFT Calculation running on Ryzen Threadripper](nwchem-dft-ryzen/nwchem-benchmark-dft-ryzen.md)
   Evaluates NWChem DFT single-point performance on Ryzen Threadripper 1950X and compares scaling against Xeon E5-2697 v3.
5. [NWChem: Integral Evaluation Approaches](nwchem-integral-eval/nwchem-benchmark-integral-evaluation-approaches.md)
   Tests NWChem direct/semi-direct integral strategies and memory layouts to identify faster CDFT execution settings.
6. [NWChem: MPI Parallelization Efficiency for DFT Calculation](nwchem-mpi-dft/nwchem-benchmark-mpi-dft.md)
   Compares MPI and MPI/CASPER scaling behavior for large-core-count NWChem DFT jobs on a distributed HPC cluster.
7. [NWChem: CCSD(T) and CCSD[T] Calculation on GeForce GTX 1050 Ti](nwchem-ccsdt-tce-gtx-1050ti/nwchem-ccsdt-tce-gtx-1050ti.md)
   Demonstrates CUDA-enabled NWChem TCE setup for CCSD(T)/CCSD[T] and validation steps on a GTX 1050 Ti.
