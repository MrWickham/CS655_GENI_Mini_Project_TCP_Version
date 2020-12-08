# CS655_GENI_Mini_Project_TCP_Version
Repository for GENI Mini Project: Performance Comparison of Various TCP Versions of BU CS 655

The report folder contains the report for the GENI Mini project.

The config files folder contains files for reserving resources: geni_tcp.xml for part 1 and exp2.rspec for part 2.

The experiment records folder contains records for part 1 and part 2. The part 1 folder contains logs of throughput and delay with three different TCP variants: Reno, Cubic and Vegas, both from pc1 to pc2 and from pc1 to delay. The part 2 folder contains logs of throughput measurements in pairs over time. For example, exp_bbr.txt contains logs that pc1 with TCP BBR sending first, then around 5 seconds later, pc2 with various variants starts sending.

The diagrams folder contains the diagrams of experiment records for part 1 and part 2.

The demo video folder contains a demo video with a quick walkthrough of this project.