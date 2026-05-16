# Login Log Analysis using Splunk Enterprise-Detection-Lab

### Objective
[Brief Objective]

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logins within a Security Information and Event Managaement (SIEM) system, explore authentication logs, identify failed and successful login attempts, detect suspicious activity patterns, and gain hands on experience with basic SOC analyst investigation workflows,to mimic real world attack scenarios. This project was designed to deepen understanding of threat Detection, attack patterns,and defensive strategies.

### Skills Learned
- Improved understanding of SIEM concepts and pratical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to identify suspicious login behavior, attack patterns, and potential brute-force activity.
- Enhanced knowledge of network protocols and security Vulnerabilities.
- Development of critical thinking and problem solving skills in cybersecurity investigations and incident analysis.

### Tools Used
- Splunk Enterprise (SIEM) for log ingestion and analysis.

### Steps
- Imported the dataset into splunk
- Ran search to find number of faied login attempts, ip with with the highest failed logins, username that appears the most, any pattern that looks suspicious.
- Analyzed the results

### Key Findings
- The Splunk analysis revealed 92 failed login attempts originating from multiple IP addresses.
- The IP 203.0.113.45 generated the highest number of failures(19 attempts) indicating potential malicious activity.
- Several IPs attempted logins against multiple usernames,suggesting a password spraying attack pattern.
- Time based analysis revealed spikes in failed logins around 13:00, further indicating automated attack behaviour.

### Conclusion

Based on these findings, the activity likely represents a brute-force authentication attack.


Ref 1 :Graphical representation of username that appears the most.

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/graphical%20representation%20of%20username%20that%20appears%20the%20most.png)

Ref 2:Highest ip address.

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/highest%20ip%20address.png)

Ref 3:Username by count.

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/username%20by%20count.png)

Ref 4:Username that appears most.

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/username%20that%20appears%20most.png)

Ref 5: Username,count ip address.

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/username%2Ccount%20ip%20address.png)

Ref : Failed Login

![image alt](https://github.com/Eno-Lab28/-Login-Log-Analysis-using-Splunk-Enterprise-/blob/50944ead31f7013ecf8e8933aa569661cc8cfd33/FAILED%20LOGIN.png)
