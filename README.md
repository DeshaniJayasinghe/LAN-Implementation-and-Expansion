<h1 align="center"> LAN Implementation and Expansion Project </h1>

<p align="center">
  <img src="https://img.shields.io/badge/Course-CTEC%2022061-blue" alt="Course Code">
  <img src="https://img.shields.io/badge/Semester-2nd%20Year%202nd%20Sem-orange" alt="Semester">
  <img src="https://img.shields.io/badge/Tools-Cisco%20Packet%20Tracer-green" alt="Tools">
</p>

<hr>

<h3>📝 Project Overview</h3>
<p>
  This project focuses on <b>Implementing and Expanding Local Area Networks (LANs)</b>. Developed as part of the <b>CTEC 22061: Data Communication and Networking II</b> course, it demonstrates advanced networking concepts including VLAN segmentation, Inter-VLAN routing, and the integration of specialized services like <b>VoIP</b> and <b>IoT</b>.
</p>

<div align="center">
  <img width="1478" alt="Project Topology" src="https://github.com/user-attachments/assets/your-image-link-here" />
</div>

<h3>🚀 Key Features</h3>
<ul>
  <li><b>VLAN Segmentation:</b> Organized network traffic into functional groups (Voice, Data, IoT) for enhanced security and efficiency.</li>
  <li><b>Inter-VLAN Routing:</b> Configured Router-on-a-Stick and Layer 3 switching to allow communication between different subnets.</li>
  <li><b>Dynamic Addressing:</b> Implemented <b>DHCP pools</b> for automatic IP assignment across the network.</li>
  <li><b>VoIP Integration:</b> Configured Cisco IP Phones and Softphones (IP Communicator) with custom directory numbers and TFTP services.</li>
  <li><b>IoT Management:</b> Integrated smart devices (Fan, AC, Light) controlled via a central gateway/server.</li>
</ul>

<h3>🛠️ Tech Stack & Networking Protocols</h3>
<p>
  <img src="https://img.shields.io/badge/Cisco_Packet_Tracer-005FB8?style=for-the-badge&logo=cisco&logoColor=white" alt="Packet Tracer">
  <img src="https://img.shields.io/badge/Networking-DHCP%20%7C%20VLAN%20%7C%20VoIP-lightgrey?style=for-the-badge" alt="Networking">
</p>

<h3>⚙️ Implementation Details</h3>

<h4>1. Network Topology</h4>
<p>The network consists of multiple subnets, including a main server farm, office workstations, and a wireless IoT zone. A core router serves as the <b>Default Gateway (208.67.220.250)</b>.</p>

<h4>2. VoIP Configuration</h4>
<p>Telephony services were configured on the Cisco router to handle registration for:</p>
<ul>
  <li>IP Phones (DN 1001-1002)</li>
  <li>Smartphones (DN 1003)</li>
  <li>Laptop Softphones (DN 1004)</li>
</ul>

<h4>3. IoT Ecosystem</h4>
<p>Devices like Humidity Monitors and Garage Doors are linked via a Wireless Access Point, enabling remote monitoring and automation within the LAN environment.</p>

<h3>📂 Project Files</h3>
<p>This repository includes the following resources:</p>

<div align="left">
  <table>
    <tr>
      <td><b>File Name</b></td>
      <td><b>Description</b></td>
    </tr>
    <tr>
      <td><code>CT2022_067 -Expanding LANs.pkt</code></td>
      <td>Source Cisco Packet Tracer File</td>
    </tr>
    <tr>
      <td><code>CTECT 22061 - Day2Lab - ImplementingLANs.pdf</code></td>
      <td>Phase 1 Lab Guidelines</td>
    </tr>
    <tr>
      <td><code>CTECT 22061 -Day2Lab_Part ii - Expanding LANs.pdf</code></td>
      <td>Phase 2 Expansion Guidelines</td>
    </tr>
  </table>
</div>

<br>
<blockquote style="background-color: #f9f9f9; border-left: 5px solid #ccc; padding: 10px;">
  <b>Academic Integrity:</b> This project is part of an undergraduate laboratory series at the <b>University of Kelaniya</b> to demonstrate proficiency in enterprise-grade network design and troubleshooting.
</blockquote>
