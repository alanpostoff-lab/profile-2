<svg xmlns="http://www.w3.org/2000/svg" width="1180" height="610" viewBox="0 0 1180 610" role="img" aria-labelledby="title desc">
<title id="title">Animated developer profile hero — light theme</title>
<desc id="desc">Premium animated GitHub profile banner with terminal, ASCII portrait, role rotation, skills and social links.</desc>
<defs>
 <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1"><stop stop-color="#FFFFFF"/><stop offset=".55" stop-color="#F1F5F9"/><stop offset="1" stop-color="#FFFFFF"/><animate attributeName="x1" values="0;1;0" dur="18s" repeatCount="indefinite"/></linearGradient>
 <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0"><stop stop-color="#2563EB"/><stop offset=".52" stop-color="#06B6D4"/><stop offset="1" stop-color="#10B981"/><animate attributeName="x1" values="0;1;0" dur="8s" repeatCount="indefinite"/><animate attributeName="x2" values="1;0;1" dur="8s" repeatCount="indefinite"/></linearGradient>
 <linearGradient id="ascii" x1="0" y1="0" x2="1" y2="0"><stop stop-color="#2563EB"/><stop offset=".55" stop-color="#06B6D4"/><stop offset="1" stop-color="#10B981"/><animate attributeName="x1" values="0;1;0" dur="7s" repeatCount="indefinite"/><animate attributeName="x2" values="1;0;1" dur="7s" repeatCount="indefinite"/></linearGradient>
 <radialGradient id="glowA"><stop stop-color="#2563EB" stop-opacity=".08"/><stop offset="1" stop-color="#2563EB" stop-opacity="0"/></radialGradient>
 <radialGradient id="glowB"><stop stop-color="#06B6D4" stop-opacity=".08"/><stop offset="1" stop-color="#06B6D4" stop-opacity="0"/></radialGradient>
 <linearGradient id="glass" x1="0" y1="0" x2="0" y2="1"><stop stop-color="#0F172A" stop-opacity=".035"/><stop offset="1" stop-color="#0F172A" stop-opacity=".012"/></linearGradient>
 <linearGradient id="shine" x1="0" y1="0" x2="1" y2="0"><stop stop-color="#0F172A" stop-opacity="0"/><stop offset=".5" stop-color="#0F172A" stop-opacity=".12"/><stop offset="1" stop-color="#0F172A" stop-opacity="0"/></linearGradient>
 <filter id="glow" x="-50%" y="-50%" width="200%" height="200%"><feGaussianBlur stdDeviation="5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
 <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%"><feGaussianBlur in="SourceAlpha" stdDeviation="12" result="b"/><feOffset dy="9"/><feComponentTransfer><feFuncA type="linear" slope=".18"/></feComponentTransfer><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge></filter>
 <clipPath id="clip"><rect width="1180" height="610" rx="28"/></clipPath>
 <mask id="scan"><rect width="1180" height="610" fill="white"/><rect x="0" y="-60" width="1180" height="42" fill="black"><animate attributeName="y" values="-60;640" dur="6s" repeatCount="indefinite"/></rect></mask>
</defs>
<g clip-path="url(#clip)">
 <rect width="1180" height="610" fill="url(#bg)"/>
 <ellipse cx="180" cy="125" rx="300" ry="260" fill="url(#glowA)"><animate attributeName="cx" values="180;245;180" dur="15s" repeatCount="indefinite"/></ellipse>
 <ellipse cx="800" cy="280" rx="400" ry="300" fill="url(#glowB)"><animate attributeName="cy" values="280;335;280" dur="17s" repeatCount="indefinite"/></ellipse>
 <g fill="#06B6D4" opacity=".55">
  <circle cx="55" cy="90" r="1.5"><animate attributeName="cy" values="90;72;90" dur="5s" repeatCount="indefinite"/></circle>
  <circle cx="405" cy="76" r="1.2"><animate attributeName="cy" values="76;95;76" dur="6s" repeatCount="indefinite"/></circle>
  <circle cx="520" cy="550" r="1.4"><animate attributeName="cy" values="550;530;550" dur="7s" repeatCount="indefinite"/></circle>
  <circle cx="1110" cy="125" r="1.2"><animate attributeName="cy" values="125;145;125" dur="8s" repeatCount="indefinite"/></circle>
  <circle cx="930" cy="560" r="1.1"><animate attributeName="cx" values="930;950;930" dur="9s" repeatCount="indefinite"/></circle>
 </g>
 <rect x="1" y="1" width="1178" height="608" rx="27" fill="none" stroke="#0F172A" stroke-opacity=".12"/>
 <rect x="1" y="1" width="1178" height="608" rx="27" fill="none" stroke="url(#accent)" stroke-width="1.4" stroke-dasharray="180 2200"><animate attributeName="stroke-dashoffset" values="0;-2380" dur="12s" repeatCount="indefinite"/></rect>
 <path d="M20 2 H1160 Q1178 2 1178 20 V150 Q800 70 20 180 Z" fill="url(#shine)" opacity=".45"/>
 <!-- Left identity panel -->
 <g filter="url(#shadow)"><rect x="24" y="24" width="410" height="562" rx="22" fill="#F8FAFC" fill-opacity=".78" stroke="#0F172A" stroke-opacity=".12"/><rect x="24" y="24" width="410" height="562" rx="22" fill="url(#glass)"/></g>
 <g font-family="ui-monospace,SFMono-Regular,Menlo,Consolas,monospace">
  <circle cx="48" cy="51" r="4" fill="#FB7185"/><circle cx="62" cy="51" r="4" fill="#FBBF24"/><circle cx="76" cy="51" r="4" fill="#34D399"/>
  <text x="95" y="55" fill="#475569" font-size="10" letter-spacing="1.5">IDENTITY / 01</text>
  <text x="48" y="91" fill="#475569" font-size="11" letter-spacing="2">SYSTEM ONLINE</text><circle cx="400" cy="87" r="3" fill="#10B981"><animate attributeName="opacity" values="1;.25;1" dur="1.5s" repeatCount="indefinite"/></circle>
  <g transform="translate(37 146)" font-size="13" font-weight="600" font-family="monospace" fill="url(#ascii)" filter="url(#glow)">
   <animateTransform attributeName="transform" type="translate" values="37 146;37 140;37 146" dur="6s" repeatCount="indefinite"/>
   <text y="0" opacity="0">          .-=============-.</text><animate attributeName="opacity" values="0;1" dur=".3s" begin=".1s" fill="freeze"/>
   <text y="23" opacity="0">       .-'  .---------.  '-.</text><animate attributeName="opacity" values="0;1" dur=".3s" begin=".4s" fill="freeze"/>
   <text y="46" opacity="0">      /    /  .-----.  \    \</text><animate attributeName="opacity" values="0;1" dur=".3s" begin=".7s" fill="freeze"/>
   <text y="69" opacity="0">     |    |  /       \  |    |</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="1s" fill="freeze"/>
   <text y="92" opacity="0">     |    | |  o   o  | |    |</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="1.3s" fill="freeze"/>
   <text y="115" opacity="0">     |    | |    ^    | |    |</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="1.6s" fill="freeze"/>
   <text y="138" opacity="0">     |    |  \  ___  /  |    |</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="1.9s" fill="freeze"/>
   <text y="161" opacity="0">      \    \  '-----'  /    /</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="2.2s" fill="freeze"/>
   <text y="184" opacity="0">       '-.  '---------'  .-'</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="2.5s" fill="freeze"/>
   <text y="207" opacity="0">          '-._________.-'</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="2.8s" fill="freeze"/>
   <text y="230" opacity="0">             /|  |\</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="3.1s" fill="freeze"/>
   <text y="253" opacity="0">            /_|__|_\</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="3.4s" fill="freeze"/>
   <text y="276" opacity="0">              /  \</text><animate attributeName="opacity" values="0;1" dur=".3s" begin="3.7s" fill="freeze"/>
  </g>
  <rect x="24" y="-35" width="410" height="2" fill="#06B6D4" opacity=".35" filter="url(#glow)"><animate attributeName="y" values="-35;590" dur="5.5s" repeatCount="indefinite"/></rect>
  <path d="M48 475 H410" stroke="#0F172A" stroke-opacity=".12"/>
  <text x="48" y="503" fill="#06B6D4" font-size="10" letter-spacing="1.6">BUILDING THE NEXT</text>
  <text x="48" y="528" fill="#0F172A" font-size="16" font-weight="700">idea → interface → impact</text>
  <text x="48" y="557" fill="#475569" font-size="10">~/profile/README.md</text><text x="399" y="557" fill="#10B981" font-size="10" text-anchor="end">● LIVE</text>
 </g>
 <!-- Right terminal -->
 <g filter="url(#shadow)"><rect x="458" y="24" width="698" height="562" rx="22" fill="#F8FAFC" fill-opacity=".88" stroke="#0F172A" stroke-opacity=".12"/><rect x="458" y="24" width="698" height="562" rx="22" fill="url(#glass)"/></g>
 <g font-family="ui-monospace,SFMono-Regular,Menlo,Consolas,monospace">
  <path d="M458 68 H1156" stroke="#0F172A" stroke-opacity=".12"/>
  <circle cx="484" cy="46" r="4" fill="#FB7185"/><circle cx="498" cy="46" r="4" fill="#FBBF24"/><circle cx="512" cy="46" r="4" fill="#34D399"/>
  <text x="538" y="50" fill="#475569" font-size="11">developer@profile</text><text x="1128" y="50" fill="#475569" font-size="10" text-anchor="end">zsh — 80×24</text>
  <text x="490" y="103" fill="#06B6D4" font-size="12">$ whoami</text>
  <text x="490" y="139" fill="#0F172A" font-size="29" font-weight="700" font-family="Inter,ui-sans-serif,system-ui,sans-serif">Hi 👋 I'm <tspan fill="url(#accent)">YOUR NAME</tspan></text>
  <text x="490" y="169" fill="#475569" font-size="13">Crafting thoughtful digital experiences.</text>
  <text x="490" y="207" fill="#06B6D4" font-size="12">$ role --current</text>
  <g fill="#0F172A" font-size="15">
   <text x="490" y="235" opacity="0">Frontend Engineer</text><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;.08;.78;1" dur="8s" repeatCount="indefinite"/>
   <text x="490" y="235" opacity="0">Full Stack Developer</text><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;.08;.78;1" dur="8s" begin="2s" repeatCount="indefinite"/>
   <text x="490" y="235" opacity="0">Open Source Contributor</text><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;.08;.78;1" dur="8s" begin="4s" repeatCount="indefinite"/>
   <text x="490" y="235" opacity="0">UI Engineer · AI Enthusiast</text><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;.08;.78;1" dur="8s" begin="6s" repeatCount="indefinite"/>
  </g>
  <rect x="490" y="218" width="2" height="22" fill="#06B6D4"><animate attributeName="x" values="490;670;490" dur="2.4s" repeatCount="indefinite"/><animate attributeName="opacity" values="1;0;1" dur=".8s" repeatCount="indefinite"/></rect>
  <path d="M490 257 H1124" stroke="#0F172A" stroke-opacity=".12"/>
  <text x="490" y="281" fill="#06B6D4" font-size="11">$ cat about.json</text>
  <g font-size="12.5">
   <text x="490" y="307" fill="#475569">location</text><text x="585" y="307" fill="#0F172A">"Your City, Country"</text>
   <text x="490" y="330" fill="#475569">education</text><text x="585" y="330" fill="#0F172A">"Your Degree / University"</text>
   <text x="490" y="353" fill="#475569">focus</text><text x="585" y="353" fill="#0F172A">"Building useful things"</text>
   <text x="490" y="376" fill="#475569">portfolio</text><text x="585" y="376" fill="#06B6D4">"your-portfolio.dev"</text>
   <text x="490" y="399" fill="#475569">email</text><text x="585" y="399" fill="#06B6D4">"hello@example.com"</text>
  </g>
  <text x="490" y="433" fill="#06B6D4" font-size="11" opacity="0">$ stack --list</text><animate attributeName="opacity" values="0;1" dur=".5s" begin="1.3s" fill="freeze"/>
  <g font-family="ui-sans-serif,system-ui,sans-serif" font-size="11.5" font-weight="600">
   <g><rect x="490" y="447" width="75" height="29" rx="9" fill="#2563EB" fill-opacity=".10" stroke="#2563EB" stroke-opacity=".55"><animate attributeName="stroke-opacity" values=".3;.9;.3" dur="3s" repeatCount="indefinite"/></rect><text x="527.5" y="465" text-anchor="middle" fill="#2563EB">React</text></g>
   <g><rect x="574" y="447" width="83" height="29" rx="9" fill="#06B6D4" fill-opacity=".10" stroke="#06B6D4" stroke-opacity=".55"/><text x="615.5" y="465" text-anchor="middle" fill="#06B6D4">Next.js</text></g>
   <g><rect x="666" y="447" width="80" height="29" rx="9" fill="#06B6D4" fill-opacity=".10" stroke="#06B6D4" stroke-opacity=".55"/><text x="706" y="465" text-anchor="middle" fill="#06B6D4">Node.js</text></g>
   <g><rect x="755" y="447" width="100" height="29" rx="9" fill="#2563EB" fill-opacity=".10" stroke="#2563EB" stroke-opacity=".55"/><text x="805" y="465" text-anchor="middle" fill="#2563EB">TypeScript</text></g>
   <g><rect x="864" y="447" width="93" height="29" rx="9" fill="#10B981" fill-opacity=".10" stroke="#10B981" stroke-opacity=".55"/><text x="910.5" y="465" text-anchor="middle" fill="#10B981">Tailwind</text></g>
   <g><rect x="966" y="447" width="76" height="29" rx="9" fill="#10B981" fill-opacity=".10" stroke="#10B981" stroke-opacity=".55"/><text x="1004" y="465" text-anchor="middle" fill="#10B981">Python</text></g>
   <g><rect x="1051" y="447" width="73" height="29" rx="9" fill="#06B6D4" fill-opacity=".10" stroke="#06B6D4" stroke-opacity=".55"/><text x="1087.5" y="465" text-anchor="middle" fill="#06B6D4">Docker</text></g>
   <g><rect x="490" y="485" width="88" height="29" rx="9" fill="#06B6D4" fill-opacity=".10" stroke="#06B6D4" stroke-opacity=".55"/><text x="534" y="503" text-anchor="middle" fill="#06B6D4">Postgres</text></g>
   <g><rect x="587" y="485" width="60" height="29" rx="9" fill="#10B981" fill-opacity=".10" stroke="#10B981" stroke-opacity=".55"/><text x="617" y="503" text-anchor="middle" fill="#10B981">AWS</text></g>
   <g><rect x="656" y="485" width="52" height="29" rx="9" fill="#2563EB" fill-opacity=".10" stroke="#2563EB" stroke-opacity=".55"/><text x="682" y="503" text-anchor="middle" fill="#2563EB">Git</text></g>
   <g><rect x="717" y="485" width="64" height="29" rx="9" fill="#2563EB" fill-opacity=".10" stroke="#2563EB" stroke-opacity=".55"/><text x="749" y="503" text-anchor="middle" fill="#2563EB">Figma</text></g>
  </g>
  <path d="M490 530 H1124" stroke="#0F172A" stroke-opacity=".12"/>
  <text x="490" y="557" fill="#475569" font-size="11">$ connect --social</text>
  <g transform="translate(665 541)" fill="none" stroke="url(#accent)" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round">
   <circle cx="8" cy="8" r="10" stroke-opacity=".35"/><path d="M4 12 V5 L8 9 L12 5 V12"/>
   <g transform="translate(48 0)"><circle cx="8" cy="8" r="10" stroke-opacity=".35"/><path d="M5 13 V7 M5 4 V4.1 M9 13 V9.5 C9 6.8 14 6.8 14 9.5 V13"/></g>
   <g transform="translate(96 0)"><circle cx="8" cy="8" r="10" stroke-opacity=".35"/><path d="M14 5.5 C12 6 11 6 10 5 C7 3 3 5 4 9 C4.5 11 6 12 8 12 M4 9 L2 9"/></g>
   <g transform="translate(144 0)"><circle cx="8" cy="8" r="10" stroke-opacity=".35"/><path d="M3 13 V3 H13 V13 Z M5 6 H11 M5 9 H11"/></g>
  </g>
  <text x="1126" y="557" fill="#10B981" font-size="10" text-anchor="end">● AVAILABLE</text>
 </g>
 <g opacity=".045" mask="url(#scan)" stroke="#0F172A" stroke-width="1"><path d="M0 80H1180 M0 86H1180 M0 92H1180 M0 98H1180 M0 104H1180 M0 110H1180 M0 116H1180 M0 122H1180 M0 128H1180 M0 134H1180 M0 140H1180 M0 146H1180 M0 152H1180 M0 158H1180 M0 164H1180 M0 170H1180 M0 176H1180 M0 182H1180 M0 188H1180 M0 194H1180 M0 200H1180 M0 206H1180 M0 212H1180 M0 218H1180 M0 224H1180 M0 230H1180 M0 236H1180 M0 242H1180 M0 248H1180 M0 254H1180 M0 260H1180 M0 266H1180 M0 272H1180 M0 278H1180 M0 284H1180 M0 290H1180 M0 296H1180 M0 302H1180 M0 308H1180 M0 314H1180 M0 320H1180 M0 326H1180 M0 332H1180 M0 338H1180 M0 344H1180 M0 350H1180 M0 356H1180 M0 362H1180 M0 368H1180 M0 374H1180 M0 380H1180 M0 386H1180 M0 392H1180 M0 398H1180 M0 404H1180 M0 410H1180 M0 416H1180 M0 422H1180 M0 428H1180 M0 434H1180 M0 440H1180 M0 446H1180 M0 452H1180 M0 458H1180 M0 464H1180 M0 470H1180 M0 476H1180 M0 482H1180 M0 488H1180 M0 494H1180 M0 500H1180 M0 506H1180 M0 512H1180 M0 518H1180 M0 524H1180 M0 530H1180 M0 536H1180 M0 542H1180 M0 548H1180 M0 554H1180 M0 560H1180 M0 566H1180 M0 572H1180 M0 578H1180 M0 584H1180 M0 590H1180"/></g>
</g></svg>
