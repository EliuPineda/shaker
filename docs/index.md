# Getting Started

<div style="display: flex; justify-content: center;">
  <video autoplay loop muted playsinline width="600">
    <source src="videos/shaker2.mp4" type="video/mp4">
    Tu navegador no soporta video HTML5.
  </video>
</div>



Si en su poder se encuentra el Kit de experimentación e investigación **P-Shaker**, ¡Felicitaciones! Está en presencia de la mesa sísmica más portátil y accesible del mercado.

<div style="text-align: center;">
    <span style="color: rgb(167, 255, 164);">
        ¡Lleva hoy tu <em>Kit educativo de experimentación e investigación P-Shaker</em>! <br>
        <span style="color: rgb(255, 134, 35);">
            Ahora en preventa: <strong style="color: rgb(105, 255, 35);">USD $198.90</strong> <span style="text-decoration: line-through; color: rgb(255, 94, 94);">USD $300</span><br>
            <span style="color: rgb(255, 134, 35);">Envío gratis a Colombia <small>(Consulta disponibilidad)</small></span>
        </span>
    </span>
</div>

<br>

<div style="display: flex; flex-direction: row; align-items: stretch; justify-content: center; gap: 1rem; width: 100%; height: 2rem;">
    <a href="https://biz.payulatam.com/B0f59311D291A18" target="_blank" style="width: 10rem; height: 100%; display: flex; overflow: hidden;border-radius: 0.9rem;">
        <img src="https://ecommerce.payulatam.com/img-secure-2015/boton_pagar_grande.png" alt="Pagar con PayU" style="width: 100%; height: 100%; object-fit: cover;">
    </a>
    <a href="https://api.whatsapp.com/send?phone=573167164222&text=Hola!%20%0ADeseo%20ayuda%20con%20la%20compra%20de%20Platypus%20Shaker" style="background-color: rgb(255, 116, 35); color: white; text-decoration: none; font-weight: bold; border-radius: 0.9rem; width: 5rem; height: 100%; display: flex; align-items: center; justify-content: center;">
        Ayuda🛒 
    </a>
</div>

## 🔌 Pasos de Conexión y Primer Uso
Sigue estos pasos para conectar correctamente la mesa:

- **Conectar el cable de alimentación** a la fuente de 12V (incluida).
- **Crear un HotSpot**  
  **SSID:** p-sensors.com  
  **Contraseña:** p-sensors.com123


<script>
  window.onload = function () {
    const isWindows = navigator.userAgent.indexOf('Windows') !== -1;
    const hotspotLink = document.getElementById('hotspot-link');
    const instructions = document.getElementById('hotspot-instructions');

    if (isWindows) {
      hotspotLink.style.display = 'inline-block';
    } else {
      instructions.innerHTML = 'Parece que estás usando macOS. Para compartir Internet, abre "Preferencias del Sistema" → "Compartir" → "Compartir Internet".';
    }
  };
</script>

<a id="hotspot-link" href="ms-settings:network-mobilehotspot" style="display:none;" class="hotspot-button">
  Abrir configuración de Hotspot en Windows
</a>

<p id="hotspot-instructions" class="hotspot-instruction"></p>



- **Encender el interruptor principal** y verificar que el indicador LED esté encendido. Una vez conectado a la red WiFi, el LED verde dejará de parpadear.
- **Abrir el software de control**  
  En el navegador web, ir a <a href="http://p-shaker.local" target="_blank">p-shaker.local</a>  
  Si es su primer uso, le pedirá la clave de activación, que se encuentra en la tarjeta de garantía del dispositivo.
- **Realizar la primera prueba**  
  Ingrese a la función sinusoidal y presione el botón **Iniciar**. La mesa realizará una calibración y centrado inicial automático antes de ejecutar la función.

Si la mesa no responde, revisa la sección de [Solución de Problemas](mantenimiento.md).

¡Explora la documentación para más detalles! 🚀

<!--mkdocs serve -->  