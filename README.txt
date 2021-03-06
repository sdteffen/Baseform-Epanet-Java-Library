////////////////////////////////////////////////////////////////
Baseform EpaNet Java Library 1.0 - 2012-02-02
////////////////////////////////////////////////////////////////

Baseform EpaNet Java Library is part of the Baseform EpaNet tool
<http://www.baseform.org/np4/tools/epanetTool.html>.

Baseform EpaNet Java Library is open-source and licensed under the GNU General Public License, or GPL.
See LICENSE.txt for detailed terms and conditions.

///////
FUNCTIONALITY
///////
The library contains the main port of USEPA <http://www.epa.gov/> EpaNet hydraulic and water quality modeling and
simulation toolkit <http://www.epa.gov/nrmrl/wswrd/dw/epanet.html>.
It also contains a port of the EPANET-MSX (Multi-Species eXtension) which adds complex reaction simulation capabilities
between multiple chemical and biological species in both the bulk flow and at the pipe wall.

This Java EpaNet implementation is feature-complete, representing a full port of the currently available versions of
EpaNet Toolkit (2.00.12 - 20/March/2008) and EpaNet MSX extension (1.1.00 - 08/Feb/2011).

The library adds to the original toolkit(s) by providing a more accessible, cross-platform, object-oriented
implementation; some changes have been made on the integration of hydraulic and quality simulation and on the range of
available input and output file formats, which now include:
 - regular .INP files (epanet and msx)
 - xls/xlsx .INP.XLSX files for direct excel versions of the full network model (easier for edit)
 - xml .INP.XML files for XML markup language versions of the full network model (easier to parse and manipulate
 by computers).

Aside from linking the library against your code, the library includes a command-line access mode via
(org.addition.epanet.EPATool) and a simple LaunchPad application for running Epanet and MSX simulations without having
to write any code (org.addition.epanet.ui.EpanetUI).


///////
USAGE/HOW-TO
///////
You can use the library by downloading the binary (jar, exe, or mac dmg app) on baseform.org, or by linking and
compiling this source code against your project.


///////
DEPENDENCIES
///////
EpaNet Java Library is self-contained. It uses or depends on these open-source libraries for identified
specific functionality:

- MSX expression parsing:
    JEPLite - JEP enlited - http://jeplite.sourceforge.net/

- XML input and output of the models
    XStream - http://xstream.codehaus.org/

- XLS/XLSX input and output (of the network and of simulation results)
    Apache POI "Poor Obfuscation Implementation" - http://poi.apache.org/

- User interface of the LaunchPad
    JGoodies Looks - http://www.jgoodies.com
    JetBrains Forms Runtime - http://www.jetbrains.com/