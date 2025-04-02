<h1>
  <span class="headline">Security Controls</span>
  <span class="subhead">Control Category Breakdown</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to distinguish between the four main categories of security controls and identify when each should be applied.

Security controls can be divided into four categories based on their implementation method.

Let's explore each with examples of how they could have potentially helped in the SolarWinds case.

1. **Managerial (Administrative) Controls**
These are the policies, procedures, and guidelines that govern your security program.

   - ***Examples***

     - Security policies and standards
     - Risk assessments and audits
     - Security awareness training
     - Vendor management procedures
     - Incident response plans

   - **SolarWinds Application:**

     - Enhanced vendor security assessment processes
     - More rigorous software development security policies
     - Better third-party code review requirements

2. **Operational Controls**
These controls focus on the day-to-day operations and are typically executed by people.

   - ***Examples:***

     - Security monitoring
     - Configuration management
     - Change management procedures
     - Vulnerability management
     - Incident handling

   - **SolarWinds Application:**

     - Enhanced code review processes for critical systems
     - More frequent security reviews of build systems
     - Improved monitoring of privileged operations
     - Separation of duties in the development pipeline

3. **Technical Controls**
These are the technological solutions implemented to protect systems and data.

   - ***Examples:***

     - Authentication systems
     - Firewalls and IDS/IPS
     - Encryption
     - Access control systems
     - Anti-malware solutions

   - **SolarWinds Application:**

     - Code signing with hardware security modules
     - Runtime application self-protection (RASP)
     - Enhanced network monitoring for unusual connections
     - Multi-factor authentication for build system access

4. **Physical Controls**
These focus on securing the physical environment where information systems operate.

   - ***Examples:***

     - Secure data centers
     - Badge access systems
     - CCTV surveillance
     - Biometric authentication
     - Environmental controls

   - **SolarWinds Application:**

     - Physical access restrictions to build environment systems
     - Secured development environments
     - Hardware security modules for cryptographic operations
     - Air-gapped systems for critical code signing

### Control Categories in Practice

Most effective security programs employ a mix of all four categories to create defense in depth. Here's how they work together:

Policy (Managerial) → Process (Operational) → Implementation (Technical & Physical)

For example, a data protection strategy might include:

- Data classification policy (Managerial)
- Training on handling sensitive data (Operational)
- Encryption of sensitive data (Technical)
- Secured server rooms (Physical)

Never rely on just one category of controls. Each provides different layers of protection that complement each other. Defense in depth is key!
