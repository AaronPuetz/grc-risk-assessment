**Company Profile: Elmbrook Surgery**

**Note:** Elmbrook Surgery is a fictional organization created for this risk assessment project. Any resemblance to a real practice is coincidental.  
**1\. Overview**  
Elmbrook Surgery is a small NHS GP practice in Nottingham, England. Providing routine appointments, repeat prescriptions, vaccinations, health checks and home visits.

| **Detail**           | **Value**                 |
| -------------------- | ------------------------- |
| Type of organization | NHS GP practice           |
| Registered patients  | About 8,000               |
| Staff                | 16                        |
| Sites                | 1 building                |
| Opening hours        | Monday–Friday, 8am–6:30pm |

# **2\. Staff**

| **Role**             | **Number** | **Notes**                                                             |
| -------------------- | ---------- | --------------------------------------------------------------------- |
| GP partners          | 3          | Own and run the practice                                              |
| Salaried GP          | 1          |                                                                       |
| Practice nurses      | 2          |                                                                       |
| Healthcare assistant | 1          |                                                                       |
| Practice manager     | 1          | Also responsible for IT and data protection, alongside their main job |
| Receptionists        | 5          | Some part-time                                                        |
| Administrators       | 3          | Handle letters, scanning and referrals                                |

**IT support** is outsourced to a small local IT company; helping only when something breaks but does not monitor systems on a day-to-day basis.

# **3\. Technology**

- **Clinical system:** a cloud-hosted electronic patient record system, used for patient records, appointments and prescriptions
- **Computers:** 16 Windows desktops in consulting rooms and reception, plus 3 laptops used by GPs for home visits and remote working
- **Email:** NHSmail for clinical email; a separate general email account for supplier and admin messages
- **File storage:** a small file server in a cupboard behind reception, holding scanned letters, staff rotas, HR files and finance spreadsheets
- **Backups:** a network storage device (NAS) in the same cupboard backs up the file server every night
- **Network:** one internet connection, a staff Wi-Fi network and a free guest Wi-Fi network for patients in the waiting room
- **Website:** a practice website with an online contact form, built and hosted by a local web design company
- **Phones:** an internet-based (VoIP) phone system
- **Other devices:** 4 printers, 1 scanner, and an older desktop PC connected to the ECG (heart monitoring) machine

# **4\. Data Held**

| **Data**                 | **Examples**                                                 | **Sensitivity**                                 |
| ------------------------ | ------------------------------------------------------------ | ----------------------------------------------- |
| Patient health records   | Diagnoses, medications, test results, consultation notes     | Very high (special category data under UK GDPR) |
| Patient personal details | Names, addresses, dates of birth, phone numbers, NHS numbers | High                                            |
| Staff records            | Contracts, bank details, sickness records                    | High                                            |
| Practice finances        | Payroll, supplier invoices, accounts                         | Medium                                          |
| Operational data         | Rotas, policies, meeting notes                               | Low                                             |

# **5\. Current Security Situation**

The practice has grown quickly, and security has not kept up. The practice manager has raised the following observations:

- Reception staff share a single login on two of the front desk computers so they can swap shifts quickly.
- Some staff write passwords on sticky notes near their screens.
- Windows updates are installed when someone remembers, not on a schedule.
- The ECG machine's PC runs an old version of Windows that no longer receives security updates, because the ECG software will not run on anything newer.
- Backups are stored in the same cupboard as the file server and have never been tested by restoring data from them.
- Not all GP laptops are known to have encrypted hard drives.
- Accounts for staff who have left are not always disabled promptly.
- Staff have had no formal cyber security or phishing awareness training.
- The guest Wi-Fi is believed to be separate from the staff network, but this has never been checked.
- There is no written incident response plan.

# **6\. Scope of This Risk Assessment**

**In scope:**

- All staff devices, the file server, backups, network and Wi-Fi
- Email and user accounts
- Patient, staff and financial data held by the practice
- Staff behavior and processes

**Out of scope:**

- The internal security of the cloud clinical system (run by the supplier)
- The internal security of NHSmail (run by the NHS)
- The web design company's own systems

These suppliers are still recorded as third-party dependencies, as a problem on their side would affect the practice.