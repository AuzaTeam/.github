<div align="center" class="container">
    <svg width="351" height="351" viewBox="0 0 351 351" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
        @keyframes flicker {
          0%, 100% { opacity: 1; }
          3% { opacity: 0.4; }
          6% { opacity: 1; }
          7.5% { opacity: 0.6; }
          8% { opacity: 0.2; }
          9% { opacity: 0.5; }
          10% { opacity: 1; }
          25% { opacity: 1; }
          25.5% { opacity: 0.3; }
          26% { opacity: 1; }
          28% { opacity: 0.5; }
          30% { opacity: 1; }
          55% { opacity: 1; }
          55.5% { opacity: 0.7; }
          56% { opacity: 1; }
          60% { opacity: 0.3; }
          60.7% { opacity: 0.8; }
          61.5% { opacity: 0; }
          62% { opacity: 1; }
          73% { opacity: 1; }
          73.5% { opacity: 0.4; }
          74% { opacity: 1; }
          75% { opacity: 0.8; }
          75.5% { opacity: 0.3; }
          76% { opacity: 1; }
          80% { opacity: 1; }
        }
        @keyframes glitch1 {
          0%, 100% { transform: translateX(0) skewX(0); }
          7% { transform: translateX(-2px) skewX(2deg); }
          7.5% { transform: translateX(-3px) skewY(-1deg); }
          8% { transform: translateX(0) skew(0); }
          27% { transform: translateX(0) skewX(0); }
          28% { transform: translateX(4px) skewX(-1deg); }
          28.5% { transform: translateX(5px) skewY(1deg); }
          29% { transform: translateX(0) skew(0); }
          30% { transform: translateX(3px); }
          35% { transform: translateX(0); }
          52% { transform: translateX(0) skewX(0); }
          53% { transform: translateX(-1px) skewX(1deg); }
          54% { transform: translateX(-3px) skewY(-1deg); }
          55% { transform: translateX(-1px); }
          58% { transform: translateX(0); }
          77% { transform: translateX(0); }
          77.3% { transform: translateX(3px); }
          77.5% { transform: translateX(5px) skewX(-1.5deg); }
          77.8% { transform: translateX(0); }
          80% { transform: translateX(2px); }
          85% { transform: translateX(0); }
        }
        @keyframes glitch2 {
          0%, 100% { transform: translateX(0) skewY(0); }
          7% { transform: translateX(2px) skewY(-1deg); }
          8% { transform: translateX(4px) skewY(1deg); }
          9% { transform: translateX(0) skewY(0); }
          10% { transform: translateX(0); }
          27% { transform: translateX(0); }
          28% { transform: translateX(-4px) skewY(1deg); }
          29% { transform: translateX(-1px) skewY(0); }
          30% { transform: translateX(-3px); }
          35% { transform: translateX(0); }
          52% { transform: translateX(0); }
          53% { transform: translateX(2px) skewY(-1deg); }
          54% { transform: translateX(3px) skewY(0.5deg); }
          55% { transform: translateX(1px); }
          58% { transform: translateX(0); }
          77% { transform: translateX(0); }
          77.5% { transform: translateX(-5px) skewY(1deg); }
          78% { transform: translateX(-2px) skewY(0); }
          80% { transform: translateX(-2px); }
          85% { transform: translateX(0); }
        }
        @keyframes letterGlitch {
          0%, 100% { transform: translateX(0) skewX(0); opacity: 1; }
          10% { transform: translateX(0) skewX(0); opacity: 1; }
          10.2% { transform: translateX(-4px) skewX(5deg); opacity: 0.8; filter: drop-shadow(4px 0 #00ffff); }
          10.5% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
          25% { transform: translateX(0) skewX(0); opacity: 1; }
          25.1% { transform: translateX(2px) skewX(-3deg); opacity: 0.7; filter: drop-shadow(-2px 0 #ff00de); }
          25.2% { transform: translateX(-1px) skewX(0); opacity: 1; filter: none; }
          42% { transform: translateX(0) skewX(0); opacity: 1; }
          42.1% { transform: translateX(5px) skewX(-5deg); opacity: 0.5; filter: drop-shadow(-3px 0 #ff00de); }
          42.5% { transform: translateX(0) skewY(0); opacity: 1; filter: none; }
          60% { transform: translateX(0) skewX(0); opacity: 1; }
          60.1% { transform: translateX(-3px) skewX(3deg); opacity: 0.7; filter: drop-shadow(3px 0 #ff8800); }
          60.2% { transform: translateX(3px) skewX(-2deg); opacity: 0.6; filter: drop-shadow(-2px 0 #00ffff); }
          60.3% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
          85% { transform: translateX(0) skewX(0); opacity: 1; }
          85.1% { transform: translateX(2px) skewX(-4deg); opacity: 0.7; filter: drop-shadow(3px 0 #00ffff); }
          85.2% { transform: translateX(-4px) skewX(5deg); opacity: 0.5; filter: brightness(1.5) drop-shadow(-2px 0 #ff00de); }
          85.4% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
        }
        @keyframes textDistort {
          0%, 100% { transform: scale(1, 1); }
          10.1% { transform: scale(1.03, 0.97); }
          10.2% { transform: scale(0.98, 1.02); }
          10.3% { transform: scale(1, 1); }
          25% { transform: scale(1, 1); }
          25.1% { transform: scale(1.02, 0.98); }
          25.2% { transform: scale(1, 1); }
          42% { transform: scale(1, 1); }
          42.1% { transform: scale(0.95, 1.05); }
          42.2% { transform: scale(1.03, 0.97); }
          42.3% { transform: scale(1, 1); }
          60% { transform: scale(1, 1); }
          60.1% { transform: scale(1.04, 0.96); }
          60.2% { transform: scale(0.98, 1.02); }
          60.3% { transform: scale(1, 1); }
          85% { transform: scale(1, 1); }
          85.1% { transform: scale(0.94, 1.06); }
          85.2% { transform: scale(1.02, 0.98); }
          85.3% { transform: scale(1, 1); }
        }
        @keyframes individualLetterOffset {
          0%, 100% { transform: translateY(0); }
          15% { transform: translateY(0); }
          15.1% { transform: translateY(-3px); }
          15.2% { transform: translateY(2px); }
          15.3% { transform: translateY(0); } 
          45% { transform: translateY(0); }
          45.1% { transform: translateY(3px); }
          45.2% { transform: translateY(-2px); }
          45.3% { transform: translateY(0); }
          72% { transform: translateY(0); }
          72.1% { transform: translateY(-4px); }
          72.2% { transform: translateY(2px); }
          72.3% { transform: translateY(0); }
        }
        @keyframes letterSlice {
          0%, 100% { clip-path: inset(0 0 0 0); }
          20% { clip-path: inset(0 0 0 0); }
          20.1% { clip-path: inset(40% 0 20% 0); }
          20.15% { clip-path: inset(0 0 0 0); }
          20.2% { clip-path: inset(10% 0 60% 0); }
          20.25% { clip-path: inset(0 0 0 0); }
          60% { clip-path: inset(0 0 0 0); }
          60.1% { clip-path: inset(15% 0 70% 0); }
          60.15% { clip-path: inset(0 0 0 0); }
          85% { clip-path: inset(0 0 0 0); }
          85.1% { clip-path: inset(0 30% 0 40%); }
          85.15% { clip-path: inset(0 0 0 0); }
          85.2% { clip-path: inset(50% 20% 10% 0); }
          85.25% { clip-path: inset(0 0 0 0); }
        }
        @keyframes letterRotate {
          0%, 100% { transform: rotate(0deg); }
          25% { transform: rotate(0deg); }
          25.1% { transform: rotate(-1deg); }
          25.2% { transform: rotate(0deg); }
          50% { transform: rotate(0deg); }
          50.1% { transform: rotate(1deg); }
          50.2% { transform: rotate(0deg); }
          75% { transform: rotate(0deg); }
          75.1% { transform: rotate(-1.5deg); }
          75.2% { transform: rotate(0deg); }
        }
        @keyframes hueRotate {
          0%, 100% { filter: hue-rotate(0deg); }
          25% { filter: hue-rotate(-10deg); }
          50% { filter: hue-rotate(0deg); }
          75% { filter: hue-rotate(10deg); }
        }
        @keyframes drawPath {
          0% { 
            stroke-dashoffset: 1000;
            fill-opacity: 0;
          }
          80% { 
            stroke-dashoffset: 0;
            fill-opacity: 0;
          }
          100% { 
            stroke-dashoffset: 0;
            fill-opacity: 1;
          }
        }
        @keyframes appearFromNoise {
          0% { opacity: 0; filter: blur(10px); }
          30% { opacity: 0.5; filter: blur(5px); }
          60% { opacity: 1; filter: blur(1px); }
          75% { opacity: 0.9; filter: blur(0); }
          85% { opacity: 1; filter: blur(0.5px); }
          90% { opacity: 0.8; filter: blur(0); }
          100% { opacity: 1; filter: blur(0); }
        }
        @keyframes initialFlicker {
          0% { opacity: 0.2; }
          3% { opacity: 0.4; }
          6% { opacity: 1; }
          7.5% { opacity: 0.6; }
          8% { opacity: 0.2; }
          9% { opacity: 0.5; }
          10% { opacity: 1; }
          25% { opacity: 1; }
          25.5% { opacity: 0.3; }
          26% { opacity: 1; }
          28% { opacity: 0.5; }
          30% { opacity: 1; }
          55% { opacity: 1; }
          55.5% { opacity: 0.7; }
          56% { opacity: 1; }
          60% { opacity: 0.3; }
          60.7% { opacity: 0.8; }
          61.5% { opacity: 0; }
          62% { opacity: 1; }
          73% { opacity: 1; }
          73.5% { opacity: 0.4; }
          74% { opacity: 1; }
          75% { opacity: 0.8; }
          75.5% { opacity: 0.3; }
          76% { opacity: 1; }
          80% { opacity: 1; }
          100% { opacity: 1; }
        }
        @keyframes initialGlitch1 {
          0% { transform: translateX(-5px) skewX(5deg); }
          7% { transform: translateX(-2px) skewX(2deg); }
          7.5% { transform: translateX(-3px) skewY(-1deg); }
          8% { transform: translateX(0) skew(0); }
          27% { transform: translateX(0) skewX(0); }
          28% { transform: translateX(4px) skewX(-1deg); }
          28.5% { transform: translateX(5px) skewY(1deg); }
          29% { transform: translateX(0) skew(0); }
          30% { transform: translateX(3px); }
          35% { transform: translateX(0); }
          52% { transform: translateX(0) skewX(0); }
          53% { transform: translateX(-1px) skewX(1deg); }
          54% { transform: translateX(-3px) skewY(-1deg); }
          55% { transform: translateX(-1px); }
          58% { transform: translateX(0); }
          77% { transform: translateX(0); }
          77.3% { transform: translateX(3px); }
          77.5% { transform: translateX(5px) skewX(-1.5deg); }
          77.8% { transform: translateX(0); }
          80% { transform: translateX(2px); }
          85% { transform: translateX(0); }
          100% { transform: translateX(0) skewX(0); }
        }
        @keyframes initialGlitch2 {
          0% { transform: translateX(5px) skewY(3deg); }
          7% { transform: translateX(2px) skewY(-1deg); }
          8% { transform: translateX(4px) skewY(1deg); }
          9% { transform: translateX(0) skewY(0); }
          10% { transform: translateX(0); }
          27% { transform: translateX(0); }
          28% { transform: translateX(-4px) skewY(1deg); }
          29% { transform: translateX(-1px) skewY(0); }
          30% { transform: translateX(-3px); }
          35% { transform: translateX(0); }
          52% { transform: translateX(0); }
          53% { transform: translateX(2px) skewY(-1deg); }
          54% { transform: translateX(3px) skewY(0.5deg); }
          55% { transform: translateX(1px); }
          58% { transform: translateX(0); }
          77% { transform: translateX(0); }
          77.5% { transform: translateX(-5px) skewY(1deg); }
          78% { transform: translateX(-2px) skewY(0); }
          80% { transform: translateX(-2px); }
          85% { transform: translateX(0); }
          100% { transform: translateX(0) skewY(0); }
        }
        @keyframes initialLetterGlitch {
          0% { transform: translateX(-6px) skewX(10deg); opacity: 0.6; filter: drop-shadow(6px 0 #ff00de); }
          10% { transform: translateX(0) skewX(0); opacity: 1; }
          10.2% { transform: translateX(-4px) skewX(5deg); opacity: 0.8; filter: drop-shadow(4px 0 #00ffff); }
          10.5% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
          25% { transform: translateX(0) skewX(0); opacity: 1; }
          25.1% { transform: translateX(2px) skewX(-3deg); opacity: 0.7; filter: drop-shadow(-2px 0 #ff00de); }
          25.2% { transform: translateX(-1px) skewX(0); opacity: 1; filter: none; }
          42% { transform: translateX(0) skewX(0); opacity: 1; }
          42.1% { transform: translateX(5px) skewX(-5deg); opacity: 0.5; filter: drop-shadow(-3px 0 #ff00de); }
          42.5% { transform: translateX(0) skewY(0); opacity: 1; filter: none; }
          60% { transform: translateX(0) skewX(0); opacity: 1; }
          60.1% { transform: translateX(-3px) skewX(3deg); opacity: 0.7; filter: drop-shadow(3px 0 #ff8800); }
          60.2% { transform: translateX(3px) skewX(-2deg); opacity: 0.6; filter: drop-shadow(-2px 0 #00ffff); }
          60.3% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
          85% { transform: translateX(0) skewX(0); opacity: 1; }
          85.1% { transform: translateX(2px) skewX(-4deg); opacity: 0.7; filter: drop-shadow(3px 0 #00ffff); }
          85.2% { transform: translateX(-4px) skewX(5deg); opacity: 0.5; filter: brightness(1.5) drop-shadow(-2px 0 #ff00de); }
          85.4% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
          100% { transform: translateX(0) skewX(0); opacity: 1; filter: none; }
        }
        @keyframes initialTextDistort {
          0% { transform: scale(1.05, 0.95); }
          10.1% { transform: scale(1.03, 0.97); }
          10.2% { transform: scale(0.98, 1.02); }
          10.3% { transform: scale(1, 1); }
          25% { transform: scale(1, 1); }
          25.1% { transform: scale(1.02, 0.98); }
          25.2% { transform: scale(1, 1); }
          42% { transform: scale(1, 1); }
          42.1% { transform: scale(0.95, 1.05); }
          42.2% { transform: scale(1.03, 0.97); }
          42.3% { transform: scale(1, 1); }
          60% { transform: scale(1, 1); }
          60.1% { transform: scale(1.04, 0.96); }
          60.2% { transform: scale(0.98, 1.02); }
          60.3% { transform: scale(1, 1); }
          85% { transform: scale(1, 1); }
          85.1% { transform: scale(0.94, 1.06); }
          85.2% { transform: scale(1.02, 0.98); }
          85.3% { transform: scale(1, 1); }
          100% { transform: scale(1, 1); }
        }
        @keyframes initialLetterSlice {
          0% { clip-path: inset(50% 0 20% 0); }
          10% { clip-path: inset(0 0 0 0); }
          20% { clip-path: inset(0 0 0 0); }
          20.1% { clip-path: inset(40% 0 20% 0); }
          20.15% { clip-path: inset(0 0 0 0); }
          20.2% { clip-path: inset(10% 0 60% 0); }
          20.25% { clip-path: inset(0 0 0 0); }
          60% { clip-path: inset(0 0 0 0); }
          60.1% { clip-path: inset(15% 0 70% 0); }
          60.15% { clip-path: inset(0 0 0 0); }
          85% { clip-path: inset(0 0 0 0); }
          85.1% { clip-path: inset(0 30% 0 40%); }
          85.15% { clip-path: inset(0 0 0 0); }
          85.2% { clip-path: inset(50% 20% 10% 0); }
          85.25% { clip-path: inset(0 0 0 0); }
          100% { clip-path: inset(0 0 0 0); }
        }
        @keyframes glitchFadeOut {
          0%, 70% { opacity: 1; }
          85% { opacity: 0.8; }
          90% { opacity: 0.6; }
          95% { opacity: 0.3; }
          100% { opacity: 0; }
        }
        @keyframes transformFadeOut {
          0%, 70% { transform: translate(0, 0) skew(0, 0) scale(1, 1); opacity: 1; }
          85% { transform: translate(0, 0) skew(0, 0) scale(1, 1); opacity: 0.7; }
          90% { transform: translate(0, 0) skew(0, 0) scale(1, 1); opacity: 0.5; }
          95% { transform: translate(0, 0) skew(0, 0) scale(1, 1); opacity: 0.2; }
          100% { transform: translate(0, 0) skew(0, 0) scale(1, 1); opacity: 0; }
        }
        @keyframes hueRotateFade {
          0% { filter: hue-rotate(-15deg); }
          25% { filter: hue-rotate(-10deg); }
          50% { filter: hue-rotate(0deg); }
          75% { filter: hue-rotate(10deg); }
          100% { filter: hue-rotate(0deg); }
        }
        .glitch-container {
          animation: initialFlicker 2s linear, hueRotateFade 6s ease-in-out;
          animation-fill-mode: forwards;
        }
        .glitch-layer-1 {
          animation: initialGlitch1 2s linear, glitchFadeOut 6s ease-in-out;
          animation-fill-mode: forwards;
          mix-blend-mode: screen;
        }
        .glitch-layer-2 {
          animation: initialGlitch2 2s linear, glitchFadeOut 6s ease-in-out;
          animation-fill-mode: forwards;
          opacity: 0.7;
          mix-blend-mode: lighten;
        }
        .outer-path {
          stroke-dasharray: 1000;
          stroke-dashoffset: 1000;
          animation: drawPath 2s ease-in-out forwards;
          filter: drop-shadow(0 0 3px rgba(19, 142, 255, 0.8));
        }
        .inner-path {
          stroke-dasharray: 1000;
          stroke-dashoffset: 1000;
          animation: drawPath 2s ease-in-out forwards;
          animation-delay: 1.5s;
          filter: drop-shadow(0 0 4px rgba(19, 142, 255, 0.9));
        }
        .text-glitch {
          opacity: 0;
          animation: initialLetterGlitch 2s linear, initialTextDistort 2s linear, appearFromNoise 0.5s ease-out forwards, transformFadeOut 6s ease-in-out forwards;
          animation-delay: 0s, 0s, 3.5s, 3.5s;
          transform-origin: center;
        }
        .letter-a1 {
          animation: individualLetterOffset 1.7s ease-in-out, letterRotate 3.1s ease-in-out;
          animation-iteration-count: 3, 3;
          transform-origin: center;
        }
        .letter-u {
          animation: initialLetterSlice 2.3s ease-in-out, letterRotate 2.7s ease-in-out;
          animation-iteration-count: 3, 3;
          transform-origin: center;
        }
        .letter-z {
          animation: individualLetterOffset 2.1s ease-in-out, letterRotate 3.3s ease-in-out;
          animation-iteration-count: 3, 3;
          transform-origin: center;
        }
        .letter-a2 {
          animation: initialLetterSlice 1.9s ease-in-out, letterRotate 2.9s ease-in-out;
          animation-iteration-count: 3, 3;
          transform-origin: center;
        }
        .static-logo {
          opacity: 0;
          animation: staticLogoAppear 6s ease-in-out forwards;
        }
        @keyframes staticLogoAppear {
          0%, 70% { opacity: 0; }
          85% { opacity: 0.2; }
          90% { opacity: 0.4; }
          95% { opacity: 0.7; }
          100% { opacity: 1; }
        }
      </style>
  <g class="glitch-container">
    <!-- Glitch Layer 1 - slight offset -->
    <g class="glitch-layer-1">
      <path class="outer-path" d="M63.2805 227H54L68.5 247L79.4976 260.747C81.3953 263.119 84.2684 264.5 87.3062 264.5H114.5L175.5 142.5L237.5 264.5H266.354C269.583 264.5 272.614 262.94 274.491 260.312L284 247L297 227H285.606C281.109 227 276.848 229.019 274 232.5L263.086 244.673C261.759 246.154 259.864 247 257.874 247H250.5L177.284 100.08C176.549 98.605 174.445 98.6022 173.706 100.075L100 247H92.3443C90.2292 247 88.2276 246.044 86.8987 244.398L78.5 234C74.6917 229.557 69.1322 227 63.2805 227Z" fill="#138EFF" stroke="#138EFF" stroke-width="2" opacity="0.95"/>
    </g>
    <!-- Glitch Layer 2 - opposite offset -->
    <g class="glitch-layer-2">
      <path class="outer-path" d="M63.2805 227H54L68.5 247L79.4976 260.747C81.3953 263.119 84.2684 264.5 87.3062 264.5H114.5L175.5 142.5L237.5 264.5H266.354C269.583 264.5 272.614 262.94 274.491 260.312L284 247L297 227H285.606C281.109 227 276.848 229.019 274 232.5L263.086 244.673C261.759 246.154 259.864 247 257.874 247H250.5L177.284 100.08C176.549 98.605 174.445 98.6022 173.706 100.075L100 247H92.3443C90.2292 247 88.2276 246.044 86.8987 244.398L78.5 234C74.6917 229.557 69.1322 227 63.2805 227Z" fill="#4DA1FF" stroke="#4DA1FF" stroke-width="2" opacity="0.4"/>
    </g> 
    <!-- Static logo that will appear when glitch fades -->
    <g class="static-logo">
      <path d="M63.2805 227H54L68.5 247L79.4976 260.747C81.3953 263.119 84.2684 264.5 87.3062 264.5H114.5L175.5 142.5L237.5 264.5H266.354C269.583 264.5 272.614 262.94 274.491 260.312L284 247L297 227H285.606C281.109 227 276.848 229.019 274 232.5L263.086 244.673C261.759 246.154 259.864 247 257.874 247H250.5L177.284 100.08C176.549 98.605 174.445 98.6022 173.706 100.075L100 247H92.3443C90.2292 247 88.2276 246.044 86.8987 244.398L78.5 234C74.6917 229.557 69.1322 227 63.2805 227Z" fill="#138EFF" stroke="#138EFF" stroke-width="2"/> 
      <path opacity="0.9962" d="M94.4158 216.524L103.5 230.5L106.419 223.689C109.331 216.894 109.178 209.175 106 202.5L101.928 191.536C100.315 187.195 99.2317 182.674 98.7008 178.074C98.2349 174.036 98.1974 169.96 98.5889 165.915L99.5 156.5C100.498 151.178 101.993 145.962 103.966 140.92L105.5 137C109.147 129.375 113.896 122.328 119.595 116.086L121.5 114L132.5 104.5L135.994 102.222C141.308 98.7559 147.059 96.0132 153.097 94.0655L153.315 93.9952C157.429 92.668 161.659 91.7301 165.949 91.1939C172.286 90.4018 178.702 90.4926 185.013 91.4636L187.761 91.8863C192.573 92.6267 197.293 93.8768 201.841 95.6157C208.572 98.1892 214.855 101.806 220.461 106.334L225 110L228.496 113.69C232.158 117.555 235.458 121.748 238.355 126.215L239.436 127.881C243.784 134.584 247.032 141.939 249.056 149.668C250.679 155.864 251.5 162.242 251.5 168.647V171.32C251.5 178.401 250.448 185.442 248.379 192.214L246.758 197.52C246.254 199.168 245.565 200.753 244.704 202.246C240.837 208.949 240.639 217.159 244.178 224.041L247.5 230.5L251.072 226.162C257.958 217.8 263.155 208.18 266.373 197.837C267.788 193.287 268.812 188.625 269.434 183.901L269.552 183.006C270.514 175.694 270.614 168.294 269.85 160.959L269.198 154.696C268.733 150.241 267.872 145.836 266.623 141.535C264.881 135.535 262.398 129.776 259.23 124.391L257.781 121.928C255.264 117.649 252.425 113.567 249.289 109.719L243 102L240.044 99.0442C236.03 95.0299 231.538 91.5231 226.67 88.6022C223.23 86.538 219.617 84.7758 215.872 83.3355L208.5 80.5C201.525 77.8429 194.257 76.0321 186.851 75.1063L186 75H169.5L166.347 75.3153C158.477 76.1023 150.728 77.8203 143.262 80.4332L141.837 80.9321C136.954 82.6411 132.22 84.7501 127.684 87.2376L126.31 87.9911C121.45 90.6563 116.883 93.8246 112.685 97.4438C107.254 102.126 102.483 107.525 98.5055 113.492L96.2492 116.876C93.0895 121.616 90.3627 126.63 88.1017 131.859L87.4793 133.298C84.8363 139.41 82.9465 145.821 81.8518 152.389C80.9528 157.783 80.5949 163.253 80.7834 168.718L80.9602 173.847C81.317 184.192 83.592 194.381 87.6696 203.896C89.5531 208.29 91.8101 212.516 94.4158 216.524Z" fill="#138EFF" stroke="#138EFF" stroke-width="2.9993"/>
    </g>
    <!-- Main Layer -->
    <path class="outer-path" d="M63.2805 227H54L68.5 247L79.4976 260.747C81.3953 263.119 84.2684 264.5 87.3062 264.5H114.5L175.5 142.5L237.5 264.5H266.354C269.583 264.5 272.614 262.94 274.491 260.312L284 247L297 227H285.606C281.109 227 276.848 229.019 274 232.5L263.086 244.673C261.759 246.154 259.864 247 257.874 247H250.5L177.284 100.08C176.549 98.605 174.445 98.6022 173.706 100.075L100 247H92.3443C90.2292 247 88.2276 246.044 86.8987 244.398L78.5 234C74.6917 229.557 69.1322 227 63.2805 227Z" fill="#138EFF" stroke="#138EFF" stroke-width="2"/>
    <path class="inner-path" opacity="0.9962" d="M94.4158 216.524L103.5 230.5L106.419 223.689C109.331 216.894 109.178 209.175 106 202.5L101.928 191.536C100.315 187.195 99.2317 182.674 98.7008 178.074C98.2349 174.036 98.1974 169.96 98.5889 165.915L99.5 156.5C100.498 151.178 101.993 145.962 103.966 140.92L105.5 137C109.147 129.375 113.896 122.328 119.595 116.086L121.5 114L132.5 104.5L135.994 102.222C141.308 98.7559 147.059 96.0132 153.097 94.0655L153.315 93.9952C157.429 92.668 161.659 91.7301 165.949 91.1939C172.286 90.4018 178.702 90.4926 185.013 91.4636L187.761 91.8863C192.573 92.6267 197.293 93.8768 201.841 95.6157C208.572 98.1892 214.855 101.806 220.461 106.334L225 110L228.496 113.69C232.158 117.555 235.458 121.748 238.355 126.215L239.436 127.881C243.784 134.584 247.032 141.939 249.056 149.668C250.679 155.864 251.5 162.242 251.5 168.647V171.32C251.5 178.401 250.448 185.442 248.379 192.214L246.758 197.52C246.254 199.168 245.565 200.753 244.704 202.246C240.837 208.949 240.639 217.159 244.178 224.041L247.5 230.5L251.072 226.162C257.958 217.8 263.155 208.18 266.373 197.837C267.788 193.287 268.812 188.625 269.434 183.901L269.552 183.006C270.514 175.694 270.614 168.294 269.85 160.959L269.198 154.696C268.733 150.241 267.872 145.836 266.623 141.535C264.881 135.535 262.398 129.776 259.23 124.391L257.781 121.928C255.264 117.649 252.425 113.567 249.289 109.719L243 102L240.044 99.0442C236.03 95.0299 231.538 91.5231 226.67 88.6022C223.23 86.538 219.617 84.7758 215.872 83.3355L208.5 80.5C201.525 77.8429 194.257 76.0321 186.851 75.1063L186 75H169.5L166.347 75.3153C158.477 76.1023 150.728 77.8203 143.262 80.4332L141.837 80.9321C136.954 82.6411 132.22 84.7501 127.684 87.2376L126.31 87.9911C121.45 90.6563 116.883 93.8246 112.685 97.4438C107.254 102.126 102.483 107.525 98.5055 113.492L96.2492 116.876C93.0895 121.616 90.3627 126.63 88.1017 131.859L87.4793 133.298C84.8363 139.41 82.9465 145.821 81.8518 152.389C80.9528 157.783 80.5949 163.253 80.7834 168.718L80.9602 173.847C81.317 184.192 83.592 194.381 87.6696 203.896C89.5531 208.29 91.8101 212.516 94.4158 216.524Z" fill="#138EFF" stroke="#138EFF" stroke-width="2.9993"/>
    <!-- AUZA text with enhanced glitch effects -->
    <g class="text-glitch">
      <!-- Enhanced ghost layers for glitch effect -->
      <path opacity="0.4" d="M116.342 264.303L127.751 241.406H135.423L146.793 264.303H140.796L138.499 259.358H124.558L122.027 264.303H116.342Z" fill="#00ffff" style="mix-blend-mode: screen; filter: blur(1.5px);" />
      <path opacity="0.4" d="M157.681 264.693C155.318 264.693 153.67 264.057 152.735 262.785C151.801 261.513 151.333 259.825 151.333 257.722V241.406H156.473V257.878C156.473 259.098 156.772 259.916 157.369 260.331C157.966 260.747 158.706 260.954 159.589 260.954H167.844C168.675 260.954 169.402 260.747 170.025 260.331C170.648 259.89 170.959 259.072 170.959 257.878V241.406H176.1V257.722" fill="#ff00de" style="mix-blend-mode: screen; filter: blur(1.5px);" />
      <path opacity="0.4" d="M180.563 264.303V260.526L197.853 245.144H180.563V241.406H204.746V245.144L187.105 260.565H204.551L206.108 263.875" fill="#ff8800" style="mix-blend-mode: screen; filter: blur(1.5px);" />
      <path opacity="0.4" d="M205.198 264.303L216.608 241.406H224.279L235.65 264.303H229.653L227.355 259.358H213.414L210.883 264.303H205.198Z" fill="#00ffff" style="mix-blend-mode: screen; filter: blur(1.5px);" />
      <!-- Additional distortion layers -->
      <path opacity="0.3" d="M117.342 264.303L128.751 241.406H136.423L147.793 264.303H141.796L139.499 259.358H125.558L123.027 264.303H117.342Z" fill="#ff00de" style="mix-blend-mode: difference; filter: blur(1px); transform: translate(2px, -1px);" />
      <path opacity="0.3" d="M156.681 264.693C154.318 264.693 152.67 264.057 151.735 262.785C150.801 261.513 150.333 259.825 150.333 257.722V241.406H155.473V257.878C155.473 259.098 155.772 259.916 156.369 260.331C156.966 260.747 157.706 260.954 158.589 260.954H166.844C167.675 260.954 168.402 260.747 169.025 260.331C169.648 259.89 169.959 259.072 169.959 257.878V241.406H175.1V257.722C175.1 259.124 174.905 260.344 174.516 261.383C174.126 262.421 173.477 263.239 172.568 263.836C171.66 264.407 170.401 264.693 168.791 264.693H156.681Z" fill="#00ffff" style="mix-blend-mode: difference; filter: blur(1px); transform: translate(-2px, 1px);" />
      <path opacity="0.3" d="M179.563 264.303V260.526L196.853 245.144H179.563V241.406H203.746V245.144L186.105 260.565H203.551L205.108 263.875" fill="#00ffff" style="mix-blend-mode: difference; filter: blur(1px); transform: translate(2px, 1px);" />
      <path opacity="0.3" d="M204.198 264.303L215.608 241.406H223.279L234.65 264.303H228.653L226.355 259.358H212.414L209.883 264.303H204.198Z" fill="#ff00de" style="mix-blend-mode: difference; filter: blur(1px); transform: translate(-2px, -1px);" />
      <!-- First letter A -->
      <path class="letter-a1" d="M117.342 264.303L128.751 241.406H136.423L147.793 264.303H141.796L139.499 259.358H125.558L123.027 264.303H117.342ZM126.96 255.542H138.058L132.723 244.911H132.334L126.96 255.542Z" fill="white"/>
      <!-- Letter U -->
      <path class="letter-u" d="M156.681 264.693C154.318 264.693 152.67 264.057 151.735 262.785C150.801 261.513 150.333 259.825 150.333 257.722V241.406H155.473V257.878C155.473 259.098 155.772 259.916 156.369 260.331C156.966 260.747 157.706 260.954 158.589 260.954H166.844C167.675 260.954 168.402 260.747 169.025 260.331C169.648 259.89 169.959 259.072 169.959 257.878V241.406H175.1V257.722C175.1 259.124 174.905 260.344 174.516 261.383C174.126 262.421 173.477 263.239 172.568 263.836C171.66 264.407 170.401 264.693 168.791 264.693H156.681Z" fill="white"/>
      <!-- Letter Z -->
      <path class="letter-z" d="M179.563 264.303V260.526L196.853 245.144H179.563V241.406H203.746V245.144L186.105 260.565H203.551L205.108 263.875C205.108 263.979 204.758 264.083 204.057 264.187C203.356 264.264 202.149 264.303 200.436 264.303H179.563Z" fill="white"/>
      <!-- Second letter A -->
      <path class="letter-a2" d="M204.198 264.303L215.608 241.406H223.279L234.65 264.303H228.653L226.355 259.358H212.414L209.883 264.303H204.198ZM213.816 255.542H224.914L219.58 244.911H219.19L213.816 255.542Z" fill="white"/>
    </g>
  </g>
  
  <!-- Static Text that will appear when glitch fades -->
  <g class="static-logo">
    <!-- Static AUZA text -->
    <path d="M117.342 264.303L128.751 241.406H136.423L147.793 264.303H141.796L139.499 259.358H125.558L123.027 264.303H117.342ZM126.96 255.542H138.058L132.723 244.911H132.334L126.96 255.542Z" fill="white"/>
    <path d="M156.681 264.693C154.318 264.693 152.67 264.057 151.735 262.785C150.801 261.513 150.333 259.825 150.333 257.722V241.406H155.473V257.878C155.473 259.098 155.772 259.916 156.369 260.331C156.966 260.747 157.706 260.954 158.589 260.954H166.844C167.675 260.954 168.402 260.747 169.025 260.331C169.648 259.89 169.959 259.072 169.959 257.878V241.406H175.1V257.722C175.1 259.124 174.905 260.344 174.516 261.383C174.126 262.421 173.477 263.239 172.568 263.836C171.66 264.407 170.401 264.693 168.791 264.693H156.681Z" fill="white"/>
    <path d="M179.563 264.303V260.526L196.853 245.144H179.563V241.406H203.746V245.144L186.105 260.565H203.551L205.108 263.875C205.108 263.979 204.758 264.083 204.057 264.187C203.356 264.264 202.149 264.303 200.436 264.303H179.563Z" fill="white"/>
    <path d="M204.198 264.303L215.608 241.406H223.279L234.65 264.303H228.653L226.355 259.358H212.414L209.883 264.303H204.198ZM213.816 255.542H224.914L219.58 244.911H219.19L213.816 255.542Z" fill="white"/>
  </g>
</svg>

</div>
<div id="views" align="center">![Uploading png.svg…]()

    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=33&pause=1000&color=F7F7F7&center=true&vCenter=true&repeat=false&width=435&lines=%F0%9F%91%8BHello+from+AuzaTeam" alt="Typing Auza" />
</div>
<div align="center">
    <a href="auzateaminc@gmail.com"><img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Youtube Badge"></a>
    <a href="https://t.me/n1_3ro"><img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"></a>
</div>
<div align="center">
    <h3 align="left">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&vCenter=true&random=true&width=330&lines=%D0%A1%D0%B0%D0%BF+%D0%BE%D1%82+AuzaTeam;FearFusion+Games+%7C+AuzaTeam" alt="Typing SVG" /><br>
  Команда Auza собрана для интересного будущего :)<br><br>Начало наше, начинается с того, что мы собираем новичков для работы над интересными & сложными проектами<br><br>Всегда рады помочь ;)<br><br>
  Стек на начало 25го года
</h3>

<div align="left">
    <img src="https://skillicons.dev/icons?i=git" height="45" alt="git logo"  />
    <img src="https://skillicons.dev/icons?i=unity" height="45" alt="unity logo"  />
    <img src="https://skillicons.dev/icons?i=visualstudio" height="45" alt="visualstudio logo"  />
    <img src="https://skillicons.dev/icons?i=cs" height="45" alt="csharp logo"  />
    <img src="https://skillicons.dev/icons?i=dotnet" height="45" alt="dot-net logo"  />
    <img src="https://skillicons.dev/icons?i=postgres" height="45" alt="postgresql logo"  />
    <img src="https://skillicons.dev/icons?i=vscode" height="45" alt="vscode logo"  />
    <img src="https://skillicons.dev/icons?i=js" height="45" alt="javascript logo"  />
    <img src="https://skillicons.dev/icons?i=ts" height="45" alt="typescript logo"  />
    <img src="https://skillicons.dev/icons?i=css" height="45" alt="css3 logo"  />
    <img src="https://skillicons.dev/icons?i=html" height="45" alt="html5 logo"  />
    <img src="https://skillicons.dev/icons?i=tailwind" height="45" alt="tailwindcss logo"  />
    <img src="https://skillicons.dev/icons?i=react" height="45" alt="react logo"  />
    <img src="https://skillicons.dev/icons?i=vue" height="45" alt="vue logo"  />
    <img src="https://skillicons.dev/icons?i=github" height="45" alt="github logo"  />
</div>
</div>  
<div align="center">
    <h2 style="font-size:100px">🏆 Участники на начало 2025</h2>
    <a href="https://github.com/n13ro" target="_blank"><img src="https://github-widgetbox.vercel.app/api/profile?username=n13ro&data=followers,repositories,stars,commits" alt="Telegram Badge"></a>
    <a href="https://github.com/Ypags" target="_blank"><img src="https://github-widgetbox.vercel.app/api/profile?username=Ypags&data=followers,repositories,stars,commits" alt="Telegram Badge"></a>
    <a href="https://github.com/Zzerud" target="_blank"> <img src="https://github-widgetbox.vercel.app/api/profile?username=Zzerud&data=followers,repositories,stars,commits" alt="Telegram Badge"></a>
</div>

