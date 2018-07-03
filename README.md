Files:

centos7-cis.ks

minimal.ks

cis-audit

This branch is a re-work of Ross Hamilton's work done for centos-7 with CIS v1.1 which I have updated to CIS v2.2 (Dec 2017)

centos7-cis.ks:  kickstart file for CentOS 7, aims to provide a starting point for a Linux admin to build a host which meets the CIS CentOS 7 benchmarks

minimal.ks:  A minimal kickstart file is provided so people can test their setup (PXE/DHCP etc) with a minimal amount of configuration going on.

cis-audit: A bash script to audit whether a host conforms to the CIS benchmarks. 

Aforementioned CIS benchmarks should be able to be found here https://benchmarks.cisecurity.org/tools2/linux/CIS_CentOS_Linux_7_Benchmark_v2.2.0.pdf

I'm not affliated with the Center for Internet Security in any way.
Use any material from this repository at your own risk.  

centos7-cis.ks will need extensive customising to suit a particular user's environment.  There's a lot of config in there because it suits me. e.g. CIS 6.4 /etc/securetty, change it to suit yourself. 


Feel free to get in touch about this.  Particularly with any errors or bugs!

Paul Branston <apbran at rannoch.demon.co.uk>
