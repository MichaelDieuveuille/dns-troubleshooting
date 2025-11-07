<h1>Troubleshooting DNS with nslookup and ping</h1>

<h2>Overview</h2>
<p>Tested and resolved DNS resolution issues by using <code>nslookup</code> and <code>ping</code> to diagnose misconfigured or missing DNS entries.</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (VMs)</li>
  <li>Windows Server DNS</li>
  <li>Command-line tools (<code>nslookup</code>, <code>ping</code>)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows Server 2019/2022</li>
  <li>Windows 10 (client)</li>
</ul>

<h2>High-Level Steps</h2>
<ol>
  <li>Attempted hostname resolution to observe initial failures.</li>
  <li>Used <code>nslookup</code> to find incorrect or missing records.</li>
  <li>Updated DNS Manager entries.</li>
  <li>Re-tested and verified resolution and connectivity.</li>
</ol>

<h2>Actions and Observations</h2>

<img width="2559" height="766" alt="Screenshot 2025-11-07 113643" src="https://github.com/user-attachments/assets/ef9deaf1-4d21-45ed-aa15-c6fd6e093b4a" />

<p>Initial ping attempts failed due to missing DNS records.</p>

<img width="2559" height="1199" alt="Screenshot 2025-11-07 113835" src="https://github.com/user-attachments/assets/6808e5f0-d45a-4c61-bbf2-a7faf60be87f" />

<p>Used <code>nslookup</code> to confirm DNS record absence.</p>

<img width="2559" height="1264" alt="Screenshot 2025-11-07 114103" src="https://github.com/user-attachments/assets/31ed0990-b6ab-4959-bc58-956990b4c404" />

<p>After record updates, DNS resolution succeeded across the domain.</p>
