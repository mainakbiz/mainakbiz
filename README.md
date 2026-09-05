<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     width="1600"
     height="900"
     viewBox="0 0 1600 900"
     font-family="Consolas, 'Courier New', monospace">

  <style>
    .bg { fill: #0d1117; }
    .panel { fill: #0d1117; stroke: #30363d; stroke-width: 2; }
    .text { fill: #c9d1d9; }
    .muted { fill: #8b949e; }
    .dim { fill: #484f58; }
    .key { fill: #f2cc60; }
    .value { fill: #a5d6ff; }
    .green { fill: #7ee787; }
    .red { fill: #ff7b72; }
    .blue { fill: #79c0ff; }
    .line { stroke: #30363d; stroke-width: 2; }
    .ascii { fill: #8b949e; font-size: 15px; }
    .small { font-size: 14px; }
    .normal { font-size: 18px; }
    .large { font-size: 22px; }
  </style>

  <!-- background -->
  <rect width="1600" height="900" class="bg"/>

  <!-- outer frame -->
  <rect x="12" y="12" width="1576" height="876"
        rx="18" class="panel"/>

  <!-- ========================================================= -->
  <!-- LEFT ASCII ART                                            -->
  <!-- ========================================================= -->

  <g class="ascii">

    <!-- stars -->
    <text x="70" y="70">+</text>
    <text x="185" y="120">·</text>
    <text x="325" y="92">+</text>
    <text x="455" y="145">·</text>
    <text x="110" y="220">·</text>
    <text x="390" y="250">+</text>
    <text x="500" y="185">·</text>

    <!-- moon -->
    <text x="330" y="115" font-size="20">.---.</text>
    <text x="315" y="135">/     \</text>
    <text x="310" y="155">|  )) |</text>
    <text x="315" y="175">\     /</text>
    <text x="330" y="195">'---'</text>

    <!-- mountains -->
    <text x="45" y="275">          /\</text>
    <text x="35" y="295">     /\   /  \        /\</text>
    <text x="25" y="315">    /  \_/    \  /\  /  \</text>
    <text x="20" y="335">___/            \/  \/    \___</text>
    <text x="20" y="355">   .    .       /\       .</text>
    <text x="20" y="375">      .        /  \    .</text>

    <text x="20" y="395">   .........___/....\___.........</text>
    <text x="20" y="415">       .........  .........</text>

    <!-- snow -->
    <text x="45" y="335">       /\</text>
    <text x="38" y="350">      /  \</text>
    <text x="30" y="365">_____/____\______</text>

    <!-- trees -->
    <text x="25" y="470" class="green">  ^    ^       ^    ^</text>
    <text x="20" y="490" class="green"> /|\  /|\     /|\  /|\</text>
    <text x="15" y="510" class="green"> |||  |||  ^  |||  |||</text>
    <text x="20" y="530" class="green"> |||  ||| /|\ |||  |||</text>
    <text x="10" y="550" class="green">||||||||||||||||||||||||||||</text>

    <text x="35" y="575" class="green"> |||    |||      |||    |||</text>
    <text x="30" y="595" class="green"> |||    |||      |||    |||</text>

    <!-- cabin -->
    <text x="265" y="490">        /\</text>
    <text x="250" y="510">       /  \</text>
    <text x="240" y="530">      /____\</text>
    <text x="235" y="550">     |  []  |</text>
    <text x="235" y="570">     |  __  |</text>
    <text x="230" y="590">_____|_|__|_|_____</text>

    <!-- cabin window glow -->
    <text x="270" y="550" class="key">[]</text>

    <!-- water -->
    <text x="20" y="630" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>
    <text x="40" y="650" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>
    <text x="15" y="670" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>
    <text x="55" y="690" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>
    <text x="25" y="710" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>
    <text x="70" y="730" class="blue">~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</text>

    <!-- reflection -->
    <text x="145" y="750">---------------------------</text>
    <text x="180" y="770">-----------------------</text>
    <text x="210" y="790">-------------------</text>

    <!-- quote -->
    <text x="45" y="830" class="muted">/  "A more thoughtful internet."</text>
    <text x="65" y="852" class="muted">   One small thing at a time.</text>

  </g>


  <!-- ========================================================= -->
  <!-- RIGHT SIDE                                                 -->
  <!-- ========================================================= -->

  <!-- header -->
  <text x="640" y="60" class="text large">YOUR_USERNAME@github</text>
  <line x1="835" y1="54" x2="1480" y2="54" class="line"/>

  <circle cx="1515" cy="53" r="7" class="green"/>
  <text x="1535" y="60" class="green">online</text>


  <!-- ========================================================= -->
  <!-- ABOUT                                                      -->
  <!-- ========================================================= -->

  <text x="640" y="105" class="key large">whoami</text>
  <text x="820" y="105" class="muted">:</text>
  <text x="850" y="105" class="value large">design engineer</text>

  <text x="640" y="135" class="key large">location</text>
  <text x="820" y="135" class="muted">:</text>
  <text x="850" y="135" class="value">somewhere on earth</text>

  <text x="640" y="165" class="key large">focus</text>
  <text x="820" y="165" class="muted">:</text>
  <text x="850" y="165" class="value">design × code × ai</text>

  <text x="640" y="195" class="key large">currently</text>
  <text x="820" y="195" class="muted">:</text>
  <text x="850" y="195" class="value">building useful things</text>

  <text x="640" y="225" class="key large">learning</text>
  <text x="820" y="225" class="muted">:</text>
  <text x="850" y="225" class="value">systems, interfaces, and a bit of everything</text>

  <text x="640" y="255" class="key large">mindset</text>
  <text x="820" y="255" class="muted">:</text>
  <text x="850" y="255" class="value">curious, always</text>


  <!-- quote -->
  <line x1="1375" y1="95" x2="1375" y2="245" class="line"/>

  <text x="1400" y="125" class="muted">"good</text>
  <text x="1400" y="150" class="muted"> software</text>
  <text x="1400" y="175" class="muted"> feels</text>
  <text x="1400" y="200" class="muted"> inevitable."</text>


  <!-- ========================================================= -->
  <!-- TECH                                                        -->
  <!-- ========================================================= -->

  <text x="640" y="300" class="text large">tech</text>
  <line x1="710" y1="294" x2="1480" y2="294" class="line"/>

  <text x="640" y="340" class="key large">languages</text>
  <text x="820" y="340" class="muted">:</text>
  <text x="850" y="340" class="value">TypeScript, Python, JavaScript, HTML, CSS</text>

  <text x="640" y="370" class="key large">tools</text>
  <text x="820" y="370" class="muted">:</text>
  <text x="850" y="370" class="value">React, Next.js, Tailwind, Figma, Git</text>

  <text x="640" y="400" class="key large">interests</text>
  <text x="820" y="400" class="muted">:</text>
  <text x="850" y="400" class="value">product design, web, ai, creative coding</text>

  <text x="640" y="430" class="key large">os</text>
  <text x="820" y="430" class="muted">:</text>
  <text x="850" y="430" class="value">macOS, Linux, Windows</text>


  <!-- ========================================================= -->
  <!-- PROJECTS                                                    -->
  <!-- ========================================================= -->

  <text x="640" y="480" class="text large">projects</text>
  <line x1="750" y1="474" x2="1370" y2="474" class="line"/>
  <text x="1390" y="480" class="value">→ see more on github</text>

  <text x="640" y="525" class="green large">01</text>
  <text x="705" y="525" class="green large">a better tomorrow</text>
  <text x="705" y="550" class="muted">small tools for a more thoughtful internet.</text>
  <text x="1410" y="525" class="muted">web, ai, design</text>

  <text x="640" y="590" class="green large">02</text>
  <text x="705" y="590" class="green large">pixels &amp; problems</text>
  <text x="705" y="615" class="muted">experiments in interaction and visual systems.</text>
  <text x="1410" y="590" class="muted">creative coding</text>

  <text x="640" y="655" class="green large">03</text>
  <text x="705" y="655" class="green large">build in public</text>
  <text x="705" y="680" class="muted">notes, ideas, and things in progress.</text>
  <text x="1410" y="655" class="muted">writing, product</text>


  <!-- ========================================================= -->
  <!-- GITHUB STATS                                                -->
  <!-- ========================================================= -->

  <text x="640" y="720" class="text large">github stats</text>
  <line x1="800" y1="714" x2="1480" y2="714" class="line"/>

  <text x="640" y="760" class="key">repositories</text>
  <text x="820" y="760" class="muted">:</text>
  <text x="850" y="760" class="value" id="repo_data">42</text>

  <text x="640" y="785" class="key">commits</text>
  <text x="820" y="785" class="muted">:</text>
  <text x="850" y="785" class="value" id="commit_data">1,287</text>

  <text x="640" y="810" class="key">stars</text>
  <text x="820" y="810" class="muted">:</text>
  <text x="850" y="810" class="value" id="star_data">342</text>

  <text x="640" y="835" class="key">followers</text>
  <text x="820" y="835" class="muted">:</text>
  <text x="850" y="835" class="value" id="follower_data">196</text>

  <text x="640" y="860" class="key">lines of code</text>
  <text x="820" y="860" class="muted">:</text>
  <text x="850" y="860" class="value" id="loc_data">446,276</text>

  <text x="1010" y="860" class="green" id="loc_add">523,178++</text>
  <text x="1140" y="860" class="red" id="loc_del">76,902--</text>


  <!-- contribution mini graph -->

  <text x="1260" y="750" class="muted small">contributions</text>

  <g id="contribution_graph">
    <rect x="1260" y="770" width="9" height="9" rx="2" class="dim"/>
    <rect x="1278" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1296" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1314" y="770" width="9" height="9" rx="2" class="dim"/>
    <rect x="1332" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1350" y="770" width="9" height="9" rx="2" class="dim"/>
    <rect x="1368" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1386" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1404" y="770" width="9" height="9" rx="2" class="dim"/>
    <rect x="1422" y="770" width="9" height="9" rx="2" class="green"/>
    <rect x="1440" y="770" width="9" height="9" rx="2" class="green"/>

    <rect x="1260" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1278" y="790" width="9" height="9" rx="2" class="dim"/>
    <rect x="1296" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1314" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1332" y="790" width="9" height="9" rx="2" class="dim"/>
    <rect x="1350" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1368" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1386" y="790" width="9" height="9" rx="2" class="dim"/>
    <rect x="1404" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1422" y="790" width="9" height="9" rx="2" class="green"/>
    <rect x="1440" y="790" width="9" height="9" rx="2" class="green"/>

    <rect x="1260" y="810" width="9" height="9" rx="2" class="dim"/>
    <rect x="1278" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1296" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1314" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1332" y="810" width="9" height="9" rx="2" class="dim"/>
    <rect x="1350" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1368" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1386" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1404" y="810" width="9" height="9" rx="2" class="dim"/>
    <rect x="1422" y="810" width="9" height="9" rx="2" class="green"/>
    <rect x="1440" y="810" width="9" height="9" rx="2" class="green"/>
  </g>


  <!-- ========================================================= -->
  <!-- CONTACT                                                     -->
  <!-- ========================================================= -->

  <text x="640" y="885" class="text">contact</text>
  <line x1="735" y1="879" x2="1370" y2="879" class="line"/>

  <text x="1390" y="885" class="muted">let's make cool things.</text>

</svg>
