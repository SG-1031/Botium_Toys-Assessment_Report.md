# Control Categories and Types
## Control Categories
Controls within cybersecurity are grouped into three main categories:
- **Administrative/Managerial Controls**  
- **Technical Controls**  
- **Physical/Operational Controls**

### Administrative/Managerial Controls
These address the human component of cybersecurity. They include policies and procedures that define how an organization manages data and employee responsibilities in protecting the organization.
> While administrative controls are typically policy-based, their enforcement may require the use of technical or physical controls.

### Technical Controls
Technical solutions such as firewalls, IDS/IPS, antivirus, and encryption. These are used to enforce policies and protect systems.

### Physical/Operational Controls
These include locks, surveillance cameras, and other mechanisms that limit physical access to systems and infrastructure.

## Control Types
Control types include:
1. **Preventative** – Designed to stop incidents before they occur  
2. **Corrective** – Restore systems after an incident  
3. **Detective** – Identify and report incidents  
4. **Deterrent** – Discourage potential threats

These work together to establish defense in depth.
## Control Matrices

### Administrative/Managerial Controls
| Control Name                | Control Type  | Control Purpose                                                                 |
|-----------------------------|---------------|---------------------------------------------------------------------------------|
| Least Privilege             | Preventative  | Reduce risk and overall impact of malicious insider or compromised accounts     |
| Disaster recovery plans     | Corrective    | Provide business continuity                                                     |
| Password policies           | Preventative  | Reduce likelihood of account compromise through brute force/dictionary attacks  |
| Access control policies     | Preventative  | Bolster confidentiality and integrity by defining access roles                  |
| Account management policies | Preventative  | Manage account lifecycle; reduce attack surface                                 |
| Separation of duties        | Preventative  | Reduce risk and impact of insider threats                                       |

### Technical Controls
| Control Name              | Control Type  | Control Purpose                                                                   |
|---------------------------|---------------|-----------------------------------------------------------------------------------|
| Firewall                  | Preventative  | Filter unwanted or malicious network traffic                                      |
| IDS/IPS                   | Detective     | Detect and prevent anomalous traffic                                              |
| Encryption                | Deterrent     | Provide confidentiality for sensitive data                                        |
| Backups                   | Corrective    | Restore/recover from incidents                                                    |
| Password management       | Preventative  | Reduce password fatigue                                                           |
| Antivirus (AV) software   | Corrective    | Detect and quarantine known threats                                               |
| Manual monitoring         | Preventative  | Manage threats in out-of-date systems                                             |

### Physical/Operational Controls
| Control Name                         | Control Type           | Control Purpose                                                |
|--------------------------------------|------------------------|----------------------------------------------------------------|
| Time-controlled safe                 | Deterrent              | Reduce physical attack impact                                  |
| Adequate lighting                    | Deterrent              | Deter threats by reducing hiding places                        |
| CCTV                                 | Preventative/Detective | Discourage and record unauthorized activities                  |
| Locking cabinets (network gear)      | Preventative           | Protect network equipment from physical tampering              |
| Alarm service signage                | Deterrent              | Deter threats by signaling security measures                   |
| Locks                                | Deterrent/Preventative | Limit unauthorized physical access                             |
| Fire detection and prevention systems| Detective/Preventative | Detect and limit fire damage                                   |
