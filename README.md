<svg width="900" height="240" viewBox="0 0 900 240" xmlns="http://www.w3.org/2000/svg">
<defs>
  <radialGradient id="bgNebula" cx="50%" cy="45%" r="75%">
    <stop offset="0%" stop-color="#152A52"/>
    <stop offset="45%" stop-color="#0A1930"/>
    <stop offset="100%" stop-color="#050B1F"/>
  </radialGradient>

  <linearGradient id="borderGrad" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#4CC9F0"/>
    <stop offset="50%" stop-color="#3A86FF"/>
    <stop offset="100%" stop-color="#4CC9F0"/>
  </linearGradient>

  <linearGradient id="trailGrad" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#ffffff" stop-opacity="0.9"/>
    <stop offset="100%" stop-color="#ffffff" stop-opacity="0"/>
  </linearGradient>

  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="5" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="2.2" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="starGlow" x="-100%" y="-100%" width="300%" height="300%">
    <feGaussianBlur stdDeviation="1.3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="bigBlur" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="30"/>
  </filter>

  <clipPath id="frameClip">
    <rect x="4" y="4" width="892" height="232" rx="16"/>
  </clipPath>
</defs>

<rect x="4" y="4" width="892" height="232" rx="16" fill="url(#bgNebula)" stroke="url(#borderGrad)" stroke-width="2" filter="url(#glow)"/>

<g clip-path="url(#frameClip)">
  <!-- nebula blobs -->
  <g filter="url(#bigBlur)">
    <ellipse cx="200" cy="80" rx="180" ry="90" fill="#7B2FF7" opacity="0.12">
      <animateTransform attributeName="transform" type="translate" values="0,0; 30,15; 0,0" dur="18s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="650" cy="165" rx="200" ry="100" fill="#00B4D8" opacity="0.10">
      <animateTransform attributeName="transform" type="translate" values="0,0; -25,-10; 0,0" dur="22s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="470" cy="35" rx="150" ry="70" fill="#3A0CA3" opacity="0.10">
      <animateTransform attributeName="transform" type="translate" values="0,0; 15,20; 0,0" dur="25s" repeatCount="indefinite"/>
    </ellipse>
  </g>

  <!-- starfield -->
  <circle cx="298.5" cy="46.0" r="1.38" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.18s" begin="1.61s" repeatCount="indefinite"/>
  </circle>
  <circle cx="521.2" cy="206.9" r="0.86" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.21s" begin="1.25s" repeatCount="indefinite"/>
  </circle>
  <circle cx="98.0" cy="104.0" r="1.59" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.31s" begin="0.67s" repeatCount="indefinite"/>
  </circle>
  <circle cx="516.3" cy="98.1" r="1.77" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.12s" begin="2.58s" repeatCount="indefinite"/>
  </circle>
  <circle cx="380.5" cy="128.6" r="1.29" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.4s" begin="2.05s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520.2" cy="149.4" r="1.05" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.37s" begin="0.19s" repeatCount="indefinite"/>
  </circle>
  <circle cx="552.3" cy="119.2" r="1.24" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.94s" begin="1.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="331.0" cy="66.7" r="0.82" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.95s" begin="0.25s" repeatCount="indefinite"/>
  </circle>
  <circle cx="471.7" cy="199.5" r="1.48" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.72s" begin="2.94s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460.3" cy="49.0" r="1.01" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.33s" begin="1.27s" repeatCount="indefinite"/>
  </circle>
  <circle cx="677.5" cy="135.5" r="1.65" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.78s" begin="2.09s" repeatCount="indefinite"/>
  </circle>
  <circle cx="518.7" cy="110.7" r="1.61" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.36s" begin="1.42s" repeatCount="indefinite"/>
  </circle>
  <circle cx="72.2" cy="162.7" r="1.38" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.48s" begin="2.47s" repeatCount="indefinite"/>
  </circle>
  <circle cx="636.3" cy="202.1" r="1.02" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.35s" begin="1.07s" repeatCount="indefinite"/>
  </circle>
  <circle cx="444.6" cy="60.3" r="0.94" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.85s" begin="1.19s" repeatCount="indefinite"/>
  </circle>
  <circle cx="89.3" cy="109.2" r="1.26" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.21s" begin="2.46s" repeatCount="indefinite"/>
  </circle>
  <circle cx="627.5" cy="223.1" r="1.42" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.95s" begin="0.69s" repeatCount="indefinite"/>
  </circle>
  <circle cx="171.5" cy="63.2" r="0.88" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.21s" begin="1.77s" repeatCount="indefinite"/>
  </circle>
  <circle cx="262.5" cy="44.9" r="1.24" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.52s" begin="0.96s" repeatCount="indefinite"/>
  </circle>
  <circle cx="613.8" cy="123.3" r="1.34" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.69s" begin="0.16s" repeatCount="indefinite"/>
  </circle>
  <circle cx="362.3" cy="97.6" r="1.18" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.0s" begin="0.57s" repeatCount="indefinite"/>
  </circle>
  <circle cx="398.9" cy="37.3" r="1.32" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.26s" begin="1.7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="836.1" cy="144.1" r="0.68" fill="#CAF0F8">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.52s" begin="1.13s" repeatCount="indefinite"/>
  </circle>
  <circle cx="841.7" cy="141.7" r="1.17" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="2.29s" begin="1.46s" repeatCount="indefinite"/>
  </circle>
  <circle cx="433.1" cy="80.1" r="0.77" fill="#9be8ff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="3.87s" begin="2.22s" repeatCount="indefinite"/>
  </circle>
  <circle cx="732.8" cy="48.2" r="0.63" fill="#ffffff">
    <animate attributeName="opacity" values="0.12;1;0.12" dur="4.38s" begin="1.58s" repeatCount="indefinite"/>
  </circle>

  <!-- spiral galaxy -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="0 745 118;360 745 118" dur="55s" repeatCount="indefinite"/>
    <circle cx="745" cy="118" r="20" fill="#4CC9F0" opacity="0.22" filter="url(#bigBlur)"/>
    <path d="M 751.0,118.0 L 752.6,119.4 L 753.9,121.5 L 754.6,124.0 L 754.6,126.8 L 753.9,129.9 L 752.3,132.9 L 749.9,135.7 L 746.7,138.0 L 742.8,139.8 L 738.3,140.7 L 733.4,140.6 L 728.4,139.5 L 723.4,137.2 L 718.7,133.8" fill="none" stroke="#7DD3FC" stroke-width="2" opacity="0.55" stroke-linecap="round" filter="url(#starGlow)"/>
    <path d="M 739.0,118.0 L 737.4,116.6 L 736.1,114.5 L 735.4,112.0 L 735.4,109.2 L 736.1,106.1 L 737.7,103.1 L 740.1,100.3 L 743.3,98.0 L 747.2,96.2 L 751.7,95.3 L 756.6,95.4 L 761.6,96.5 L 766.6,98.8 L 771.3,102.2" fill="none" stroke="#7DD3FC" stroke-width="2" opacity="0.55" stroke-linecap="round" filter="url(#starGlow)"/>
    <circle cx="745" cy="118" r="6" fill="#EAFBFF" filter="url(#starGlow)"/>
  </g>

  <!-- comets -->
  <g opacity="0">
    <line x1="0" y1="0" x2="-45" y2="-18" stroke="url(#trailGrad)" stroke-width="2" stroke-linecap="round"/>
    <circle cx="0" cy="0" r="2.2" fill="#F0FBFF" filter="url(#starGlow)"/>
    <animateMotion path="M -60,-40 L 520,150" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.02;0.08;0.22;0.3;1" dur="7s" repeatCount="indefinite"/>
  </g>
  <g opacity="0">
    <line x1="0" y1="0" x2="-45" y2="-16" stroke="url(#trailGrad)" stroke-width="2" stroke-linecap="round"/>
    <circle cx="0" cy="0" r="2" fill="#CFF7FF" filter="url(#starGlow)"/>
    <animateMotion path="M 300,-30 L 940,170" dur="9s" begin="3.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.02;0.08;0.2;0.28;1" dur="9s" begin="3.2s" repeatCount="indefinite"/>
  </g>
</g>

<!-- corner brackets -->
<g stroke="#4CC9F0" stroke-width="3" fill="none" stroke-linecap="round" opacity="0.9">
  <path d="M 24 44 L 24 24 L 44 24"/>
  <path d="M 856 24 L 876 24 L 876 44"/>
  <path d="M 24 196 L 24 216 L 44 216"/>
  <path d="M 856 216 L 876 216 L 876 196"/>
</g>

<!-- name / title -->
<text x="330" y="115" text-anchor="middle" font-family="'Courier New', monospace" font-weight="800" font-size="42" fill="#ffffff" filter="url(#softGlow)" letter-spacing="4">Feyy</text>
<text x="330" y="148" text-anchor="middle" font-family="'Courier New', monospace" font-weight="600" font-size="15" fill="#4CC9F0" letter-spacing="3">UI/UX DESIGNER • GRAPHIC DESIGNER</text>
<line x1="270" y1="164" x2="390" y2="164" stroke="#3A86FF" stroke-width="2" opacity="0.8"/>
</svg>