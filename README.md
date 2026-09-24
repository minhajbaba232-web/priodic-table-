# priodic-table- 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Periodic Table</title>

<style>
    body {
        font-family: Arial, sans-serif;
        background: #111827;
        color: white;
        text-align: center;
        margin: 20px;
    }

    h1 {
        margin-bottom: 25px;
    }

    .table {
        display: grid;
        grid-template-columns: repeat(18, 1fr);
        gap: 5px;
        max-width: 1200px;
        margin: auto;
    }

    .element {
        min-height: 75px;
        padding: 6px;
        border-radius: 8px;
        background: #2563eb;
        cursor: pointer;
        transition: 0.2s;
        box-sizing: border-box;
    }

    .element:hover {
        transform: scale(1.08);
        background: #7c3aed;
    }

    .number {
        font-size: 11px;
        text-align: left;
    }

    .symbol {
        font-size: 25px;
        font-weight: bold;
    }

    .name {
        font-size: 10px;
    }

    .empty {
        visibility: hidden;
    }

    @media(max-width: 800px) {
        .table {
            gap: 3px;
        }

        .element {
            min-height: 55px;
            padding: 3px;
        }

        .symbol {
            font-size: 16px;
        }

        .name {
            font-size: 7px;
        }
    }
</style>
</head>

<body>

<h1>🧪 Periodic Table of Elements</h1>

<div class="table">

<!-- Period 1 -->
<div class="element"><div class="number">1</div><div class="symbol">H</div><div class="name">Hydrogen</div></div>
<div class="empty" style="grid-column: span 16;"></div>
<div class="element"><div class="number">2</div><div class="symbol">He</div><div class="name">Helium</div></div>

<!-- Period 2 -->
<div class="element"><div class="number">3</div><div class="symbol">Li</div><div class="name">Lithium</div></div>
<div class="element"><div class="number">4</div><div class="symbol">Be</div><div class="name">Beryllium</div></div>
<div class="empty" style="grid-column: span 10;"></div>
<div class="element"><div class="number">5</div><div class="symbol">B</div><div class="name">Boron</div></div>
<div class="element"><div class="number">6</div><div class="symbol">C</div><div class="name">Carbon</div></div>
<div class="element"><div class="number">7</div><div class="symbol">N</div><div class="name">Nitrogen</div></div>
<div class="element"><div class="number">8</div><div class="symbol">O</div><div class="name">Oxygen</div></div>
<div class="element"><div class="number">9</div><div class="symbol">F</div><div class="name">Fluorine</div></div>
<div class="element"><div class="number">10</div><div class="symbol">Ne</div><div class="name">Neon</div></div>

<!-- Period 3 -->
<div class="element"><div class="number">11</div><div class="symbol">Na</div><div class="name">Sodium</div></div>
<div class="element"><div class="number">12</div><div class="symbol">Mg</div><div class="name">Magnesium</div></div>
<div class="empty" style="grid-column: span 10;"></div>
<div class="element"><div class="number">13</div><div class="symbol">Al</div><div class="name">Aluminium</div></div>
<div class="element"><div class="number">14</div><div class="symbol">Si</div><div class="name">Silicon</div></div>
<div class="element"><div class="number">15</div><div class="symbol">P</div><div class="name">Phosphorus</div></div>
<div class="element"><div class="number">16</div><div class="symbol">S</div><div class="name">Sulfur</div></div>
<div class="element"><div class="number">17</div><div class="symbol">Cl</div><div class="name">Chlorine</div></div>
<div class="element"><div class="number">18</div><div class="symbol">Ar</div><div class="name">Argon</div></div>

<!-- Period 4 -->
<div class="element"><div class="number">19</div><div class="symbol">K</div><div class="name">Potassium</div></div>
<div class="element"><div class="number">20</div><div class="symbol">Ca</div><div class="name">Calcium</div></div>
<div class="element"><div class="number">21</div><div class="symbol">Sc</div><div class="name">Scandium</div></div>
<div class="element"><div class="number">22</div><div class="symbol">Ti</div><div class="name">Titanium</div></div>
<div class="element"><div class="number">23</div><div class="symbol">V</div><div class="name">Vanadium</div></div>
<div class="element"><div class="number">24</div><div class="symbol">Cr</div><div class="name">Chromium</div></div>
<div class="element"><div class="number">25</div><div class="symbol">Mn</div><div class="name">Manganese</div></div>
<div class="element"><div class="number">26</div><div class="symbol">Fe</div><div class="name">Iron</div></div>
<div class="element"><div class="number">27</div><div class="symbol">Co</div><div class="name">Cobalt</div></div>
<div class="element"><div class="number">28</div><div class="symbol">Ni</div><div class="name">Nickel</div></div>
<div class="element"><div class="number">29</div><div class="symbol">Cu</div><div class="name">Copper</div></div>
<div class="element"><div class="number">30</div><div class="symbol">Zn</div><div class="name">Zinc</div></div>
<div class="element"><div class="number">31</div><div class="symbol">Ga</div><div class="name">Gallium</div></div>
<div class="element"><div class="number">32</div><div class="symbol">Ge</div><div class="name">Germanium</div></div>
<div class="element"><div class="number">33</div><div class="symbol">As</div><div class="name">Arsenic</div></div>
<div class="element"><div class="number">34</div><div class="symbol">Se</div><div class="name">Selenium</div></div>
<div class="element"><div class="number">35</div><div class="symbol">Br</div><div class="name">Bromine</div></div>
<div class="element"><div class="number">36</div><div class="symbol">Kr</div><div class="name">Krypton</div></div>

<!-- Period 5 -->
<div class="element"><div class="number">37</div><div class="symbol">Rb</div><div class="name">Rubidium</div></div>
<div class="element"><div class="number">38</div><div class="symbol">Sr</div><div class="name">Strontium</div></div>
<div class="element"><div class="number">39</div><div class="symbol">Y</div><div class="name">Yttrium</div></div>
<div class="element"><div class="number">40</div><div class="symbol">Zr</div><div class="name">Zirconium</div></div>
<div class="element"><div class="number">41</div><div class="symbol">Nb</div><div class="name">Niobium</div></div>
<div class="element"><div class="number">42</div><div class="symbol">Mo</div><div class="name">Molybdenum</div></div>
<div class="element"><div class="number">43</div><div class="symbol">Tc</div><div class="name">Technetium</div></div>
<div class="element"><div class="number">44</div><div class="symbol">Ru</div><div class="name">Ruthenium</div></div>
<div class="element"><div class="number">45</div><div class="symbol">Rh</div><div class="name">Rhodium</div></div>
<div class="element"><div class="number">46</div><div class="symbol">Pd</div><div class="name">Palladium</div></div>
<div class="element"><div class="number">47</div><div class="symbol">Ag</div><div class="name">Silver</div></div>
<div class="element"><div class="number">48</div><div class="symbol">Cd</div><div class="name">Cadmium</div></div>
<div class="element"><div class="number">49</div><div class="symbol">In</div><div class="name">Indium</div></div>
<div class="element"><div class="number">50</div><div class="symbol">Sn</div><div class="name">Tin</div></div>
<div class="element"><div class="number">51</div><div class="symbol">Sb</div><div class="name">Antimony</div></div>
<div class="element"><div class="number">52</div><div class="symbol">Te</div><div class="name">Tellurium</div></div>
<div class="element"><div class="number">53</div><div class="symbol">I</div><div class="name">Iodine</div></div>
<div class="element"><div class="number">54</div><div class="symbol">Xe</div><div class="name">Xenon</div></div>

<!-- Period 6 -->
<div class="element"><div class="number">55</div><div class="symbol">Cs</div><div class="name">Cesium</div></div>
<div class="element"><div class="number">56</div><div class="symbol">Ba</div><div class="name">Barium</div></div>
<div class="element"><div class="number">57-71</div><div class="symbol">La-Lu</div><div class="name">Lanthanides</div></div>
<div class="element"><div class="number">72</div><div class="symbol">Hf</div><div class="name">Hafnium</div></div>
<div class="element"><div class="number">73</div><div class="symbol">Ta</div><div class="name">Tantalum</div></div>
<div class="element"><div class="number">74</div><div class="symbol">W</div><div class="name">Tungsten</div></div>
<div class="element"><div class="number">75</div><div class="symbol">Re</div><div class="name">Rhenium</div></div>
<div class="element"><div class="number">76</div><div class="symbol">Os</div><div class="name">Osmium</div></div>
<div class="element"><div class="number">77</div><div class="symbol">Ir</div><div class="name">Iridium</div></div>
<div class="element"><div class="number">78</div><div class="symbol">Pt</div><div class="name">Platinum</div></div>
<div class="element"><div class="number">79</div><div class="symbol">Au</div><div class="name">Gold</div></div>
<div class="element"><div class="number">80</div><div class="symbol">Hg</div><div class="name">Mercury</div></div>
<div class="element"><div class="number">81</div><div class="symbol">Tl</div><div class="name">Thallium</div></div>
<div class="element"><div class="number">82</div><div class="symbol">Pb</div><div class="name">Lead</div></div>
<div class="element"><div class="number">83</div><div class="symbol">Bi</div><div class="name">Bismuth</div></div>
<div class="element"><div class="number">84</div><div class="symbol">Po</div><div class="name">Polonium</div></div>
<div class="element"><div class="number">85</div><div class="symbol">At</div><div class="name">Astatine</div></div>
<div class="element"><div class="number">86</div><div class="symbol">Rn</div><div class="name">Radon</div></div>

<!-- Period 7 -->
<div class="element"><div class="number">87</div><div class="symbol">Fr</div><div class="name">Francium</div></div>
<div class="element"><div class="number">88</div><div class="symbol">Ra</div><div class="name">Radium</div></div>
<div class="element"><div class="number">89-103</div><div class="symbol">Ac-Lr</div><div class="name">Actinides</div></div>
<div class="element"><div class="number">104</div><div class="symbol">Rf</div><div class="name">Rutherfordium</div></div>
<div class="element"><div class="number">105</div><div class="symbol">Db</div><div class="name">Dubnium</div></div>
<div class="element"><div class="number">106</div><div class="symbol">Sg</div><div class="name">Seaborgium</div></div>
<div class="element"><div class="number">107</div><div class="symbol">Bh</div><div class="name">Bohrium</div></div>
<div class="element"><div class="number">108</div><div class="symbol">Hs</div><div class="name">Hassium</div></div>
<div class="element"><div class="number">109</div><div class="symbol">Mt</div><div class="name">Meitnerium</div></div>
<div class="element"><div class="number">110</div><div class="symbol">Ds</div><div class="name">Darmstadtium</div></div>
<div class="element"><div class="number">111</div><div class="symbol">Rg</div><div class="name">Roentgenium</div></div>
<div class="element"><div class="number">112</div><div class="symbol">Cn</div><div class="name">Copernicium</div></div>
<div class="element"><div class="number">113</div><div class="symbol">Nh</div><div class="name">Nihonium</div></div>
<div class="element"><div class="number">114</div><div class="symbol">Fl</div><div class="name">Flerovium</div></div>
<div class="element"><div class="number">115</div><div class="symbol">Mc</div><div class="name">Moscovium</div></div>
<div class="element"><div class="number">116</div><div class="symbol">Lv</div><div class="name">Livermorium</div></div>
<div class="element"><div class="number">117</div><div class="symbol">Ts</div><div class="name">Tennessine</div></div>
<div class="element"><div class="number">118</div><div class="symbol">Og</div><div class="name">Oganesson</div></div>

</div>

</body>
</html>
