# How to setup and use ePursuit

# Quickstart #

  * Download and unzip ePursuit
  * Put Mr X and Agent numbers (SIP/.../Number) - one number per line - into files
  * Edit the epursuit.properties, to fit your Asterisk system (remember to record some sounds - gsm is the default format)
  * Start ePursuit: java -jar epursuit.jar /PATH/TO/epursuit.properties

# Commands #

<table border='1'>
<tr><td>call mrx</td><td>starts calling all Mr X</td></tr>
<tr><td>call test</td><td>calls the testnumber specified in the config and plays the same stuff, the agents get to hear</td></tr>
<tr><td>call agents</td><td>starts calling all agents (only use it after you have at least once called Mr X)</td></tr>
<tr><td>reload mrx</td><td>reloads Mr X list</td></tr>
<tr><td>reload agents</td><td>reloads Agent list</td></tr>
<tr><td>quit</td><td>guess what</td></tr>
</table>