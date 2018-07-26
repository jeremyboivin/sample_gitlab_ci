# How works CI with gitlab ?

This repository concerns uniquely `gitlab` (for the moment obviously).<br />
Onto this repository, we'll see 4 stages :<br />
<ul>
	<li>syntax : to check syntax before merge a specific branch into develop</li>
	<li>test : to run specific tests (here python and shell tests are available, but anyway exists into differents programming languages) such as unit, functional and more of them</li>
	<li>build : to make a package such as debian (.deb) and more</li>
	<li>deploy : to send a built package onto (pre)production server for example</li>
</ul>
