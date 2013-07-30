MojoShare
=========

All vector-based social buttons in one place


<h2>About</h2>
<ul>
    <li>Full vector icons by @font-face MojoSocial</li>
    <li>Support for more than 40 services and their brand colors</li>
    <li>Icon font use private unicode spaces for accessibility</li>
    <li>Useful LESS styles for customize buttons</li>
    <li>Different types of buttons: square, circle, minimalism</li>
    <li>Works splendidly on any browser supporting @font-face</li>
    <li><a href="https://github.com/Pestov/MojoRibbon">Mojo Ribbon</a> - geometrically correct LESS ribbon </li>
</ul>

Demo: http://netcribe.com/MojoShare/

##Usage

      <div class="MojoShare"> <!-- for note duplicate this class for every element -->
         <a class="[ServiceName] [Type: auth/share] [Style: none/square/circle/minimalism]">Share!</a>
      </div>
Type classes - auth/share are customize style for base button properties: size, font, position and others.
Style clases - square/circle/minimalism are MojoShare's set of designs buttons.

##Example

      <a class="Facebook share circle"></a>
