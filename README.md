# Exabeam_TDIR_Training

# Exabeam TDIR for Security Analysts (EDU-2170

## Table of contents

1. [Introduction for Advanced Analytics](#introduction1)
    1. [Slides](#slides)
    2. [All Links](#alllinks)
    3. [Key Takeaways](#keytakeaways)
    4. [Types of Attacks](#subparagraph4)

2. [Module 2: Threat Detection with Behavior Analytics](#threatdetection)
    1. [How User Entity Behavioral Analytics (UEBA) Works](#ueba)
    2. [Lab](#module2lab)
    3. [XDR](#xdr)

3. [Module 3: How data Ingestion and Enrichment works in AA](#module3)

33.  Search, Dashboards, and Correlation Rules - EDU-2201 

## Table of contents

1. [Introduction for Search, Dashboards, Rules](#introduction2)

    1. [Slides](#slides)

 


# Introduction Data Lake for Security Analysts <a name="introduction1"></a>

Purpose of the Course: 
- Help analysts use daily the Exabeam Security Operations Platform to detect, investigate, and respond to threats with rapid time to value, out-of-the-box integration, and pre-tuned detection mechanisms

1. Recall how Exabeam empowers security teams:
- Rapid time to value
- Out-of-the-box integration
- Pre-tuned detection mechanisms

![ LINK: Day In a Life](./assets/day-in-a-life.png)

## Lab Setup
[ LINK: Customer Login](https://customer.exabeamtraining.com/)
- My Profile
- Click on Class currently Enrolled in 
- All Slides/Labs will be there

## Slides <a name="slides"></a> 

[ LINK: Day 1 Slides](./assets/Day1-2170-Student-v4.pdf)

[ LINK: Day 2 Slides](./assets/Day2-2170-Student-v4.pdf)

[ LINK: Day 3 Slides](./assets/Day3-2170-Student-v4.pdf)


## Links <a name="alllinks"></a>


[ LINK: Library - Amazing Sources - Discover more about the Exabeam platform, learn about the latest in SecOps, and find resources to help mature your SOC. Browse by content type or explore our featured picks below.](https://www.exabeam.com/library/)

[ LINK: Customer Login](https://customer.exabeamtraining.com/)

[ LINK: All Documentation](https://docs.exabeam.com/)

[ LINK: Advanced Analytics User Guide](https://docs.exabeam.com/cloud-delivered-advanced-analytics)

[ LINK: Office Hours](https://community.exabeam.com/s/article/Exabeam-SaaS-Cloud-Office-Hours)

[ LINK: Virtual Instructor Led Training](https://customer.exabeamtraining.com/page/instructor-led-training)

[ LINK: Digital Learning](https://customer.exabeamtraining.com/page/digital-learning)

[ LINK: Exabeam CTF](https://customer.exabeamtraining.com/exabeam-capture-the-flag)

[ LINK: Mitre Systems Engineering](https://www.mitre.org/our-impact/mitre-labs/systems-engineering-innovation-center)

[ LINK: Elimate Alert Fatigue](https://alertops.com/eliminate-alert-fatigue/)

[ LINK: What is XDR](https://www.exabeam.com/information-security/what-is-xdr-transforming-threat-detection-and-response/)

## Key Takeaways <a name="keytakeaways"></a>

### Takeaway #1 - Adop a Use Case Methodology 
![#1](./assets/keytakeaway-1.png)

### Takeaway #2 - Known How Behavior Analytics Work

![#2](./assets/keytakeaway-2.png)
![#2](./assets/keytakeaway-2-2.png)

### Key Takeaway #3: Utilize the Exabeam Security Operations Platform for Investigation and Response Workflows


![#3](./assets/keytakeaway-3.png)

 


## Types of Attacks <a name="attacktypes"></a>

- Insider Threat
  - An exisitng employee or contractor exploits thier access for malicoius purposes 

- Lateral/Parallel Movement

- Compromised Insider
  - Credentials exploited by someone outside the organization for the purpose of data theft and/or sabotage


## Module 2 Threat Detection with Behavior Analytics <a name="threatdetection"></a> 

**1. Security Alerts**

  - Security Alerts have many ways of being noticed – directly through consoles and notifications or indirectly through a SIEM or a tool like Exabeam Alert Triage
  - 3rd party products issues theirn own alerts 

**2. Fact-Based Rules**

  - Conditional logic applied to log data in Advanced Analytics that identifies patterns associated with unwanted or risky activity
  - Fact-based rules are often referred to as correlation rules in a traditional SIEM. Fact-based rules are
applied to unwanted activities, risky activities, or even undesired activities, but not necessarily limited
to malicious events or behavior.

**3. Behavior Analytics**

  - Machine learning applied to data that generates risk scores based on anomalies
  
  - Behavior Analytics is a unique way of detecting threats because it does not look for a specific recognizable process or pattern – rather it relies on data modeling to determine normal activity and then triggers anomalies and assigns risk based on these deviations from normal.

### Alert Fatigue = Risk

- Some tools generate more alerts than others (e.g., DLP)
 
- Analysts can be overwhelmed by alerts and affected by bias

- Missed alerts and false positives cost organizations time and money

- When asked to identify their top incident response challenges, 36% of the cybersecurity professionals
surveyed said, “keeping up with the volume of security alerts.”

- 42% of cybersecurity professionals say that their organization ignores a significant number of security
alerts because they can’t keep up with the volume.

- When asked to estimate the percentage of security alerts ignored at their organization, 34% say
between 26% and 50%, 20% of cybersecurity professionals say their organization ignores between 50%
and 75% of security alerts, and 11% say their organization ignores more than 75% of security alerts. Mama Mia, that’s a lot of security alerts left on the cutting room floor.

### How Anomalies Help SOCs

- Adding anomaly detection improves visibility and alert fidelity
- Combining anomaly detection with security alerts focuses analyst effort

- Anomaly detection improves detection and increases alert fidelity by showing risky behavior in and around
events. Context and meaning are added to third party alerts and focuses analysts allowing them to make
critical security decisions.


### How User Entity Behavioral Analytics (UEBA) Works <a name="ueba"></a>

- UEBA solutions are based on a concept called baselining. They build profiles that model standard behavior for users, hosts, and devices (called entities) in an IT environment.

- Using primarily machine learning techniques, they identify activity that is anomalous, compared to the established baselines, and detect security incidents. The primary advantage of UEBA over traditional security solutions is that it can detect unknown or elusive threats, such as zero-day attacks and insider threats. In addition, UEBA reduces the number of false positives because it adapts and learns actual system behavior, rather than relying on predetermined rules which may not be relevant in the current context.

#### Another term that is sometimes used in conjunction with UEBA is next-generation SIEM. In Gartner’s vision of a nextgeneration SIEM solution, a SIEM should include built-in UEBA functionality. The report lists the following as critical capabilities of a modern SIEM:
- User monitoring, including baselining and advanced analytics to analyze access and authentication data, establish
user context, and report on suspicious behavior.
-  Advanced analytics – applying sophisticated statistical and quantitative models, such as machine learning and deep learning, on security log and event data to detect anomalous activity. Advanced analytics should complement the traditional rule and correlation-based analytics available in traditional SIEMs. 

#### Advanced analytics, which is the hallmark of UEBA tools, involves several modern technologies that can help identify abnormal behavior even in the absence of known patterns:
-  Supervised machine learning – sets of known good behavior and known bad behavior are fed into the system. The tool learns to analyze new behavior and determine if it is “similar to” the known good or known bad behavior set.
- Bayesian networks – can combine supervised machine learning and rules to create behavioral profiles.
- Unsupervised learning – the system learns normal behavior and is able to detect and alert on abnormal behavior. It
will not be able to tell if the abnormal behavior is good or bad, only that it deviates from normal.
- Reinforced / semi-supervised machine learning – a hybrid model where the basis is unsupervised learning, and actual alert resolutions are fed back into the system to allow fine tuning of the model and reduce the signal-tonoise ratio. 
- Deep learning – enables virtual alert triage and investigation. The system trains on data sets representing security alerts and their triage outcomes, performs self-identification of features, and is able to predict triage outcomes for new sets of security alerts.


### Module 2 Lab <a name="module2lab"></a>

[ LINK: Lab Login](https://classroom9-aa.exalabs.io/)

![ LINK: Lab Dashboard](./assets/module2-lab1.png)

![ LINK: Lab Dashboard](./assets/module2-lab2.png)


### What is XDR eXtended Detection and Response <a name="xdr"></a>

- What is a native XDR?
  - A native XDR is a closed ecosystem that offers both the front-end solutions that generate data as well as the back-end capabilities of analysis and workflow. To be a native XDR solution, a vendor should ideally offer all required sensors needed for common XDR use cases, typically endpoint, network, cloud, identity, email, etc. as well as a back end capable of performing threat detection, investigation, and response with that data. Native XDR vendors can be EDR vendors who are expanding their portfolio to include more sensors and back-end capabilities such as efficient advanced analytics, or they can be platform vendors which have a wide portfolio of security tools that they are trying to more tightly integrate to provide XDR-like functionalities.
- What is an open XDR?
  - Alternatively, open XDR vendors offer a solution that is predominantly focused on the back-end analytics and workflow engine. Leading open XDR vendors also add prescriptive content required across all the phases and the full lifecycle of threat detection, investigation and response (TDIR) to easily solve common SOC use cases out of the box. - Open XDRs need to integrate with all of an organization’s existing security and IT infrastructure, then correlate and analyze all relevant data, and finally automate and optimize TDIR workflows, making it easier for SOC teams to respond to incidents quicker. As security stacks have grown more complex and disjointed in organizations, open XDRs act as a single control plane across multiple products and vendors. This provides visibility and allows orchestration and automation of actions (similar to SIEM and SOAR functionality) so that SOC teams don’t have to run manual workflows across a myriad of tools.

- Exabeam’s take on XDR
  - We believe the open XDR approach best positions most security teams for success and reduces their cybersecurity risks. While the native approach may, in theory, offer the major pieces of a security program and the simplicity of a single vendor, we believe this will inevitably lead to vendor lock-in and a lack of depth and breadth of coverage for organizations. Security teams will find it difficult to get best-in-class capabilities across email, DLP, identity, cloud all from a single vendor.
In addition, organizations selecting a native XDR may find it very difficult to add a security tool from another vendor that covers a new attack vector or more advanced threats. Because native XDRs are usually focused on their own portfolio, little to no capabilities and support exist to efficiently integrate with sensors from other infosec tools. The flexibility offered by an open XDR allows security teams to keep existing investments in best-of-breed security tools while allowing desired changes to their tech stack. Open XDRs are made to integrate with other products — so they can comprehensi 

- XDR is a set of technologies that can help security teams perform more effective threat detection, as well as rapid investigation and response.
- Unlike previous-generation security solutions, XDR is not limited to one security silo — it combines data from networks, endpoints, email, IoT devices, servers, cloud workloads, and identity systems. It combines data from all layers of the IT environment, and enriches them with threat intelligence, to detect sophisticated and evasive threats.
- A primary value of XDR is that it provides prepackaged, automated threat detection, investigation and
response (TDIR) for a variety of threats. XDR solutions are cloud delivered, suited for distributed,
heterogeneous IT environments. They are turn-key solutions that immediately provide value and improve
productivity for security teams.

- XDR is typically made up of three major feature sets: front end, back end and content. The front end consists of the “sensors” that generate security telemetry data, like CASBs, EDRs, IAM, DLP solutions, and others. The back end ingests all the collected telemetry data, logs and context information, then conducts all the data correlation, advanced analytics, threat detection, investigation, tool orchestration, and response automation.
- The third critical component of any successful XDR is content. XDRs should be able to offer a closed-loop
solution that encompasses the entire security operations workflows of threats. XDRs are supposed to be
turnkey solutions with immediate time to value and minimum/no configuration, regardless of the expertise
level of the SOC — so instead of tuning, SOCs should be able to use XDRs to address immediate concerns
from start to finish. By this, we mean focusing on one use case and expanding from thereafter each one is
addressed. Without this capability, XDRs will not be able to fulfill their value prop: turn-key TDIR that works immediately, without customization.
- Without prescriptive, prepackaged content that ties these pieces together around specific use cases, it’s
impossible to achieve the value props of simplicity, automation, and successful outcomes that XDR promises.

![ LINK: XDR Examples](./assets/xdr-examples.png)


## Module 3 How Data Ingestion and Enrichment Works in AA <a name='module3'></a>








<table>
   <thead>
      <tr>
         <th>Attack Name</th>
         <th>Details</th>
         <th>Notes</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>Insider Threat</td>
         <td>df </td>
         <td>data3</td>
      </tr>
      <tr>
         <td>d</td>
         <td>data12</td>
         <td>data13</td>
      </tr>
   </tbody>
</table>


#  Search, Dashboards, and Correlation Rules - EDU-2201 