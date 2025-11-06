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

<p><img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Ping Failure"/></p>
<p>Initial ping attempts failed due to missing DNS records.</p>

<p><img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="nslookup Diagnostics"/></p>
<p>Used <code>nslookup</code> to confirm DNS record absence.</p>

<p><img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Fixed DNS Records"/></p>
<p>After record updates, DNS resolution succeeded across the domain.</p>
