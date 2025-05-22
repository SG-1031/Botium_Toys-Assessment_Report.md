# Controls and Compliance Checklist

## Controls Assessment Checklist
| Yes | No  | Control                                        | Explanation |
|-----|-----|------------------------------------------------|-------------|
|     |  X  | Least Privilege                                | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
|  X  |     | Disaster recovery plans                        | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
|  X  |     | Password policies                              | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |
|  X  |     | Separation of duties                           | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll. |
|  X  |     | Firewall                                       | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
|     |  X  | Intrusion detection system (IDS)               | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
|  X  |     | Backups                                        | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
|  X  |     | Antivirus software                             | Antivirus software is installed and monitored regularly by the IT department. |
|  X  |     | Manual monitoring for legacy systems           | Legacy systems are monitored and maintained, but without a clear schedule or intervention policy. |
|     |  X  | Encryption                                     | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
|  X  |     | Password management system                     | No system is currently in place; implementing one would improve password handling productivity. |
|  X  |     | Locks (offices, storefront, warehouse)         | Physical locks are sufficiently installed and functioning. |
|  X  |     | Closed-circuit television (CCTV) surveillance  | CCTV is installed and operational at the store's physical location. |
|  X  |     | Fire detection/prevention systems              | Fire alarms and prevention systems are in place and functional. |

## Compliance Checklist

### **Payment Card Industry Data Security Standard (PCI DSS)**
| Yes | No  | Best Practice                                        | Explanation |
|-----|-----|------------------------------------------------------|-------------|
|     |  X  | Only authorized users have access to card data       | All employees currently have access to internal data. |
|  X  |     | Credit card info is stored in a secure environment   | Data is not encrypted and all employees have access. |
|  X  |     | Implement encryption for transactions                | Encryption is not currently in use. |
|  X  |     | Adopt secure password policies                       | Password policies are minimal and no management system is in place. |

### **General Data Protection Regulation (GDPR)**
| Yes | No  | Best Practice                                        | Explanation |
|-----|-----|------------------------------------------------------|-------------|
|     |  X  | E.U. customers’ data is private/secured              | Encryption is not in use. |
|  X  |     | 72-hour breach notification policy in place          | Botium has a plan in place. |
|  X  |     | Ensure data is properly classified and inventoried   | Data has been inventoried, but not classified. |
|  X  |     | Enforce privacy policies and procedures              | Policies are developed and enforced among staff. |

### **System and Organization Controls (SOC Type 1 & 2)**
| Yes | No  | Best Practice                                        | Explanation |
|-----|-----|------------------------------------------------------|-------------|
|     |  X  | User access policies established                     | Least Privilege and separation of duties not implemented. |
|  X  |     | Sensitive data (PII/SPII) is confidential            | Encryption not implemented. |
|  X  |     | Data integrity measures are in place                 | Data integrity ensured. |
|  X  |     | Authorized data access only                          | All employees have access, restrictions are needed. |

## Recommendations
To reduce risk and improve Botium Toys’ security posture, the following actions are recommended:
- **Implement key controls**: Least Privilege, separation of duties, encryption, IDS, disaster recovery plans, password management system, scheduled legacy system maintenance.
- **Improve compliance**: Enforce restricted access to sensitive data, implement encryption for PII and financial data, and properly classify all inventoried assets.
