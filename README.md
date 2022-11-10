<h1 id='DUfACAaHxVP'>A-HLS - DataRaptor Library - DRUpdateContract Documentation</h1>

<i>This DataRaptor acts as a base for developers to update existing contracts quickly.</i><br/>

<hr style='width:100%'><h2 id='DUfACAT8M3H'>Overview</h2>

A DataRaptor is a mapping tool to help read, transform, and write Salesforce data. There are four types of DataRaptors: <span style="color:#1e1e1c" textcolor="#1e1e1c">Turbo Extract, Extract, Load, and Transform. You can use these four methods to extract data for digital customer interactions and business processes to present data. </span><br/>

<br/>

This Data Raptor Load updates an existing Contract.<br/>

<hr style='width:100%'><h2 id='DUfACAyJCAh'>Business Objective</h2>

The Business objective is to provide a contract for the provider to be held accountable. <br/>

<h2 id='DUfACAKe2tj'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div data-section-style='5' class="" style=""><ul id='DUfACALTZ59'><li id='temp:C:DUf48f6afe5d5874f3ca6bb5b90e' class='' value='1'><span style="color:#0e101a" textcolor="#0e101a">Decrease IT costs associated with custom build</span>

<br/></li><li id='temp:C:DUf307aad11f3e64465ac9031098' class=''>Improve user experience

<br/></li></ul></div><hr style='width:100%'><h2 id='DUfACAI1r3X'>Export-Package Includes</h2>

<h3 id='DUfACAijDy8'><b>DataRaptor (1)</b></h3>

<div data-section-style='5' class="" style=""><ul id='DUfACA7BD6a'><li id='DUfACA2BTBG' class='' value='1'>DRUpdateContract

<br/></li></ul></div><h2 id='DUfACAGedPT'><b>Input JSON Reference</b></h2>

<div data-section-style='5' class="" style=""><ul id='DUfACA2Kt0Z'><li id='DUfACAaLyFu' class='' value='1'>{<br>    "Contract": {<br>        "Id": "xxxxxxxxxxx",<br>        "Name": "xxxxxxxxxxx",<br>        "AccountId": "xxxxxxxxxxx",<br>        "ContractTerm": xx,<br>        "StartDate": "yyyy-mm-dd",<br>        "Pricebook2Id": "xxxxxxxxxxx",<br>        "SpecialTerms": "xxxxxxxxxxx",<br>        "CompanySignedId": "xxxxxxxxxxx",<br>        "CustomerSignedId": "xxxxxxxxxxx",<br>        "CustomerSignedTitle": "xxxxxxxxxxx",<br>        "CompanySignedDate": "yyyy-mm-dd",<br>        "CustomerSignedDate": "yyyy-mm-dd"<br>    }<br>}

<br/></li></ul></div><hr style='width:100%'><h2 id='DUfACAn1vvl'>Configuration Requirements</h2>

<h3 id='temp:C:DUfddcfab02fe954cdeb54a25e49'>Configuration Instructions:</h3>

<div data-section-style='5' class="" style=""><ul id='temp:C:DUf3d204437c13e497c9c63fc54e'><li id='temp:C:DUf86cb7d965244429eace5b0e8c' class='' value='1'>The Data Raptor is ready to be imported and customized. No further base configuration requirements are necessary.

<br/></li></ul></div><h3 id='temp:C:DUf832a3ec9f4f4438c837bb6992'>Install the Data Pack</h3>

<div class="" style="" data-section-style='6'><ul id='DUfACAKkDej'><li id='DUfACAZJSjg' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRUpdateContract">https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRUpdateContract</a>

<br/></li><li id='DUfACAnjiOW' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='DUfACASlSyA' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='DUfACAVrPgH' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='DUfACA92rDy' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul><li id='DUfACA42u9a' class=''>More about DataRaptors: <a href="https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors">https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors</a>

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:DUf9420136cd8b4465484641c240'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div data-section-style='5' class="" style=""><ul id='temp:C:DUf34250f7c8b4b4c28acc4e4822'><li id='temp:C:DUf6cfbe9f48b0647b28e925cc00' class='' value='1'>A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='temp:C:DUfca4686de6fe54bcbac847f0fb' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='temp:C:DUfd8a71833836f44999329fd1d9' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are available.

<br/></li><li id='temp:C:DUf7256a5e52f4a486589b57bd0d' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their branding.

<br/></li></ul></div><h2 id='DUfACAIV2ma'>Installed Packages Requirement</h2>

<div data-section-style='5' class="" style=""><ul id='DUfACAQkbs1'><li id='DUfACAGqe1J' class='' value='1'>HealthCloud (HealthCloudGA) - Version 236.1 or higher

<br/></li><li id='DUfACAfDiFv' class=''>Vlocity Insurance (vlocity_ins) - Version 890.317 or higher

<br/></li></ul></div><hr style='width:100%'><h2 id='DUfACAJi9Al'>Revision History</h2>

<div data-section-style='5' class="" style=""><ul id='DUfACAbdn1u'><li id='DUfACAeOuue' class='parent' value='1'><b>Revision Short Description (May 12, 2022)</b>

<br/></li><ul><li id='DUfACA021GH' class=''>Error correction from previous versions to adapt to the new Data Model.

<br/></li><li id='DUfACA4Lj0W' class=''>Initial export with QA.

<br/></li></ul><li id='DUfACA25AXU' class='parent'><b>Revision Short Description (June 21, 2022)</b>

<br/></li><ul><li id='DUfACAIOxTi' class=''>Updated Documentation.
