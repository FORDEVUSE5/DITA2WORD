# Antenna House AH-WML plug-in


$$
\begin{equation}
ddy=
\begin{cases}
0, & x[i]==0,\\
-ddx[i] & x \lt 0, \\
ddx[i] & x \gt 0 \\
\end{cases}
\end{equation}
$$


$$
ddy=\begin{cases}
0,&\text{ }x[i]==0,\\
-ddx[i]&\text{ }x<0,\\
ddx[i]&\text{ }x>0
\end{cases}
$$


















$$
\begin{align*}
&dst' = \mathrm{saturate\_cast<float>} (src_A \times w_{alpha} + src_B \times w_{beta} + b_{gamma})
\\
&dst = \mathrm{max}(v_{min}, \mathrm{min}(dst', v_{max}))
\end{align*}
$$



## Requirements ##

* DITA-OT 2.3 or later
* Saxon-PE/EE 9.8 or later
* JRE 9.0 or later

## Features ##

* Supported images: GIF, PNG, JPEG, TIFF, EMF, SVG (Word 2016 or later) 
* CALS table rendering
* Standard DITA elements, &lt;p&gt;, &lt;ul&gt;, &lt;ol&gt;, &lt;dl&gt;, &lt;pre&gt;

## Example ##

![Table formatting](./image/table-span.png)

## How to run this plug-in ##

Fork or clone this repository and copy com.antennahouse.wml folder to your \[DITA-OT\]/plugins folder.

From the command-line window at your \[DITA-OT\] folder, run `bin/dita --install` command.

## How to run this plug-in ##

Refer to mHowToRunAhWmlPlugInWithSaxonPeEe.docx for details.

## Notes ##

This project is still work in progress. Many DITA features are not implemented. Please submit your requests to issue list.

## Copyright ##

Copyright (C) 2009-2020 Antenna House, Inc. All rights reserved.
Antenna House is a trademark of [Antenna House, Inc.](http://www.antennahouse.com)

## License ##

This software is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
