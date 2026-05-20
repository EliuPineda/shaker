# Product Usage 🎮

##  Operating Modes
- **Sinusoidal function**: Simulation of predefined earthquakes.
- **Preloaded earthquakes**: Control via graphical interface.

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
      instructions.innerHTML = 'It looks like you are using Android or iOS';
    }
  };
</script>

<a id="hotspot-link" href="ms-settings:network-mobilehotspot" style="display:none;" class="hotspot-button">
  Open Hotspot Settings in Windows
</a>

<p id="hotspot-instructions" class="hotspot-instruction"></p>

- **Turn on the main switch** and verify the LED indicator turns on. Once connected to WiFi, the green LED will stop blinking.
- **Open the control software**  
  In your web browser, go to `p-shaker-(6 digit device ID).local`.

  For example, if the device ID is `45f38a`, open:

  - `p-shaker-45f38a.local`
  - `p-motion-45f38a.local`

  For software versions released in 2025 and later, simply open:
  
  - `p-shaker.local`

  If this is your first time accessing the device, you will be asked for an activation key.  
  The activation key can be found on the device’s warranty card.
- **Run your first test**  
  Enter the sinusoidal function and click **Start**. The shaker will perform auto-calibration and centering before starting.

If the table does not respond, check the [Troubleshooting](maintenance.md) section.
