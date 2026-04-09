<a href="https://example.com">
  <svg viewBox="0 0 260 60" width="260">
    <defs>
      <linearGradient id="grad" x1="0%" x2="100%">
        <stop offset="0%" stop-color="#ff7e5f">
          <animate attributeName="stop-color"
                   values="#ff7e5f;#6a11cb;#ff7e5f"
                   dur="4s"
                   repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#feb47b">
          <animate attributeName="stop-color"
                   values="#feb47b;#2575fc;#feb47b"
                   dur="4s"
                   repeatCount="indefinite"/>
        </stop>
      </linearGradient>
    </defs>

    <rect width="260" height="60" rx="15" fill="url(#grad)"/>

    <text x="130" y="50%" dominant-baseline="middle" text-anchor="middle"
          fill="white" font-size="18">
      🚀 Launch Project
    </text>
  </svg>
</a>
