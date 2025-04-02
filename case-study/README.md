<h1>
  <span class="headline">Security Controls</span>
  <span class="subhead">Case Study: The SolarWinds Supply Chain Attack</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to analyze a real-world security breach through the CIA Triad lens to identify critical control failures.

## Case Study: The SolarWinds Supply Chain Attack

### Background

In December 2020, one of the most sophisticated supply chain attacks in cybersecurity history was discovered. Attackers compromised the software build system of SolarWinds, a major IT management software provider, inserting malicious code into legitimate software updates.

The attack, attributed to a Russian intelligence-linked group known as Cozy Bear (APT29), affected up to 18,000 SolarWinds customers, including multiple U.S. government agencies and Fortune 500 companies.
Attack Timeline

1. **Initial Compromise (Sept 2019):** Attackers gained access to SolarWinds' development environment

2. **Code Injection (Oct 2019 - Feb 2020):** Attackers inserted malicious code into the Orion software build process

3. **Distribution (March 2020):** SolarWinds unknowingly distributed malicious updates to customers

4. **Dormancy Period:** Malware remained dormant for up to two weeks before activating

5. **Command & Control:** Attackers established communication with compromised networks

6. **Lateral Movement:** Attackers moved through networks, establishing persistence and stealing data

7. **Discovery (Dec 2020):** FireEye discovered the breach while investigating their own security incident

## CIA Triad Analysis

Let's analyze how the SolarWinds attack impacted each element of the CIA Triad:

- **Confidentiality Breach**

  - Attackers gained unauthorized access to sensitive government information
  - Client data was potentially exposed
  - Internal communications and intellectual property were compromised

- **Integrity Breach**

  - Legitimate software was modified to include malicious code
  - Trusted update mechanisms were subverted
  - Systems operated in ways contrary to their intended function

- **Availability Impact**

  - While not the primary focus of the attack, remediation efforts required system downtime
  - Organizations had to disconnect affected systems during investigation
  - Security teams were diverted from normal operations to incident response

### Key Vulnerabilities

1. **Inadequate Supply Chain Security**

- Failure to secure the software build environment
- Insufficient code signing verification processes

2. **Detection Failures**

- Malicious code remained undetected for months
- Sophisticated techniques to evade security tools

3. **Trust Relationship Exploitation**

- Exploited implicit trust in vendor software updates
- Used legitimate communication channels for malicious purposes

***Discussion Question:*** What controls might have prevented or detected this attack earlier? Take a minute to brainstorm before continuing.
