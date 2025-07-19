# SOC-Analyst-Portfolio
A portfolio of cybersecurity projects and labs, including SOC detection, threat hunting, and EDR response simulations using a home lab.
# 🛡️ So You Want To Be a SOC Analyst 2.0 (Home Lab Version)

This project follows the “So You Want To Be a SOC Analyst 2.0” course, recreated entirely in my own home lab using real tools, detections, and hands-on attack simulations.

## 🔧 Skills Demonstrated
- Building detections from real-world credential dumping and ransomware behavior  
- Writing and tuning Sigma/YARA rules  
- Validating rule performance in real time using test attacks  
- Using LimaCharlie to deploy, test, and tune rules on live endpoints  
- Manual event log analysis using Event Viewer and Sysmon logs  
- Creating blocking rules and confirming success with endpoint testing

## 🧪 Lab Structure
- **Endpoint**: Windows 10 virtual machine with Sysmon installed  
- **EDR Platform**: LimaCharlie (live agent installed)  
- **Attack Simulation**: Atomic Red Team + manual execution  
- **Log Analysis**: Event Viewer, Sysmon, LimaCharlie console  
- **Detection Tuning**: Tested rule success/failure and iterated

## 📂 Project Artifacts
Inside the `soc-analyst-lab/` folder:
- ✅ Detection and blocking rules  
- 📸 Screenshots of detections and rules triggering  
- 🔍 Test results from credential dumping and ransomware scenarios  
- 🧬 YARA rules and Sigma customizations
