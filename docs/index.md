# Getting Started

<div style="position: relative; display: flex; justify-content: center;">
  <video autoplay loop muted playsinline width="600" style="z-index: 1;">
    <source src="videos/shaker2.mp4" type="video/mp4">
    Your browser does not support HTML5 video.
  </video>

  <!-- Viñeta overlay -->
  <div style="
    position: absolute;
    width: 600px;
    height: 102%;
    pointer-events: none;
    z-index: 2;
    background: radial-gradient(circle, rgba(0, 0, 0, 0) 50%, rgb(0, 0, 0) 100%);
  "></div>
</div>

<div style="text-align: center;">
    <span style="color: rgb(255, 255, 255);">
        You now own the most portable and affordable seismic table on the market!🚀 <br>
        <span style="color: rgb(255, 134, 35);">
            Now on pre-sale: <strong style="color: rgb(105, 255, 35);">USD $299.9</strong> <span style="text-decoration: line-through; color: rgb(255, 94, 94);">USD $500</span><br>
        </span>
    </span>
</div>

<div style="display: flex; flex-direction: row; align-items: stretch; justify-content: center; gap: 1rem; width: 100%; height: 1rem;">
    <a href="https://api.whatsapp.com/send?phone=573167164222&text=Hi!%20%0AI%20need%20help%20with%20my%20P-Shaker%20purchase" style="background-color: rgba(35, 255, 64, 0.68); color: white; text-decoration: none; font-weight: bold; border-radius: 0.9rem; width: 5rem; height: 100%; display: flex; align-items: center; justify-content: center;">
        WhatsApp
    </a>
    <a href="https://api.whatsapp.com/send?phone=573167164222&text=Hi!%20%0AI%20need%20help%20with%20my%20P-Shaker%20purchase" style="background-color: rgb(255, 152, 35); color: white; text-decoration: none; font-weight: bold; border-radius: 0.9rem; width: 5rem; height: 100%; display: flex; align-items: center; justify-content: center;">
        Need help?
    </a>
        <a class="doc-button" href="mailto:epargel@gmail.com">
      epargel@gmail.com
    </a>

</div>

## 🔌 Setup and First Use

Follow these steps to properly set up the shaker table:

- **Connect the power cable** to the included 12V power supply.
- **Create a WiFi Hotspot**  
  **SSID:** p-sensors.com  
  **Password:** p-sensors.com123

<script>
  window.onload = function () {
    const isWindows = navigator.userAgent.indexOf('Windows') !== -1;
    const hotspotLink = document.getElementById('hotspot-link');
    const instructions = document.getElementById('hotspot-instructions');

    if (isWindows) {
      hotspotLink.style.display = 'inline-block';
    } else {
      instructions.innerHTML = 'It looks like you are using macOS. To share internet, go to "System Preferences" → "Sharing" → "Internet Sharing".';
    }
  };
</script>

<a id="hotspot-link" href="ms-settings:network-mobilehotspot" style="display:none;" class="hotspot-button">
  Open Hotspot Settings in Windows
</a>

<p id="hotspot-instructions" class="hotspot-instruction"></p>

- **Turn on the main switch** and verify the LED indicator turns on. Once connected to WiFi, the green LED will stop blinking.
- **Open the control software**  
  In your web browser, go to <a href="http://p-shaker.local" target="_blank">p-shaker.local</a>  
  If this is your first time, you will be asked for an activation key, which can be found on the device’s warranty card.
- **Run your first test**  
  Enter the sinusoidal function and click **Start**. The shaker will perform auto-calibration and centering before starting.

If the table does not respond, check the [Troubleshooting](maintenance.md) section.

Explore the full documentation for more! 🚀


<!--mkdocs serve -->  