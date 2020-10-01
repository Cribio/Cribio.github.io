---
title: Firma del Acuerdo de Cooperación entre INBio y CRBio
date: 2018-05-14 17:27:15 +0200
categories: [" Socios "]
---
<script type="text/javascript"> 

function horaLocal(hileraFechaHora) {
  var fecha = new Date(hileraFechaHora);   // The function convert the parameter ISO Date string to the local hour HH:MM.
  var horas = fecha.getHours();
  var minutos = fecha.getMinutes();
  
  if (horas < 10) {
     horas = "0" + horas.toString();
  }
  if (minutos < 10) {
     minutos = "0" + minutos.toString();
  }
  return horas + ":" + minutos;
}

function UTCLocal(hileraFechaHora) {
  var fecha = new Date(hileraFechaHora);    // The function convert the parameter ISO Date string to the UTC shift.
  var desfase = (0-fecha.getTimezoneOffset())/60;
  if (desfase > 0) {
     desfase = "+" + desfase.toString();
  } else {
     desfase = desfase.toString();
  }
  return "UTC"+desfase;
}

function DiaLocal(hileraFechaHora, lineas, fomatoDia, formatoMes, localidad) {
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

El 14 de Junio del 2018, María Auxiliadora Mora, Presidenta de CRBio y Randall García, Director General del INBio, firmaron un Convenio General de Cooperación mutua para el desarrollo de proyectos que contribuyan al <b>cumplimiento</b> de los objetivos de ambos.

<script type="text/javascript">
  var hileraDiaYHora = '2018-06-14T15:27:15Z';
  document.write( horaLocal(hileraDiaYHora)+'<br>' );
  document.write( UTCLocal(hileraDiaYHora)+ '<br>' );
  document.write( DiaLocal(hileraDiaYHora, 1, 'short', 'short', 'en-US') );
  
</script><br>

Los representantes de ambas instituciones acordaron unir esfuerzos, recursos y conocimientos científicos y técnicos para desarrollar acciones conjuntas de investigación, desarrollo de tecnología informática, fortalecimiento de capacidades y publicación libre y gratuita de información sobre biodiversidad con la finalidad de contribuir a la conservación, acrecentar el conocimiento y promover la utilización sostenible de la biodiversidad, según las leyes aplicables.







