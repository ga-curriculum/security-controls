<h1>
  <span class="headline">Security Controls</span>
  <span class="subhead">Control Functions in Action</span>
</h1>

**Learning objective:** Apply knowledge of preventive, detective, and corrective controls to create a complete security lifecycle.

Beyond categories, controls can be classified by their function in your security ecosystem:

1. **Preventive Controls**
These controls aim to stop incidents before they occur.

   - *Examples:*

     - Firewalls blocking unauthorized traffic
     - Input validation preventing SQL injection
     - Access controls limiting system access
     - Security awareness training
     - Data encryption

**Function:** They create barriers that attackers must overcome.

2. **Detective Controls**
These controls identify when something has gone wrong.

   - *Examples:*

     - Intrusion detection systems
     - Log monitoring and analysis
     - File integrity monitoring
     - Security audits
     - Honeypots

**Function:** They provide visibility into security events and potential breaches.

3. **Corrective Controls**
These controls remediate problems after they've been identified.

   - *Examples:*

     - Incident response procedures
     - Disaster recovery plans
     - Patch management
     - System restoration
     - Virus quarantine and cleanup

**Function:** They minimize damage and restore normal operations.

4. **Compensating Controls**
These are alternative controls used when primary controls cannot be implemented.

   - *Examples:*

     - Additional logging when encryption isn't possible
     - Manual approvals when automated workflows aren't available
     - Enhanced monitoring when patching is delayed

**Function:** They provide alternative security measures when preferred controls aren't feasible.

### The Security Control Lifecycle

These functions work together in a continuous cycle:

Prevent → Detect → Correct → Improve Prevention → ...

Let's see how this might work for protecting a web application:

- **Preventive:** Web Application Firewall blocks suspicious traffic patterns
- **Detective:** Log analysis identifies a new attack pattern that bypassed the WAF
- **Corrective:** Incident response team contains the breach and patches the vulnerability
- **Improvement:** WAF rules are updated to catch the new attack pattern

### Applying Control Functions to the SolarWinds Case

If we wanted to better protect against a similar supply chain attack:

**Preventive Controls:**

- Isolated build environments
- Stricter code signing procedures
- Mandatory code reviews

**Detective Controls:**

- Build process integrity monitoring
- Network behavior analysis
- Anomaly detection in privileged access

**Corrective Controls:**

- Incident response playbooks for supply chain attacks
- Segmented network design to limit lateral movement
- ßRecovery procedures for compromised systems
