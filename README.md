<svg width="1000" height="260" viewBox="0 0 1000 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0d0b1a"/>
      <stop offset="100%" stop-color="#151226"/>
    </linearGradient>
    <filter id="blur1" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="45"/>
    </filter>
    <linearGradient id="glassStroke" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.35"/>
      <stop offset="50%" stop-color="#8B5CF6" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.08"/>
    </linearGradient>
  </defs>

  <!-- fondo -->
  <rect width="1000" height="260" rx="18" fill="url(#bg)"/>

  <!-- blobs de color difuminados (efecto glass) -->
  <circle cx="150" cy="40" r="110" fill="#8B5CF6" opacity="0.45" filter="url(#blur1)"/>
  <circle cx="870" cy="230" r="130" fill="#6D28D9" opacity="0.4" filter="url(#blur1)"/>
  <circle cx="600" cy="20" r="80" fill="#A78BFA" opacity="0.25" filter="url(#blur1)"/>

  <!-- panel de vidrio -->
  <rect x="70" y="50" width="860" height="160" rx="20"
        fill="#ffffff" fill-opacity="0.06"
        stroke="url(#glassStroke)" stroke-width="1.5"/>

  <!-- brillo superior del panel -->
  <rect x="72" y="52" width="856" height="60" rx="18" fill="#ffffff" fill-opacity="0.04"/>

  <!-- texto -->
  <text x="500" y="125" text-anchor="middle"
        font-family="Segoe UI, Helvetica, Arial, sans-serif"
        font-size="42" font-weight="600" fill="#f4f4f5" letter-spacing="1">
    Sebastián Gonzalez
  </text>
  <text x="500" y="165" text-anchor="middle"
        font-family="Segoe UI, Helvetica, Arial, sans-serif"
        font-size="16" font-weight="400" fill="#a1a1aa" letter-spacing="4">
    SOFTWARE DEVELOPER · IT SUPPORT · TESTER
  </text>

  <!-- linea de acento -->
  <rect x="440" y="185" width="120" height="2" rx="1" fill="#8B5CF6"/>
</svg>
