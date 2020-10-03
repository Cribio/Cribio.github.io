---
title: Firma del Acuerdo de Cooperación entre INBio y CRBio
date: 2018-05-14 17:27:15 +0200
description: Firma del Convenio General de Cooperación mutua para el desarrollo de proyectos.
background: "assets/img/Convenio INBio - CRBio.JPG"
author: [Ronny Hernández]
categories: [" Socios "]
---
<script type="text/javascript"> 
function UTCLocalTimeZone(hileraFechaHora, addlinebreak) {
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
  if (addlinebreak == 1) { linebreak = "<br>"; } else { if (addlinebreak == 0) {linebreak = " "; } else { linebreak = ""; }; };
  return ("UTC" + linebreak + signo) + (horas + ":" + minutos);
}

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
  if (addDay) {
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

function DiaLocal(hileraFechaHora, lineas, formatoDia, formatoMes, localidad) {
  // The function convert the parameter ISO Date string to the day string.
  // lineas indicates if the result is more than 1 line (No:0, Yes:1)
  var fecha = new Date(hileraFechaHora);
  var nombreDia = fecha.toLocaleDateString(localidad, { weekday: formatoDia });
  var nombreMes = fecha.toLocaleDateString(localidad, { month: formatoMes });
  if (lineas = 1) {
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
  document.write( UTCLocalTimeZone('2018-10-19T23:00:00Z', -1) );
</script>

El 14 de Junio del 2018, María Auxiliadora Mora, Presidenta de CRBio y Randall García, Director General del INBio, firmaron un Convenio General de Cooperación mutua para el desarrollo de proyectos que contribuyan al <b>cumplimiento</b> de los objetivos de ambos.

<span style="font-size:75%"><strong>
    <a href="https://www.timeanddate.com/worldclock/fixedtime.html?msg=TDWG+2020+-+Attention%3a%20Local%20Time&iso=20200922T0800&p1=1440&ah=2&am=" target="_blank">
    Local Time: 
      <script type="text/javascript">
        let hileraFechaHora = "2018-10-19T23:00:00Z"
        document.write( DiaLocal(hileraFechaHora, 0, 'short', 'short', 'en-US')+" "+ horaLocal(hileraFechaHora, 0));
      </script>
      
  </a></strong></span>

Los representantes de ambas instituciones acordaron unir esfuerzos, recursos y conocimientos científicos y técnicos para desarrollar acciones conjuntas de investigación, desarrollo de tecnología informática, fortalecimiento de capacidades y publicación libre y gratuita de información sobre biodiversidad con la finalidad de contribuir a la conservación, acrecentar el conocimiento y promover la utilización sostenible de la biodiversidad, según las leyes aplicables.







