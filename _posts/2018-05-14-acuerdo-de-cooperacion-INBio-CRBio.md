---
title: Firma del Acuerdo de Cooperación entre INBio y CRBio
date: 2018-05-14 17:27:15 +0200
categories: [" Socios "]
---

<script type="text/javascript"> 

function horaLocal(hileraFechaHora) {
  // The function convert the parameter ISO Date string to the local hour HH:MM.
  var fecha = new Date(hileraFechaHora);
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
  // The function convert the parameter ISO Date string to the UTC shift.
  var dias = ['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat'];
  var fecha = new Date(hileraHora);
  desfase = (0-fecha.getTimezoneOffset())/60;
  if (desfase > 0) {
     desfase = "+" + desfase.toString();
  } else {
     desfase = desfase.toString();
  }
  return "UTC"+desfase;
}

function DiaLocal(hileraFechaHora, lenguaje, lineas) {
  // The function convert the parameter ISO Date string to the day string.
  // lenguaje is the language (English: 0, Spanish: 1)
  // lineas indicates if the result is more than 1 line (No:0, Yes:1)
  var dias = [['Sun', 'Mon', 'Tue, 'Wed', 'Thu', 'Fri', 'Sat'],
              ['Dom', 'Lun', 'Mar', 'Mie', 'Jue', 'Vie', 'Sáb']];
  var meses = [['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec'],
              ['Ene', 'Feb', 'Mar', 'Abr', 'May', 'Jun', 'Jul', 'Ago', 'Set', 'Oct', 'Nov', 'Dic']];

  var fecha = new Date(hileraFechaHora);
  var semana = dias[lenguaje];
  var anno = meses[lenguaje];
  var nombreDia = semana[fecha.getDay()];
  if (lineas = 1) {
    nombreDia = nombreDia + "<br>"
  } else {
    nombreDia = nombreDia + " "
  }
  nombreDia = nombreDia + fecha.getDate() + " " + anno[fecha.getMonth()];
  }
  return nombreDia;
}
</script>


<script type="text/javascript">
  var hileraDiaYHora = '2018-06-14T15:27:15Z';
  document.write( horaLocal(hileraDiaYHora) );
  document.write( UTCLocal(hileraDiaYHora) );
  document.write( DiaLocal(hileraDiaYHora, 1, 1)
</script><br>



El 14 de Junio del 2018, María Auxiliadora Mora, Presidenta de CRBio y Randall García, Director General del INBio, firmaron un Convenio General de Cooperación mutua para el desarrollo de proyectos que contribuyan al <b>cumplimiento</b> de los objetivos de ambos.

Los representantes de ambas instituciones acordaron unir esfuerzos, recursos y conocimientos científicos y técnicos para desarrollar acciones conjuntas de investigación, desarrollo de tecnología informática, fortalecimiento de capacidades y publicación libre y gratuita de información sobre biodiversidad con la finalidad de contribuir a la conservación, acrecentar el conocimiento y promover la utilización sostenible de la biodiversidad, según las leyes aplicables.







