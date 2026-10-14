# Cybersecurity-Project
# Netwise — Cybersecurity Assessment and AI Investigation Platform

<h1><a href="https://github.com/prsilvaa/Cybersecurity-Project">Cybersecurity Assessment Tool</a></h1>

<h2>Project Objective</h2>

<p>Develop a Python-based cybersecurity assessment platform that helps users investigate network security and identify potential weaknesses in their devices. The system combines network scanning, operating system information gathering, firewall and antivirus checks, and automated risk assessment to produce structured security reports.</p>

<h2>Tools and Technologies Used</h2>

<ul>
    <li><strong>Python</strong> – Implements the security checks, risk assessment logic, reporting functions, and investigation workflow.</li>
    <li><strong>Flask</strong> – Provides the backend server and API endpoints connecting the website to the security tools.</li>
    <li><strong>FastAPI</strong> – Used in the previous backend implementation for API-based security checks.</li>
    <li><strong>Network Scanning Tools</strong> – Collect network information for security analysis and investigation.</li>
    <li><strong>Operating System Security Checks</strong> – Collect operating system details and check firewall and antivirus status.</li>
    <li><strong>External Security APIs</strong> – Support additional security checks through authorised third-party services.</li>
    <li><strong>JSON</strong> – Transfers structured scan results between the backend and website.</li>
    <li><strong>AI Integration (Planned)</strong> – Analyses scan findings, explains risks, and recommends appropriate follow-up investigations.</li>
</ul>

<h2>Key Features</h2>

<ul>
    <li><strong>Network Assessment</strong> – Executes network scanning functions through the backend API.</li>
    <li><strong>Device Security Assessment</strong> – Identifies the operating system and checks firewall and antivirus status where supported.</li>
    <li><strong>Automated Risk Classification</strong> – Assigns Low, Medium, or High risk based on predefined security rules.</li>
    <li><strong>Security Report Generation</strong> – Produces readable reports containing findings and general recommendations.</li>
    <li><strong>API Integration</strong> – Connects the website to Python security tools and external services.</li>
    <li><strong>AI-Assisted Analysis (Planned)</strong> – Interprets collected evidence and provides contextual explanations and recommendations.</li>
    <li><strong>Agent-Based Investigation (Future Development)</strong> – Selects appropriate approved tools, evaluates results, and determines whether additional checks are necessary.</li>
</ul>

<h2>Skills Gained</h2>

<ul>
    <li>Python programming and automation</li>
    <li>Backend development and API integration</li>
    <li>Network security assessment</li>
    <li>Operating system security analysis</li>
    <li>Vulnerability assessment and risk classification</li>
    <li>Security report generation</li>
    <li>Exception handling and debugging</li>
    <li>AI-assisted cybersecurity investigation design</li>
    <li>Security testing and responsible tool execution</li>
</ul>

<h2>Project Outcome</h2>

<p>The current implementation provides a foundation for automated cybersecurity assessment. The Flask backend connects the website to network scanning and device vulnerability assessment functions. The device assessment collects operating system information, checks firewall and antivirus status, calculates a rule-based risk level, and generates a readable report.</p>

<p>The next development stage will introduce AI-assisted interpretation of security findings. This component will aim to explain identified weaknesses, prioritise further investigation, and recommend evidence-based remediation steps. Further development will explore agent-based workflows in which the system can select approved security tools and evaluate their results, subject to appropriate authorisation and safety controls.</p>

<h2>Future Development</h2>

<ul>
    <li>Integrate an AI model for contextual analysis of security findings.</li>
    <li>Develop a structured investigation workflow that connects scan results with follow-up checks.</li>
    <li>Improve risk scoring using evidence, severity, and confidence rather than firewall and antivirus status alone.</li>
    <li>Add input validation, authentication, and authorisation for scanning endpoints.</li>
    <li>Improve support for Windows, macOS, and Linux security checks.</li>
    <li>Test the accuracy of findings and recommendations in an authorised lab environment.</li>
    <li>Evaluate the system's usefulness as an AI-assisted cybersecurity investigation agent.</li>
</ul>

<h2>Ethical and Responsible Use</h2>

<p>Netwise is intended for authorised security assessments and educational cybersecurity investigations. Network scanning and follow-up checks must be restricted to approved devices and networks. AI-generated findings and recommendations will require verification before being treated as confirmed security conclusions.</p>

<h2>Project Status</h2>

<p><strong>In development.</strong> Automated security checks, backend API routes, rule-based risk classification, and report generation have been implemented. AI-assisted analysis and autonomous investigation capabilities are planned extensions and should not be considered completed features until implemented and tested.</p>
