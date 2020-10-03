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
  
  shifted = "";
  if (addDay) {
    shift = fecha.getDate() - hileraFechaHora.substr(9,2);
    if (shift > 0) {
      shifted = "<br>"+"-1 day";
    } else {
      if (shift < 0) {
        shifted = "<br>"+"+1 day";
      }
    }
  }
  return horas + ":" + minutos + shifted;
}
</script>


<script type="text/javascript">
  document.write( UTCLocalTimeZone('2018-06-14T08:00:00Z', -1) );
</script>

El 14 de Junio del 2018, María Auxiliadora Mora, Presidenta de CRBio y Randall García, Director General del INBio, firmaron un Convenio General de Cooperación mutua para el desarrollo de proyectos que contribuyan al <b>cumplimiento</b> de los objetivos de ambos.

<script type="text/javascript">
  document.write( horaLocal('2020-10-19T22:00:00Z', 1) );
</script>

Los representantes de ambas instituciones acordaron unir esfuerzos, recursos y conocimientos científicos y técnicos para desarrollar acciones conjuntas de investigación, desarrollo de tecnología informática, fortalecimiento de capacidades y publicación libre y gratuita de información sobre biodiversidad con la finalidad de contribuir a la conservación, acrecentar el conocimiento y promover la utilización sostenible de la biodiversidad, según las leyes aplicables.







