<template>
  <div class="demo-dom">
    <svg
      width="100"
      height="100"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 100 100"
    >
      <path d="M10 10 H 90 V 90 H 10 L 10 10" />

      <!-- Points -->
      <circle cx="10" cy="10" r="2" fill="red" />
      <circle cx="90" cy="90" r="2" fill="red" />
      <circle cx="90" cy="10" r="2" fill="red" />
      <circle cx="10" cy="90" r="2" fill="red" />
    </svg>

    <svg
      width="300"
      height="300"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 100 100"
    >
      <rect x="0" y="0" width="100" height="100" fill="currentColor" />
      <circle cx="50" cy="50" r="50" fill="green" />
      <text x="50" y="55" font-size="20" text-anchor="middle" fill="white">
        SVG
      </text>
    </svg>

    <svg width="300" height="300" xmlns="http://www.w3.org/2000/svg">
      <rect
        x="10"
        y="10"
        width="30"
        height="30"
        stroke="black"
        fill="transparent"
        stroke-width="5"
      />
      <rect
        x="60"
        y="10"
        rx="10"
        ry="10"
        width="30"
        height="30"
        stroke="black"
        fill="transparent"
        stroke-width="5"
      />

      <circle
        cx="25"
        cy="75"
        r="20"
        stroke="red"
        fill="transparent"
        stroke-width="5"
      />
      <ellipse
        cx="75"
        cy="75"
        rx="20"
        ry="5"
        stroke="red"
        fill="transparent"
        stroke-width="5"
      />

      <line
        x1="10"
        x2="50"
        y1="110"
        y2="150"
        stroke="orange"
        fill="transparent"
        stroke-width="5"
      />
      <polyline
        points="60 110 65 120 70 115 75 130 80 125 85 140 90 135 95 150 100 145 90 200 60 110"
        stroke="orange"
        fill="transparent"
        stroke-width="5"
      />

      <polygon
        points="50 160 55 180 70 180 60 190 65 205 50 195 35 205 40 190 30 180 45 180"
        stroke="green"
        fill="transparent"
        stroke-width="5"
      />

      <path
        d="M20,230 Q40,205 50,230 T90,230"
        fill="none"
        stroke="blue"
        stroke-width="5"
      />
    </svg>
  </div>
</template>
<style>
body {
  margin: 0;
}
.demo-dom {
  color: blue;
}
</style>
