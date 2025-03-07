# www
airsca.com


<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 300">
  <!-- Background -->
  <rect width="500" height="300" fill="#121a2b" rx="10" ry="10"/>
  
  <!-- Central scanning circle -->
  <circle cx="250" cy="150" r="80" fill="none" stroke="#3498db" stroke-width="3">
    <animate attributeName="r" values="60;80;60" dur="4s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" repeatCount="indefinite" />
  </circle>
  
  <!-- Scanning lines -->
  <circle cx="250" cy="150" r="100" fill="none" stroke="#3498db" stroke-width="1" opacity="0.5">
    <animate attributeName="r" values="80;120;80" dur="6s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="6s" repeatCount="indefinite" />
  </circle>
  
  <circle cx="250" cy="150" r="140" fill="none" stroke="#3498db" stroke-width="1" opacity="0.3">
    <animate attributeName="r" values="120;160;120" dur="8s" repeatCount="indefinite" />
    <animate attributeName="opacity" values="0.1;0.4;0.1" dur="8s" repeatCount="indefinite" />
  </circle>
  
  <!-- Radar sweep -->
  <path d="M 250 150 L 250 50 A 100 100 0 0 1 339 181" fill="none" stroke="#2ecc71" stroke-width="3">
    <animateTransform attributeName="transform" type="rotate" from="0 250 150" to="360 250 150" dur="4s" repeatCount="indefinite" />
  </path>
  
  <!-- Signal tower -->
  <path d="M 250 180 L 250 220" stroke="#e74c3c" stroke-width="8" stroke-linecap="round"/>
  <path d="M 230 220 L 270 220" stroke="#e74c3c" stroke-width="8" stroke-linecap="round"/>
  
  <!-- Signal waves -->
  <path d="M 235 160 Q 250 140 265 160" fill="none" stroke="#e74c3c" stroke-width="3"/>
  <path d="M 225 145 Q 250 115 275 145" fill="none" stroke="#e74c3c" stroke-width="3"/>
  <path d="M 215 130 Q 250 90 285 130" fill="none" stroke="#e74c3c" stroke-width="3"/>
  
  <!-- Text Logo -->
  <text x="250" y="260" font-family="Arial, sans-serif" font-weight="bold" font-size="40" text-anchor="middle" fill="#ffffff">AIRSCA</text>
  <text x="250" y="280" font-family="Arial, sans-serif" font-size="12" text-anchor="middle" fill="#3498db">Air Scanning & Analysis Systems</text>
</svg>
