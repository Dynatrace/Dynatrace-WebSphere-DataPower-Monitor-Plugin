<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>WebSphere DataPower Monitor Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
                <h1>WebSphere DataPower Monitor Plugin</h1>
    <div class="section-2"  id="84279597_WebSphereDataPowerMonitorPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/84279597/icon.png" alt="images_community/download/attachments/84279597/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
This plugin enables monitoring of the WebSphere Data Power SOA Appliance. The plugin uses the XML Management interface as described in this PDF: <a href="attachments_84443192_1_SOMA_redp4446.pdf">SOMA_redp4446.pdf</a>    </p>
    </div>
    <div class="section-2"  id="84279597_WebSphereDataPowerMonitorPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">dynaTrace 4.x+</strong>:<br/><a href="attachments_116523207_1_com.dynatrace.diagnostics.plugin.DataPowerMonitor_4.2.0.3154.jar">WebSphere DataPower Monitor Plugin for dynaTrace 4.2+</a><br/><a href="attachments_103546906_1_com.dynatrace.diagnostics.plugin.DataPowerMonitor_4.1.0.3070.jar">WebSphere DataPower Monitor Plugin for 4.1</a><br/><a href="attachments_84443195_1_DataPowerDevice.dashboard.xml">Data Power Monitor Dashboard </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Noormohammed Sheikh (noor.sheikh@compuware.com)<br/> Chuck Miller (charles.miller@compuware.com)<br/> Jeffrey Fynboh (jeffrey.fynboh@compuware.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.1+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2012-06-25 1.0.1 Initial Release    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="84279597_WebSphereDataPowerMonitorPlugin-Dashboards"  >
        <h2>Dashboards</h2>
    <p>
The following image shows the attached dashboard including all metrics that the monitor provides:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/84279597/soma_dashboard.png" alt="images_community/download/attachments/84279597/soma_dashboard.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="84279597_WebSphereDataPowerMonitorPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the <a href="https://community.dynatrace.com/community/display/DOCDT41/Manage+and+Develop+Plugins#ManageandDevelopPlugins-ManageandDevelopPlugins">dynaTrace documentation</a>.    </p>
    </div>
    <div class="section-2"  id="84279597_WebSphereDataPowerMonitorPlugin-Configuration"  >
        <h2>Configuration</h2>
    <p>
            <img src="images_community/download/attachments/84279597/DataPowerConfiguration.jpg" alt="images_community/download/attachments/84279597/DataPowerConfiguration.jpg" class="" />
            </p>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Type    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Value    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Protocol    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
list    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
https    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Port    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
long    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
5550    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Soma Path    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
string    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
/service/mgmt/current    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
SOMA SOAP Envelope Template    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
string    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt;?xml version=&quot;1.0&quot; encoding=&quot;UTF-8&quot;?&gt;&lt;env:Envelope xmlns:env=&quot;http://schemas.xmlsoap.org/soap/envelope/&quot;&gt;&lt;env:Body&gt;&lt;dp:request domain=&quot;default&quot; xmlns:dp=&quot;http://www.datapower.com/schemas/management&quot;&gt;&lt;dp:get-status class=&quot;&lt;at:var at:name=&quot;SOMAMONITORCLASS&quot; /&gt;&quot;/&gt;&lt;/dp:request&gt;&lt;/env:Body&gt;&lt;/env:Envelope&gt;</code></pre>
        </div>
    </div>
    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
HTTP Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
list    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
User-Agent    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
string    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace/4    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Max. redirects    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
long    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Match Content	list    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Disabled    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Server authorization    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Boolean    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Check Box Selected    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Server Username    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
string    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The username to access data power device    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Server Password    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
string    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The password to access  data power device    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Proxy    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Boolean    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Check Box Unselected    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Disable certificate Veralidation    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
boolean    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Check Box Selected    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
