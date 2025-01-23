# Controls and Compliance Assessment 

## Case Study

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scenario
Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope 

The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

### Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

### Current assets
Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

### Risk assessment

#### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

#### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

#### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

#### Additional Info 

In Cybersecurity, control types can be classified in three ways: 
1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

Control types (providing defense and protecting assets) include, but are not limited to:
1. Preventative (preventing an incident from occurring in the first place)
2. Corrective (restoring an asset after an incident)
3. Detective (Determining whether an incident has occurred or is in progress)
4. Deterrent (Discouraging attacks)

5. ## Controls Assessment Checklist

Does Botium Toys currenly have this control in place? 

| Yes / No / ? | Control | Explanation |
| :---------      |    :---:   |  :---     |
| No | Least Privilige | The employees have access to customer data. This has to be changed to reduce the risk of breach. |
| No | Disaster Recovery Plan | At this time there is no plans in place for handling a disaster, Implementing one ensures the buisness continuity. |
| No | Password Policies | a password policy exists, however the requirements are considered weak and puts Identity management access at risk. |
| Yes | Storefront | Although IT team is not responsible for the management at the storefront, the organization should have sufficient locks.|
| No | Seperation of Duties | Needs to be Implemented to reduce the possibility of fraud/access to critical data, the Companies CEO currently runs the daily operations of the company as well as payroll. |
| Yes | Firewall | The companies firewall is configured properly with the appropriate security rules, which blocks traffic accordingly. |
| Yes | Antivirus | The antivirus software is active and regulary monitored by IT team. |
| No | Backups | This should be part of the disaster recovery plan. They are not prepared in the case of breach to occure.|
| No | Encryption | This would improve the ability to protect the confidentiality of data. |
| No | Intrusion Detection System (IDS) | This would help IT team to identiy possible intrusions by the threat actors. | 
| Yes | CCTV | It is working and functioning. |
| Yes | Fire detection | physical location has a functioning fire detection and prevention system. However, the team should maintain it and establish a plan on how to use it. |


## Compliance Checklist
Does Botium Toys currenly adhrere to this compliance best practice? 

# Payment Card Industry Data Security Standard (PCI DSS)

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | Only Authorized users she be able to access to customer's credit card. | at this time all employees in the company have access to the information which is way too many people and has a higher possibility of information getting leaked accidently or intentionally.  |
| No | Credit card information should stored in a secure location. | It is currenly not encrypted and which violates the law and regulations as well as makes the system way less secure and easier for threat actors to steal the information. |
| No | Encryption is secured. | No, there is no encryption in place this needs to be changed when dealing with highly sensitive information. | 


# General Data Protection Regulation (GDPR)
  
| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | EU customers are kept secured. | The organization does not apply GDPR practice. Thus, it puts them at risk of being fined by the EU government. |
| Yes | Privacy policies are maintained properly.| According to the scenario, it has been enforced by the IT Team members and other staff. |


# System and Organizations Controls 

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | User access policies are established | Employees have access to internally stored data which means the access policy has not been applied. |
| Yes | Data integrity is consistent, complete, accurate | Data integrity is in place. | 
| No | Data is available to authorized users | Currently, all the employees can access all the data. |


## Recommendations (optional)
In this section, provide recommendations, related to controls and/or compliance needs, that your IT manager could communicate to stakeholders to reduce risks to assets and improve Botium Toys’ security posture.
There are several potential risk issues in the current audit results. I recommend getting fixed as quickly as possible to avoid any potential harm or legal issues in the future. 

1. I recommend is to make sure all data and information is classified and stored properly and then establish a principle of Least Privilege system within the organization as not everyone in the company needs to have access to the Internally stored data or need to be able to access to cardholder data and/or customers PII/SPII information. Only those who have been specifically hired to work with that information should have the privileges needed to do their job and nothing more, to help prevent any exploits threat actors could use to gain access to any private information or accidental leakage of the information as well.

2. Establishing both a stronger Password Policy as the current one is too weak and is an easy target for a Threat Actor to take advantage of but I also recommend establishing a password management system to have more control of which users have access to the systems, It also grants the ability to quickly disable a user if the employee is either fired, quits their job from the company or even goes away on holidays, sealing up any holes quickly so threat actors cannot use the account as a method of accessing the system while the user is away.

3. Establishing an encryption system to better ensure the safety and confidentiality of customers credit card information, as well as install an Intrusion Detection System to help monitor and catch any unauthorized use of the customer's credit cards as well. It will also help the company to be much more compliant to the General Data Protection Regulations act (GDPR) as well to help satisfy PCI DSS regulations.

4. The final change I recommend is improving the way the Legacy systems are being monitored and maintained by establishing a regular schedule to perform the required tasks and interventions as well as making the methods much clearer and easier to follow for anyone who is currently assigned to the role and for future hires, including backing up the systems. There should be 2 different backups in place one scheduled to be done once a week and another back up to be done once a month and kept in a safe and secure storage location so that if a security incident happens once the issues have been resolved, the security teams can recover after the incident by rolling back the company system back to a date prior to the incident to hopefully help mitigate how much damage is done and how much of the companies assests are lost allowing the company to get back up to proper functioning form as quickly as possible.



