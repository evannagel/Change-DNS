# Change DNS to Google Public DNS

This guide shows how to switch your DNS to **Google Public DNS (8.8.8.8 / 8.8.4.4)**  
for faster and more reliable connections.

---

## 🪟 Windows

1. Click the **Start** menu → type **Control Panel** → open it.  
2. Go to **Network and Internet → Network and Sharing Center**.  
3. On the left, click **Change adapter settings**.  
4. Right-click your active connection → **Properties**.  
5. Select **Internet Protocol Version 4 (TCP/IPv4)** → **Properties**.  
6. Choose **Use the following DNS server addresses** and enter:

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Change DNS to Google DNS on Windows 10</title>
  <style>
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, Arial; max-width:900px; margin:40px auto; line-height:1.5; padding:0 20px; }
    h1 { font-size:1.6rem; }
    .step { margin-bottom:28px; }
    img { display:block; max-width:100%; height:auto; border:1px solid #ddd; margin-top:8px; }
    code { background:#f5f5f5; padding:2px 6px; border-radius:4px; }
    footer { margin-top:40px; color:#666; font-size:0.9rem; }
  </style>
</head>
<body>
  <h1>Change DNS to Google DNS on Windows 10</h1>

  <div class="step">
    <strong>Step 1</strong>
    <div>Click the Start menu → type <code>Control Panel</code> → open it.</div>
    <img src="assets/image-1.png" alt="Open Control Panel (Windows 10)" />
  </div>

  <div class="step">
    <strong>Step 2</strong>
    <div>Click <em>Network and Internet</em> → <em>Network and Sharing Center</em>.</div>
    <img src="assets/image-2.png" alt="Network and Internet (Windows 10)" />
  </div>

  <div class="step">
    <strong>Step 3</strong>
    <div>On the left, click <em>Change adapter settings</em>. Then right-click your active adapter and choose <em>Status</em> or <em>Properties</em>.</div>
    <img src="assets/image-3.png" alt="Network and Sharing Center showing active connection" />
  </div>

  <div class="step">
    <strong>Step 4</strong>
    <div>Open the connection <em>Status</em> (or <em>Properties</em>) for your active adapter to view details like SSID, speed, and signal quality.</div>
    <img src="assets/image-4.png" alt="Wi-Fi Status dialog (connection details)" />
  </div>

  <div class="step">
    <strong>Step 5</strong>
    <div>In the adapter <em>Properties</em> window, find and select <em>Internet Protocol Version 4 (TCP/IPv4)</em>, then click <em>Properties</em>.</div>
    <img src="assets/image-5.png" alt="Wi-Fi Properties window showing IPv4 item" />
  </div>

  <div class="step">
    <strong>Step 6</strong>
    <div>In the <em>Internet Protocol Version 4 (TCP/IPv4) Properties</em> dialog, select <em>Use the following DNS server addresses</em> and enter:</div>
    <ul>
      <li>Preferred: <code>8.8.8.8</code></li>
      <li>Alternate: <code>8.8.4.4</code></li>
    </ul>
    <img src="assets/image-6.png" alt="IPv4 Properties dialog with Google DNS entered" />
    <p>Click <em>OK</em>, then close the remaining dialogs — you're done.</p>
  </div>

  <footer>
    Place your screenshots in the <code>assets/</code> folder and name them <code>image-1.png</code> … <code>image-6.png</code>, or edit this file to match your filenames.
  </footer>
</body>
</html>
