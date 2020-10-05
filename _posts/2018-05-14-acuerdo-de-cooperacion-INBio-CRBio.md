---
title: Firma del Acuerdo de Cooperación entre INBio y CRBio
date: 2018-05-14 17:27:15 +0200
description: Firma del Convenio General de Cooperación mutua para el desarrollo de proyectos.
background: "assets/img/Convenio INBio - CRBio.JPG"
author: [Ronny Hernández]
categories: [" Socios "]
---


<script type="text/javascript"> 

function horaLocal(hileraFechaHora, addDay) {
// The function convert the parameter ISO Date string to the local hour HH:MM.
// If addDay = 1 then A "(+1 day)" is added in another line.
  var fecha = new Date(hileraFechaHora);   
  var horas = fecha.getHours();
  var minutos = fecha.getMinutes();
  
  if (horas < 10) {
     horas = "0" + horas.toString();
  }
  if (minutos < 10) {
     minutos = "0" + minutos.toString();
  }
  
  shiftDays = 0;
  shifted = "";
  if (addDay == 1) {
    shiftDays = fecha.getDate() - parseInt(hileraFechaHora.substr(hileraFechaHora.search("T")-2,2),10);
    if (shiftDays > 0) {
      shifted = "<br>"+"+1 day";
    } else {
      if (shiftDays < 0) {
        shifted = "<br>"+"-1 day";
      }
    }
  }
  return horas + ":" + minutos + shifted;
}
function UTCZonaHorariaLocal(hileraFechaHora, addlinebreak) {
  // The function convert the parameter UTC ISO Date string to the local time.
  // Use addlinebreak to indicate a new line (1), a space (0) between "UTC" and the sign of the time.
  var fecha = new Date(hileraFechaHora);    

  var desfase = fecha.getTimezoneOffset();
  var signo = "+";
  
  if (desfase < 0) { signo = "+"; } else { signo = "-"; }
  desfase = Math.abs(desfase);
  var horas = Math.trunc(desfase/60);
  var minutos = Math.trunc(desfase - (horas * 60));
  
  if (horas < 9) {horas = "0" + horas};
  if (minutos < 9) {minutos = "0"+ minutos};
  if (addlinebreak == 1) { 
    linebreak = "<br>"; 
  } else { 
    if (addlinebreak == 0) {
      linebreak = " "; 
    } else { 
      linebreak = ""; 
    } 
  }
  return ("UTC" + linebreak + signo) + (horas + ":" + minutos);
}

function DiaLocal(hileraFechaHora, lineas, formatoDia, formatoMes, localidad) {
  // The function convert the parameter ISO Date string to the day string.
  // lineas indicates if the result is more than 1 line (No:0, Yes:1)
  var fecha = new Date(hileraFechaHora);
  var nombreDia = fecha.toLocaleDateString(localidad, { weekday: formatoDia });
  var nombreMes = fecha.toLocaleDateString(localidad, { month: formatoMes });
  if (lineas == 1) {
    nombreDia = nombreDia + "<br>";
  } else {
    nombreDia = nombreDia + " ";
  }
  nombreDia = nombreDia + fecha.getDate() + " " + nombreMes;
  return nombreDia;
}
</script>

<script type="text/javascript">
  let showDay = 1;
  document.write( UTCZonaHorariaLocal('2018-10-19T23:00:00Z', -1) );
</script>

El 14 de Junio del 2018, María Auxiliadora Mora, Presidenta de CRBio y Randall García, Director General del INBio, firmaron un Convenio General de Cooperación mutua para el desarrollo de proyectos que contribuyan al <b>cumplimiento</b> de los objetivos de ambos.

<span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+Attention%3a%20Local%20Time&iso=20200922T0800&p1=1440&ah=2&am=" target="_blank">
    Local Time: 
      <script type="text/javascript">
        let hileraFechaHora = "2018-10-19T23:00:00Z";
        document.write( DiaLocal(hileraFechaHora, 0, 'short', 'short', 'en-US')+" "+ horaLocal(hileraFechaHora, 0));
      </script>
      
  </a>
  </strong>
</span>

Los representantes de ambas instituciones acordaron unir esfuerzos, recursos y conocimientos científicos y técnicos para desarrollar acciones conjuntas de investigación, desarrollo de tecnología informática, fortalecimiento de capacidades y publicación libre y gratuita de información sobre biodiversidad con la finalidad de contribuir a la conservación, acrecentar el conocimiento y promover la utilización sostenible de la biodiversidad, según las leyes aplicables.



# Draft Conference Schedule, Oct 19-23

The times posted for events below (in <script type="text/javascript"> document.write( UTCZonaHorariaLocal('2020-10-19T00:00:00Z', 2) ); </script>) are nearly final, but some confirmations are still pending so changes are still possible.
<script type="text/javascript"> 
  // Some configuration variables
  let breakUTCLine = 1;
  let breakLocalDayLine = 1;
  let weekOfDayFormat = 'long';
  let monthFormat = 'short';
  let localLocale = 'en-US';
  let showDayShift = 1;
</script>

<table style="border-collapse: collapse" border="1px">
<tbody>
<tr style="border-style: double;">
<td style="vertical-align: bottom; text-align:center;">Time
  <script type="text/javascript">
    document.write( UTCZonaHorariaLocal('2020-10-19T00:00:00Z', breakUTCLine) );
  </script>
</td>
<td align="center" valign="top"><strong>
  Monday<br />Oct. 19
<!--- <script type="text/javascript">document.write( DiaLocal('2020-10-19T00:00:00Z', breakLocalDayLine, weekOfDayFormat, monthFormat, localLocale) );</script> --->
  <br /> </strong>
</td>
<td align="center" valign="top"><strong>
  Tuesday<br />Oct. 20
<!---  <script type="text/javascript">document.write( DiaLocal('2020-10-20T00:00:00Z', breakLocalDayLine, weekOfDayFormat, monthFormat, localLocale) );</script> --->
<br /> </strong></td>
<td align="center" valign="top"><strong>
  Wednesday<br />Oct. 21
<!---  <script type="text/javascript">document.write( DiaLocal('2020-10-21T00:00:00Z', breakLocalDayLine, weekOfDayFormat, monthFormat, localLocale) );</script> --->
  <br /> </strong></td>
<td align="center" valign="top"><strong>
  Thursday<br />Oct. 22
<!---  <script type="text/javascript">document.write( DiaLocal('2020-10-22T00:00:00Z', breakLocalDayLine, weekOfDayFormat, monthFormat, localLocale) );</script> --->
  <br /> </strong></td>
<td align="center" valign="top"><strong>
  Friday<br />Oct. 23
<!---  <script type="text/javascript">document.write( DiaLocal('2020-10-23T00:00:00Z', breakLocalDayLine, weekOfDayFormat, monthFormat, localLocale) );</script> --->
  </strong></td>
</tr>
<tbody valign="top">
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T00:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T00:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T01:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td style="background-color: #ECEEAC;" rowspan="3"><p><a href="../session-list/#pd02%20the%20biocultural%20labels%20initiative:%20supporting%20indigenous%20rights%20in%20data%20derived%20from%20genetic%20resources">PD02: The Biocultural labels initiative: supporting indigenous rights in data derived from genetic resources</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+PD02%3A%20The%20Biocultural%20labels%20initiative&iso=20201020T0100&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-20T01:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T01:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td style="background-color: #ECEEAC;" rowspan="4"><p><a href="../session-list/#pd01%20avenues%20into%20integration:%20communicating%20taxonomic%20intelligence%20from%20sender%20to%20recipient">PD01: Avenues into integration: communicating taxonomic intelligence from sender to recipient</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+PD01%3A%20Avenues%20into%20integration&iso=20201023T0130&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-23T01:30:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T02:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T02:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T03:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T03:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T04:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T04:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T05:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T05:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T06:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T06:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T07:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td style="background-color: #c8add8;" rowspan="2"><p>Social Hour?</p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+Social%20Hour&iso=20201020T0700&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-20T07:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T07:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T08:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T08:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td style="background-color: #acdfee;" rowspan="4"><p><a href="../session-list/#co04%20contributed%20oral%204">CO4: Contributed Oral 4</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+CO04%3A%20Contributed%20Oral%204&iso=20201023T0830&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-23T08:30:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T09:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T09:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T10:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T10:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T11:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T11:30:00Z', showDayShift) );
  </script>  
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td style="background-color: #acdfee;" rowspan="4"><p><a href="../session-list/#co05%20contributed%20oral%205">CO5: Contributed Oral 5</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+CO05%3A%20Contributed%20Oral%205&iso=20201023T1130&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-23T11:30:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T12:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T12:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T13:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T13:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T14:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td style="background-color: #C3EEAC;" rowspan="4"><p><a href="../session-list/#sym02%20use%20and%20re-use%20of%20images%20and%20their%20metadata%20in%20biodiversity%20research">SYM02: Use and re-use of images and their metadata in biodiversity research</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+SYM02%3A%20Use%20and%20Re-use%20of%20%20images%20and%20their%20metadata%20in%20biodiversity%20research&iso=20201020T1400&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-20T14:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
<td style="background-color: #C3EEAC;" rowspan="4"><p><a href="../session-list/#sym09%20technical%20and%20standards%20implications%20in%20data%20liberation%20and%20semantic%20publishing%20for%20biodiversity">SYM09: Technical standards implications in data liberation and semantic publishing for biodiversity</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+SYM09%3A%20Technical%20standards%20implications%20in%20data%20liberation%20and%20semantic%20publishing%20for%20biodiversity&iso=20201021T1400&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-21T14:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
<td style="background-color: #C3EEAC;" rowspan="3"><p><a href="../session-list/#sym01%20standards%20alignment:%20which%20and%20how?">SYM01: Standards alignment: which and how?</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+SYM01%3A%20Standards%20alignment%3F%20which%20and%20how%3F&iso=20201022T1400&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-22T14:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
<td style="background-color: #ECEEAC;" rowspan="3"><p><a href="../session-list/#pd03%20enabling%20digital%20specimen%20and%20extended%20specimen%20concepts%20in%20current%20tools%20and%20services">PD03: Enabling digital specimen and extended specimen concepts in current tools and services</a></p>
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+PD03%3A%20Enabling%20digital%20specimen%20and%20extended%20specimen%20concepts%20in%20current%20tools%20and%20services&iso=20201023T1400&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-23T14:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-20T01:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </span>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T14:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T15:00:00Z', showDayShift) );
  </script>
</td>
<td style="background-color: #EEACEC;" rowspan="2">
  Conference welcome and Keynote by<br />Scott Edwards<br />
  <span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+Conference%20welcome%20and%20Keynote&iso=20201019T1500&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-19T15:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-19T15:00:00Z", 0) ); --->
      </script>
    </a></strong></span>
  </td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T15:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T16:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T16:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T17:00:00Z', showDayShift) );
  </script>
</td>
<td style="background-color: #acdfee;" rowspan="4"><p><a href="../session-list/#co02%20contributed%20oral%202">CO2: Contributed Oral 2</a></p></td>
<td style="background-color: #C3EEAC;" rowspan="3"><p><a href="../session-list/#sym07%20new%20standards%20development%20to%20support%20the%20transformation%20of%20collection%20data%20into%20digital%20specimens">SYM07: New Standards development to support the transformation of collection data into digital specimens</a></p></td>
<td style="background-color: #C3EEAC;" rowspan="4"><p><a href="../session-list/#sym04%20challenges%20of%20the%20alignment%20of%20collection%20management%20systems%20across%20the%20globe%20and%20different%20domains">SYM04: Challenges of the alignment of collection management systems across the globe and different domains</a></p></td>
<td style="background-color: #acdfee;" rowspan="4"><p><a href="../session-list/#co03%20contributed%20oral%203">CO3: Contributed Oral 3</a></p></td>
<td style="background-color: #C3EEAC;" rowspan="3"><p><a href="../session-list/#sym05%20using%20collections%20to%20mitigate%20and%20prevent%20zoonotic%20disease:%20data%20mobilization%20and%20integration">SYM05: Using collections to mitigate and prevent zoonotic disease: data mobilization and integration</a></p></td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T17:30:00Z', showDayShift) );
  </script>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T18:00:00Z', showDayShift) );
  </script>
</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T18:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T19:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T19:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T20:00:00Z', showDayShift) );
  </script>
</td>
<td style="background-color: #C3EEAC;" rowspan="4"><p><a href="../session-list/#sym06%20you%20have%20what%20in%20your%20collection?">SYM06: You've got what in your collection?</a></p></td>
<td style="background-color: #C3EEAC;" rowspan="3"><p><a href="../session-list/#sym03%20enhancing%20connections%20with%20the%20global%20neighbourhood%20through%20expanding%20partnerships">SYM03: Enhancing connections with the global neighbourhood through expanding partnerships</a></p></td>
<td style="background-color: #C3EEAC;" rowspan="3"><p><a href="../session-list/#sym08%20introduction%20to%20the%20new%20living%20atlases%20community">SYM08: Introduction to the new Living Atlases community</a></p></td>
  <td style="background-color: #EEACEC;" rowspan="4">
    <p>Keynote by<br />
    Ken-Ichi Ueda</p>
    <p style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+Mid%20Conference%20Keynote&iso=20201022T2200&p1=1440&ah=2&am=" target="_blank"> 
      <script type="text/javascript">
        document.write( DiaLocal("2020-10-22T22:00:00Z", 0, "short", "short", "en-US") );
<!---        document.write(" "); document.write( horaLocal("2020-10-22T22:00:00Z", 0) ); --->
      </script>
    </a></strong>
  </p>
  <p style="font-size:50%; text-align:center; background-color:white">&nbsp;&nbsp;5 min break&nbsp;&nbsp;</p>
  <p>TDWG Business Meeting</p>
</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T20:30:00Z', showDayShift) );
  </script>
</td>
<td style="background-color: #c8add8;" rowspan="2">Closing social session</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T21:00:00Z', showDayShift) );
  </script>
</td>
<!---<td>&nbsp; style="background-color: #d8c3ad;" rowspan="3" --->
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T21:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T22:00:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td style="background-color: #acdfee;" rowspan="3"><p><a href="../session-list/#co01%20contributed%20oral%201">CO1: Contributed Oral 1</a></p></td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T22:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T23:00:00Z', showDayShift) );
  </script>
</td>
<td style="background-color: #c8add8;" rowspan="2">Social Hour?</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>
  <script type="text/javascript">
    document.write( horaLocal('2020-10-19T23:30:00Z', showDayShift) );
  </script>
</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>  








