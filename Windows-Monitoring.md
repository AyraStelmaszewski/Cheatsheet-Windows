The purpose of this readme is to reference fews windows monitoring tools with explaination. 

## Sysmon
==============================================================================================================
**sources**
https://syedhasan010.medium.com/sysmon-how-to-setup-configure-and-analyze-the-system-monitors-events-930e9add78d
==============================================================================================================
Due to active development of the project, newer artifacts and evidence sources are constantly being added to Sysmon’s capabilities. 
However, you can get a quick idea on how Sysmon can aid you in identifying anomalous activities by checking this short list of features:
<br>
    - Log process creation — command line, basic process information, parent process information, etc.
    - Network communications — connection’s source processes, IPs, ports, hostnames, etc.
    - Hashing process images — a hash of process image files is available in SHA1, MD5, SHA-256, or the IMPHASH format
    - DLL loading — identify the loading of DLLs along with their hashes
    - File modification — Identify changes in file creation times, a technique most commonly utilized by attackers to avoid detection
    - Kernel-mode malware, rule filtering based on False Positives, session identification, correlations, and much more!